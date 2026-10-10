# Bonsai

Melbourne bonsai grow plan — budget materials, 60–90 cm trees, Chinese elm forest plus oak and large-leaf specimens.

## Live site

**https://aionnexusaus.github.io/bonsai/**

## Structure

```
.
├── index.html          # GitHub Pages site (project plan)
├── assets/             # Photos used by the plan
├── plants/             # Optional per-species notes as the collection grows
├── .cursor/rules/      # Project rules for Cursor
├── .gitignore
└── README.md
```

## Local

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Deploy

Pushes to `main` publish via GitHub Pages (root of `main`).
