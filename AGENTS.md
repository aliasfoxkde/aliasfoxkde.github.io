# Agent guidance

This repository is a static GitHub Pages site and profile-example gallery. There is no build system or runtime dependency.

## Working rules

- Keep pages usable as static files: no credentials, account tokens, or private profile data in HTML, JavaScript, SVG, or checked-in assets.
- Keep sample values explicitly labeled. Do not claim a chart is live unless its data source and refresh workflow are implemented and documented.
- Preserve responsive layouts, visible keyboard focus, descriptive image text, and reduced-motion behavior when editing interactive pages.
- Keep the examples self-contained and cloneable. Prefer local, optimized assets and browser-native APIs; disclose any external request or dependency.
- The root MIT license covers repository code unless an asset says otherwise. Screenshots in `examples/assets/screenshots/` are captures of separate projects; their project licenses and terms still apply.
- Reference profiles are inspiration only. Write original descriptions, code, SVGs, and layouts; check each upstream license before reusing its assets or source.

## Validation

Run a local preview with `python3 -m http.server 8000` from the repository root. Check the changed routes at desktop and mobile widths, exercise buttons and links, inspect browser-console errors, and confirm local assets resolve. For JavaScript, run `node --check` on the changed file. Check HTML and workflow changes before opening a pull request.

## Main entry points

- `index.html` — portfolio landing page.
- `examples/index.html` — profile widget and chart lab.
- `examples/creative.html` — layout and interaction patterns.
- `examples/projects.html` — screenshot cards with interactive descriptions.
- `examples/svg-library/` — browser-based SVG generator.
- `examples/about.html` — data, licensing, and privacy notes.
