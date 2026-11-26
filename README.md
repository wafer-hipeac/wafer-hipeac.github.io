# Wafer-Scale @ HiPEAC 2027

Website for the HiPEAC 2027 workshop **Wafer-Scale and Post-GPU Computing for AI and HPC: Architectures, Compilers, and Ecosystems**, held in Glasgow on Wednesday 20 January 2027.

The site is static: `index.html`, `style.css` and `assets/`. There is no build step.

## Preview locally

```bash
python3 -m http.server 8000
```

## Deploy (GitHub Pages)

This repository must be named `wafer-hipeac.github.io` so the site is served at the root address <https://wafer-hipeac.github.io/>.
Then go to Settings → Pages → Build and deployment and set **Source: Deploy from a branch**. Pick the branch (for example `main`) and the folder **/ (root)**, then save.

## Editing

- Speakers, organizers and venue details are plain HTML in `index.html`. Search for `speaker`, `org-role` or `ticket`.
- When the program is announced, replace the `.tbd` block in the Program section.
