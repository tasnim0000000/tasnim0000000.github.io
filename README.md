# Tasnim Ahmed — Portfolio

Personal portfolio website for Tasnim Ahmed — UI/UX & Frontend Developer Intern at
[EXITO](https://exitobd.com), CSE undergraduate at Southeast University, and researcher
in smartwatch sensing & computer vision for healthcare.

Built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step.

Live at: `https://tasnim0000000.github.io`

---

## 📁 Folder Structure

```
tasnim0000000.github.io/
├── index.html                     ← Main entry point (all sections)
├── css/
│   └── style.css                  ← All styles (design tokens, layout, animations)
├── js/
│   └── main.js                    ← Cursor, scroll reveals, theme toggle, counters
├── assets/
│   └── img/
│       ├── profile.jpg
│       └── projects/
│           ├── pawpal.jpg
│           ├── studyflow.jpg
│           └── coxs-canvas.jpg
└── README.md
```

Every image slot has an `onerror` fallback baked into `index.html`, so **the site
works perfectly fine even before you add any photos** — it just shows initials/text
placeholders until real images are dropped in.

---

## 🖼️ Adding Photos (step by step)

1. **Profile photo** → save as `assets/img/profile.jpg`
   - Portrait orientation, at least 800×1000px, good lighting, face/shoulders centered.
   - Full instructions: `assets/img/PLACE_PHOTOS_HERE.md`

2. **Project screenshots** → save into `assets/img/projects/`
   - `pawpal.jpg` — a screenshot of the PawPal JavaFX app (login screen or a dashboard)
   - `studyflow.jpg` — a screenshot of the StudyFlow dashboard/Kanban board
   - `coxs-canvas.jpg` — a rendered frame from the Cox's Canvas OpenGL scene
   - Landscape orientation, roughly 800×450px (16:9).
   - Full instructions: `assets/img/projects/PLACE_PHOTOS_HERE.md`

3. Commit and push — GitHub Pages picks up the new images automatically, no build step needed.

---

## 🧩 What's on the site

- **Hero** — name, role (UI/UX & Frontend Developer, interning at EXITO), quick stats
- **About** — background, university, portrait
- **Skills** — UI/UX Design, Frontend Dev, Dev Tooling, CS Foundations, and
  **AI & Healthcare Research**
- **Experience** — EXITO internship (UI/UX & Frontend Developer Intern) + Southeast
  University B.Sc. in CSE
- **Research** — smartwatch sensing & computer vision for healthcare, ongoing
- **Projects** — real repos, pulled directly from GitHub:
  - **[PawPal](https://github.com/tasnim0000000/PawPal)** — JavaFX + MySQL desktop
    pet marketplace with buyer/seller/admin dashboards
  - **[StudyFlow](https://github.com/tasnim0000000/StudyFlow)** — React + TypeScript +
    Supabase student productivity platform (tasks, notes, planner, analytics)
  - **[Cox's Canvas](https://github.com/tasnim0000000/Cox-s-Canvas)** — C++ / OpenGL /
    GLUT real-time 3D simulation of Laboni Point, Cox's Bazar
- **Contact** — one email (`tasnimtbh123@gmail.com`), GitHub, LinkedIn — nothing else

---

## 🚀 Hosting on GitHub Pages

This repo is already named `tasnim0000000.github.io`, so:

1. Push changes to the `main` branch
2. Go to **Settings → Pages**
3. Source should be: **Deploy from branch → main → / (root)**
4. Site goes live at `https://tasnim0000000.github.io` within a minute or two

## 🛠️ Local Preview

No build step — just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## ✏️ Customizing Further

- **Colors/fonts** — all design tokens are CSS variables at the top of `css/style.css` (`:root`)
- **Adding a 4th project** — copy one `.project-card` block in the `#projects` section
  of `index.html`, update its text/tags/links, and drop a matching screenshot in
  `assets/img/projects/`
- **Resume** — add a PDF to `assets/` and link it from the "Hire Me" button if wanted
- **Research section** — currently one focused write-up on smartwatch + CV healthcare
  research; can be expanded into multiple cards the same way projects are, if more
  research areas come up later

## 🎨 Design Features

- Dark/light mode toggle
- Film grain texture overlay
- Custom magnetic cursor
- Animated word-reveal hero headline
- Scroll-triggered reveal animations
- Skills ticker marquee
- Floating orb background effects
- Counter animations on stats

## 📬 Contact Info

- Email: tasnimtbh123@gmail.com
- GitHub: [tasnim0000000](https://github.com/tasnim0000000)
- LinkedIn: [the-tasnim-ahmed](https://www.linkedin.com/in/the-tasnim-ahmed)
