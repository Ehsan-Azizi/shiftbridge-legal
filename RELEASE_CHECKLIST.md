# ShiftBridge legal release checklist

Updated August 22, 2026.

## Published pages

- Privacy Policy: `https://ehsan-azizi.github.io/shiftbridge-legal/privacy/`
- Terms of Use: `https://ehsan-azizi.github.io/shiftbridge-legal/terms/`
- Support: `https://ehsan-azizi.github.io/shiftbridge-legal/support/`
- Account deletion: `https://ehsan-azizi.github.io/shiftbridge-legal/delete-account/`

## App behavior

- Require Terms acceptance during account creation and retain the acceptance timestamp.
- Round optional location to a broad area before transmission; never store raw device coordinates.
- Offer manual workplace search when location is denied.
- Do not collect the user's personal device name for push delivery.
- Keep Report and Block as separate, readily accessible actions.
- Review safety reports promptly and document moderation actions.
- Restrict calendars and trading to the same workplace, Area, and approved role.
- Treat workplace and role approvals as platform access only, not employment or credential verification.
- Verify in-app account deletion removes all account-linked records, including role requests and reports.

## Apple App Store Connect

- Use a 4+ content rating only if the age-rating questionnaire supports it; this is not a declaration that children are the target audience.
- Update App Privacy for name, email, user ID, workplace/role data, user content, support and safety communications, push token, and optional rounded location sent for nearby search.
- Confirm no tracking or targeted advertising.
- Confirm Privacy Policy, Support, and privacy-choices/deletion URLs.
- Provide App Review with an active demo account and explain external employer approval.

## Google Play Console

- Do not select children as a target audience unless the app is redesigned for Families compliance.
- Update Data Safety for account data, workplace/role information, user content, safety/support data, push token, and optional location processed by Geoapify.
- Confirm the in-app and web account-deletion paths.
- Confirm encryption in transit, retention, and deletion declarations match production.

## Third parties and attribution

- Confirm the Privacy Policy identifies Supabase, Expo, Geoapify, Apple, and Google.
- Keep visible “Powered by Geoapify” and “© OpenStreetMap contributors” attribution while using the free Geoapify plan.
- Restrict and rotate API credentials when needed; never commit secret keys.

## Business identity

- Replace the individual operator name with the exact LLC legal name after formation and before transferring the Apple developer account.
- Use a dedicated domain email and public support/privacy contact when available.
- Have a qualified privacy and business attorney review the final public launch documents.

## Before publication

- Update the effective date whenever policy text materially changes.
- Test every page, link, consent checkbox, report flow, permission denial path, and deletion flow.
- Ensure App Store and Play declarations match the binary being submitted.
