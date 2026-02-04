# Portable Admin UI (Luisito-Wichin)

This folder contains an **offline-capable** UI so someone else can change the redirect destination without editing code.

## What it does
- Generates a new 	arget.json file containing the destination URL.
- The QR code stays the same because it points to:
  https://aureumprime.github.io/qr-redirect/Luisito-Wichin/

## How to use (non-technical)
1) Open index.html (double-click).
2) Paste the new destination URL (must start with http:// or https://).
3) Click **Download target.json**.
4) Upload the new 	arget.json to GitHub (replace the existing one):
   - Recommended: open the GitHub edit page:
     https://github.com/AUREUMPRIME/qr-redirect/edit/main/Luisito-Wichin/target.json
   - Paste the JSON content and commit.
5) Wait for GitHub Pages to update, then test:
   - https://aureumprime.github.io/qr-redirect/Luisito-Wichin/

## Notes
- Whoever updates the link must have permission to commit to this GitHub repository.
- Do not share repo write access broadly.
