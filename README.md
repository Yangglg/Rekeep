# Rekeep website publishing checklist

This folder contains a complete, static product website:

- `index.html`: product marketing homepage
- `support.html`: technical support and contact page
- `privacy-policy.html`: privacy policy
- `assets/`: local app icon, product images, and shared styles

Publishing steps:

1. Publish the entire `Legal` folder at a permanent public HTTPS domain.
2. Confirm that `index.html`, `support.html`, and `privacy-policy.html` load without sign-in.
3. Use the hosted `support.html` URL as the Support URL in App Store Connect.
4. Use the hosted `privacy-policy.html` URL under App Privacy.
5. Replace the product page's internal exploration link with the public App Store listing after the app is available.
6. Update the privacy policy and App Store privacy answers whenever the app's data practices change.

The pages have no external fonts, analytics, cookies, or third-party scripts.
