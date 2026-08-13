# ShiftBridge legal release checklist

Updated August 13, 2026.

## Published pages

- Privacy Policy: `https://ehsan-azizi.github.io/shiftbridge-legal/privacy/`
- Terms of Use: `https://ehsan-azizi.github.io/shiftbridge-legal/terms/`
- Support: `https://ehsan-azizi.github.io/shiftbridge-legal/support/`
- Account deletion: `https://ehsan-azizi.github.io/shiftbridge-legal/delete-account/`

## Apple App Store Connect

- Confirm the Privacy Policy and Support URLs above.
- Review App Privacy answers for account contact information, user ID, workplace membership, scheduling/user content, support communications, and device identifiers used for push delivery.
- CE Tracker data stays on-device and is not collected by ShiftBridge.
- Confirm the app does not use collected data for tracking or targeted advertising.

## Google Play Console

- Confirm the Privacy Policy URL above.
- Confirm the account-deletion URL above in the Data safety account-deletion section.
- Review Data safety answers for account information, workplace membership, scheduling/user content, support communications, and device identifiers used for push delivery.
- CE Tracker data stays on-device and is not collected by ShiftBridge.
- Confirm encryption-in-transit and deletion declarations match the production configuration.

## Product verification

- Account deletion removes the Supabase authentication account and account-owned database records.
- Account deletion removes registered Expo push tokens and in-app notifications through database cascades.
- Account deletion removes the current user's device-only CE Tracker record.
- Support and deletion instructions use Account -> Delete Account.
- No CE certificate, transcript, nursing license number, patient information, or other CE document upload exists.

## Before publication

- Have a qualified privacy attorney review the final language and applicable jurisdiction-specific requirements.
- Update the effective date if the published text changes again.
- Test every page and email link on mobile and desktop after deployment.
