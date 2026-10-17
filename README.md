# Touros Studio

A responsive coming-soon page for an independent Turkish game studio. Static HTML and CSS, with no dependencies or build step.

## Development

Run from the repository root:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

The burgundy version `touros-burgundy.png` is centered on the page and scales proportionally for desktop and mobile screens. The original blue logo is retained as `Touros Studio Logo.png`.

## Hosting

Serve the repository root with a static host. For GitHub Pages, choose the `main` branch and `/ (root)` in Settings → Pages.

## Triplaza privacy policy

The policy is served at `/triplaza/privacy` from `triplaza/privacy/index.html`. It describes the implementation inspected at cini commit `e77bc711f448ab533de99499566263d27f6ef1c9`. The `tur15` Task 9 plan specifies a future AdMob + UMP integration; it is not implemented in that revision. Update the policy and App Store privacy disclosures before activating advertising. The current play-data switch defaults to enabled; the policy does not claim prior consent.

## Games

The home page Games section links to `/triplaza`, served from `triplaza/index.html`. Its icon is copied from the game's original `design/art/app-icon.webp` to `assets/triplaza-icon.webp`. When the iOS game launches, replace the release-status label in `triplaza/index.html` with the confirmed App Store link, and update the home card status. No placeholder download link is active.
