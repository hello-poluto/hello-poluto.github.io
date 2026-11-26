# POLUTO — A Physical AI Work Companion

POLUTO's official project website: a photo-led account of the V1 and V2
prototypes and the making of a physical AI work companion.
The `paper/` route currently shows a short design report holding page while
submissions are under review. The homepage remains the public introduction to
the project and links to that holding page.

## Local preview

Open `index.html` directly in a browser. No installation or build is needed.
For an HTTP preview, run this from the repository directory with Python installed:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Visit http://127.0.0.1:8000 and stop the server with Ctrl+C.

## Editing

- `index.html`: English content, page structure, and sharing metadata.
- `styles.css`: layout, typography, and responsive styles.
- `paper/index.html`: temporary holding page for the former research reading page.
- `paper/paper.css` and `paper/assets/`: retained paper-page styles and web images.
- `assets/images/fig/`: supplied figure originals and poster PDF, with separate
  optimized WebP copies retained for future use.
- `assets/images/`: approved hero photo and optimized web copies.
- `assets/pics/`: supplied V1 and V2 photos. The `web/` subfolder contains
  optimized copies used on the homepage; the JPEGs remain as supplied.
- `AGENTS.md`: development and content-integrity rules.

The supplied `Untitled_1.2.6.jpg` is preserved byte-for-byte as
`assets/images/poluto-original.jpg`. The hero uses WebP copies at 800 and 1920
pixels wide, with a JPEG fallback. Web copies omit original metadata.
Do not modify the original when preparing new derivatives.

The homepage follows the supplied first-person V1 and V2 story. The detailed
research reading page is not currently shown. There is no video player or hidden
embed on the public pages.

## GitHub Pages

This is a build-free static site, intended for https://hello-poluto.github.io/.
After explicit approval to publish, confirm the repository's current
Settings → Pages source before changing it. For branch-based publication,
the branch containing these files and its `/ (root)` folder can serve the site.
If the existing source uses Actions, review that configuration before changing
the deployment method. No deployment workflow is required by this implementation.

Commit, push, GitHub settings changes, and deployment require explicit approval.
No such action is performed by opening the site locally. A push to an existing
Pages publishing branch may publish immediately, so review its settings first.

Use only approved public material. Files in a public repository, including
original images and Git author metadata, can be visible even when not linked
on the website. The website contains no personal account links, tracking,
third-party scripts, or external fonts.
