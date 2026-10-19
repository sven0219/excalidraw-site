# Excalidraw on GitHub Pages

Static Excalidraw frontend built from pinned upstream commit `e1b7aacb356a492aa1e0fc6eb57b8896124027f0`.

GitHub Actions builds and deploys the site on every push to `main`. The build uses relative asset paths so it works at both the default project URL and a custom-domain root.

Regular drawings are stored in the visitor's browser, not in this repository. Export important drawings as `.excalidraw` files. GitHub Pages is static hosting and does not provide its own sharing or collaboration backend.

Custom domain: `excalidraw.svenshen.me`. The `excalidraw` DNS record is proxied through Cloudflare (orange cloud). The site is served by GitHub Pages behind Cloudflare.

Upstream: https://github.com/excalidraw/excalidraw (MIT License).
