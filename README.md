# BetweenCats public website

Static game information, support, and privacy pages for Maymaybe. No build, package install, external fonts, or JavaScript is required.

## Publish on GitHub Pages

1. Sign in as `Lyt-May` and create a **public** repository named `betweencats-site`.
2. Upload the **contents** of this directory to the repository root, not this enclosing directory. Keep `assets`, `support`, and `privacy` as folders. Upload only this website, not the MiceOut game repository.
3. Commit to `main`. In repository **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and Save.
4. Wait for the deployment to finish. Verify all three URLs below in a signed-out browser. Enable **Enforce HTTPS** if available.

Expected URLs (not verified live until deployment succeeds):

- Home: https://lyt-may.github.io/betweencats-site/
- App Store Connect Support URL: https://lyt-may.github.io/betweencats-site/support/
- App Store Connect Privacy Policy URL: https://lyt-may.github.io/betweencats-site/privacy/

## Before submission

- Confirm the privacy policy matches the final iOS binary and your actual support-email retention practices. Add any identity/contact details required in your distribution regions.
- The site uses Maymaybe as a creator name; this does not replace Apple's personal-account legal seller name.
- Add the real App Store link after publication. The homepage currently describes the iOS release as planned.
- Add the public privacy URL to the iOS app's settings/about UI; this website package does not modify the game.
- Update the policy date whenever its terms change.

Local preview: `python3 -m http.server 4187` from this directory, then open http://localhost:4187/.
