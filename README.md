# Shivam Asthana — Personal Portfolio

A static personal portfolio introducing Shivam Asthana, selected work, professional background, and contact options. Includes a homepage and dedicated FounderOS, RetainIQ, and ScaleFlow case studies.

## Run locally
Open `index.html` directly in a browser, or run this from the repository root:

```bash
python -m http.server 8080 --bind 127.0.0.1
```

Visit http://127.0.0.1:8080. The website uses HTML and CSS, with no JavaScript required. No build step, backend, API keys, Python package dependencies, or running Streamlit applications are needed.

## Files and updates
- `index.html`: introduction, selected work, about, and contact.
- `founderos.html`, `retainiq.html`, `scaleflow.html`: individual case studies.
- `assets/styles.css`, favicon, and screenshot assets: shared presentation.
- `.nojekyll`: static GitHub Pages configuration.

Reuse the existing project-card markup for future work. All internal page and asset references are relative, including the copied application screenshots; nothing reads from sibling application folders.

## Content status
FounderOS has actual desktop captures and ScaleFlow has an existing mobile evidence capture, all using fictional demonstration data. RetainIQ and the ScaleFlow overview use clearly labelled screenshot placeholders. Replace those with real captures when available. Contact details and public application/source destinations remain unavailable plain text until exact links are provided.

Case studies describe portfolio prototypes without deployment or performance claims. ScaleFlow's optional local investigation is described without claiming verified live autonomy.

## GitHub Pages — when publication is authorized
1. Create the intended repository and push these prepared files with `index.html` at its root.
2. In Settings → Pages, choose Deploy from a branch, then `main` and `/ (root)`.
3. Save and use the URL GitHub provides. Relative paths support project-site subdirectories.

GitHub Pages serves this website only; it cannot execute the three Python applications. No GitHub repository or deployment was created during local preparation. Final screenshots, contact details, and application/source links still need content updates before publication.
