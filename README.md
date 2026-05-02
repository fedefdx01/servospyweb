# Web

Static site scaffold for deploying a public Servo website on Vercel.

## Included

- `index.html`: simple landing page scaffold
- `privacy.html`: public privacy policy page for App Store Connect
- `terms.html`: public terms page for App Store subscriptions
- `styles.css`: shared styles

## Deploy

Point Vercel at the `web` directory as the project root, or copy these files into a dedicated web repo later.

## Before publishing

- Replace `privacy@servo-app.com` in `privacy.html` with your real support or privacy email.
- Replace `privacy@servo-app.com` in `terms.html` with your real support or legal email.
- Review the policy text against your final production data flows.
- Add the deployed `terms.html` URL to App Store Connect or use it from your app description if needed.
