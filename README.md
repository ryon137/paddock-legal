# paddock-legal

Public static site hosting PrancyCar's legal documents and account information,
served via GitHub Pages. This is the canonical public source for the URLs
referenced in the PrancyCar mobile app (`LegalLinks`) and the Google Play listing.

Pages:

- `/privacy/` — Privacy Policy
- `/terms/` — Terms of Service
- `/delete-account/` — Account deletion instructions (in-app + email request)

Static HTML only (no build step). Edit the `.html` files directly. The source
of truth for the policy text also lives in the private app repo under
`docs/legal/`; keep the two in sync when updating.
