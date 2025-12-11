# Nike Store — Frontend Asset Collection

This repository contains a curated set of HTML templates, CSS styles, fonts, icons, and JavaScript utilities intended to accelerate the development of a high-quality Nike storefront prototype or landing experience.

**Highlights**
- **Polished UI assets:** Ready-to-use HTML and CSS for fast prototyping.
- **Comprehensive icon set:** Font Awesome assets and SVGs included under `icons/`, `svgs/` and `webfonts/`.
- **Typography & fonts:** Local font bundles and specimen files under `fonts/`.
- **Minimal JS utilities:** Small, focused client scripts under `js/` for interactivity.

**Quick Start**
- **Preview locally:** Open `html/index.html` or `html/form.html` in your browser.
- **Run a simple HTTP server (recommended):**

```bash
# from the project root
python3 -m http.server 8000
# then open http://localhost:8000/html/index.html
```

**Recommended Workflow**
- Use the files in `html/` as starting points for pages and prototypes.
- Keep theme and component styles in `css/` and `css/style.css` for overrides.
- Manage icons from `icons/` and `svgs/` — the `metadata/` folder contains metadata and families for quick lookups.

**Tech & Assets**
- **HTML:** Lightweight templates in `html/`.
- **CSS:** Base and vendor CSS in `css/` and `icons/css/` (Font Awesome sources).
- **JavaScript:** Utility scripts in `js/` and `icons/js/`.
- **Icons & Fonts:** `icons/`, `svgs/`, and `webfonts/` contain the iconography and font files used by the UI.

**Project Structure**
- `html/` : Page templates (entry points and forms).
- `css/`  : Project styles and overrides (`style.css`).
- `js/`   : Small scripts for UI behavior (`script.js`).
- `fonts/`: Local font packages and specimens.
- `icons/`: Font Awesome distribution, metadata, and build artifacts.
- `imgs/` : Image assets used by templates.

**Customization & Development**
- To adapt this collection for a brand or product, replace fonts in `fonts/`, update variables in `css/style.css`, and swap imagery in `imgs/`.
- To rebuild or extend icon fonts, consult files inside `icons/metadata/` and the `scss/` sources under `icons/scss/`.

**Contributing**
- Small improvements, design fixes, and asset updates are welcome. Open a PR with a clear description and preview screenshots when applicable.

**License & Attribution**
- Review the `icons/LICENSE.txt` for third-party icon licensing (Font Awesome). Other assets in the repository may carry their own license or attribution—check individual folders.

**Contact**
- For questions or collaboration requests, open an issue in this repository or reach out to the project maintainer.

