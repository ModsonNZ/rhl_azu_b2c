# Regal Portal — sign-in page assets

Static assets for a branded Azure AD B2C custom page.

This repository is public only because the hosting endpoint has to be reachable
by the browser during sign-in. It contains presentation files and nothing else.
Configuration and deployment are documented internally.

| File | |
|---|---|
| `regal-signin.html` | the page template |
| `preview.html` | generated — open from disk to view |
| `regal-truck.jpg` | photograph |
| `regal-logo.svg` | logo, light backgrounds |
| `regal-logo-white.svg` | logo, dark backgrounds |

Edit `regal-signin.html`. `preview.html` is generated from it and changes made
there are lost.

All assets are referenced by relative path and must stay in the same directory.
