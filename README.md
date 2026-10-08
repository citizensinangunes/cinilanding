# Touros Studio

A responsive coming-soon page for an independent Turkish game studio. Static HTML and CSS, with no dependencies or build step.

## Development

Run from the repository root:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

The centered wordmark is currently a text fallback. Once the original logo image is available, save it as `assets/touros-studio.png` and replace the `.wordmark` element with `<img src="assets/touros-studio.png" alt="Touros Studio">`.

## Hosting

Serve the repository root with a static host. For GitHub Pages, choose the `main` branch and `/ (root)` in Settings → Pages.
