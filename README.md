# tideline-privacy

Public privacy policy site for the [Tideline](https://github.com/oath-hash/tideline)
iOS app, served via GitHub Pages.

The published URL is
[https://oath-hash.github.io/tideline-privacy/](https://oath-hash.github.io/tideline-privacy/)
and is the canonical privacy-policy link from the Tideline App
Store listing.

## What's in here

- `index.html` — the privacy policy itself. Plain HTML, system
  fonts only, no JavaScript, no external resources, no
  tracking. The policy page is as privacy-clean as the app it
  describes.
- `LICENSE` — Creative Commons CC0 1.0. The policy is the
  operative privacy statement for the app, not reusable code;
  CC0 puts it in the public domain so anyone who wants to use
  similar wording for their own privacy-clean app can do so
  without friction.

## Updating

1. Edit `index.html`. Bump the "Effective date" line at the top.
2. Commit and push to `main`. GitHub Pages rebuilds within a
   minute or two.
3. If the change is material (i.e., it changes what data is
   handled or how), call it out in the Tideline App Store
   release notes for the version that ships alongside.

## Source of truth

The policy's factual claims are grounded in the v0.2 privacy
audit at
[`specs/002-v0-2-release/audit-privacy.md`](https://github.com/oath-hash/tideline/blob/main/specs/002-v0-2-release/audit-privacy.md)
in the main repository (zero URLSession / Network.framework
usage, verified at compile time) and the permissions audit at
[`specs/002-v0-2-release/audit-permissions.md`](https://github.com/oath-hash/tideline/blob/main/specs/002-v0-2-release/audit-permissions.md)
(only `NSFaceIDUsageDescription` declared). Any update to the
policy should be re-grounded against these audits.
