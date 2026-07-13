# Rigged website (support + privacy)

Static pages for App Store submission, hosted on GitHub Pages under the
EPLMDenver account.

- `index.html` — support page (App Store "Support URL")
- `privacy.html` — privacy policy (App Store "Privacy Policy URL")

## Publishing

1. Create a public repo under github.com/EPLMDenver, e.g. `rigged`.
2. Copy the contents of this folder into the repo root and push.
3. In the repo: Settings > Pages > Source: "Deploy from a branch",
   branch `main`, folder `/ (root)`. Save.
4. After a minute the pages are live at:
   - Support: https://eplmdenver.github.io/rigged/
   - Privacy: https://eplmdenver.github.io/rigged/privacy.html

Use those two URLs in App Store Connect. If the app's data practices
change (e.g. iCloud sync ships), update `privacy.html` and its
effective date.
