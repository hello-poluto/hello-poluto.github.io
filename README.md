# POLUTO — A Physical AI Work Companion

POLUTO's official project website: a minimal introduction to an evolving
physical AI work companion. The site presents the motivation and five proposed
interaction states, with room to grow into a project archive.
The `paper/` page provides a web reading of the supplied research paper, with
section navigation, figures, and linked references. It summarizes the paper's
design and prototype account while identifying planned work and open questions.

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
- `paper/index.html` and `paper/paper.css`: research paper reading page and styles.
- `paper/assets/`: earlier web images of paper figures.
- `assets/images/fig/`: supplied figure originals and poster PDF, with separate
  optimized WebP copies used by the paper page.
- `assets/images/`: approved hero photo and optimized web copies.
- `AGENTS.md`: development and content-integrity rules.

The supplied `Untitled_1.2.6.jpg` is preserved byte-for-byte as
`assets/images/poluto-original.jpg`. The hero uses WebP copies at 800 and 1920
pixels wide, with a JPEG fallback. Web copies omit original metadata.
Do not modify the original when preparing new derivatives.

The five states are proposals, not claims of completed implementation.
To add an approved state photo, place an image inside that state's `<dd>` with
descriptive `alt`, intrinsic `width`/`height`, and `loading="lazy"`. No empty
image slots are rendered. Add a POLUTO in Action section at the marked HTML
comment only after a real video is supplied; include an accessible title and
captions as appropriate. There is currently no video player or hidden embed.

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
