# Bonsai

Melbourne bonsai grow plan with three named projects:

1. **Elm forest** — 5 or 7 Chinese elms → one group planting (~60–90 cm)
2. **Oak solos** — English oaks as individual trees (~60–90 cm)
3. **Feijoa solo** — pineapple guava (`Acca sellowiana`), evergreen (~60–90 cm)

**Start:** Phase 0 in October (establish outdoors, sort, prep boxes). **Build:** P1/P2 in Aug–mid Sep; P3 hard root work in September (evergreen). Loquat is out of scope.

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
