# Vehicle Damage Score

This project is a static web application that aims to evaluate visible damage on a vehicle image and present a simple, easy-to-understand "damage score" to users. Visual elements and basic scoring logic are provided with HTML/CSS and SVG; the user interface is simple and fast.

## Summary

- Purpose: Visually highlight vehicle damage and provide a short summarized score.
- Target audience: vehicle inspection professionals, insurance staff, or vehicle owners.

## Features

- Damaged area highlighting (visualization using SVG).
- Simple numeric "damage score" calculation — useful for quick comparison and preliminary assessment.
- Single-file (static) setup: `index.html`, images (e.g. `car.svg`), and necessary assets.

## Technology

- HTML, CSS, (optional) JavaScript
- SVG for vector graphics

## Input / Output (Contract)

- Input: User-selected/marked vehicle area or provided visual information.
- Output: A summarized "damage score" in the range 0–100 and visual highlighting.
- Error cases: Missing image, unsupported browser, or corrupted SVG file; the user is shown a clear warning.

## How to run

1. The project is a static web page; you can open the `index.html` file directly in a browser.
2. If you want to run it on a local server (e.g., XAMPP), place the project folder under your `htdocs` and open `http://localhost/vehicle-damage-score/` in your browser.

## Important files

- `index.html` — main application page.
- `car.svg` — vehicle graphic; damage regions can be overlaid on it.
- `Readme.md` — project description in Turkish (this file contains the Turkish version).
- `Readme.en.md` — this English translation.

## Assumptions

1. The project is static and small-scale; no server-side processing is required.
2. The damage score is computed with simple heuristics or predefined rules (no ML).
3. Modern browsers (Chrome, Firefox, Edge, Safari) are supported.

If you need different assumptions (e.g., server-side analysis, ML model, API integration), state them and I will propose the required design changes.

## Development & Next Steps

- Integrate image processing or machine learning for automated damage detection.
- Make the tool interactive: allow users to select regions, add annotations, and support multiple photos.
- Add tests: unit tests and cross-browser compatibility checks.

## License

This project is open source — if you want a license, add a `LICENSE` file and specify the license type.

---

I added this English version (`Readme.en.md`) to the project; tell me if you want a different tone or a single combined README instead.
