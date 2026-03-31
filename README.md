# HLTH 207 — Course Tools

Interactive learning tools for **Health Care USA (HLTH 207)** at Towson University.  
Built to work on any phone, tablet, or laptop. No login required. Works offline once loaded.

## Live site

**[your-site-name.netlify.app](https://your-site-name.netlify.app)**  
*(Update this link after you deploy to Netlify)*

---

## How to use this site

Share the Netlify URL with students via Blackboard. They bookmark it and open tools from any device. No app download, no account, no friction.

---

## Folder structure

```
/
├── index.html                        ← Homepage (this is what students see)
├── README.md                         ← This file
└── week10/
    ├── student-app.html              ← "You Just Turned 65" student simulation
    ├── jeopardy.html                 ← LTC Jeopardy pass-and-play game
    ├── projector.html                ← Instructor projector for the simulation
    └── life-cards.html               ← Printable life cards (open in browser, print)
```

Add new weeks by creating a new folder (e.g. `week11/`) and adding a card to `index.html`.

---

## How to add a new activity

1. Create a new HTML file (e.g. `week11/activity.html`)
2. Open `index.html` and copy one of the existing `<a class="tool-card">` blocks
3. Update the `href`, title, description, and color
4. Commit and push — Netlify publishes automatically within seconds

---

## How to update an existing activity

1. Open the HTML file you want to edit
2. Make your changes (update a statistic, fix a question, etc.)
3. Save, commit, push — done

---

## Deploying to Netlify (one-time setup, ~15 minutes)

1. Create a free account at [github.com](https://github.com) if you don't have one
2. Create a new repository called `hlth207-tools` (or any name you like)
3. Upload all files maintaining the folder structure above
4. Create a free account at [netlify.com](https://netlify.com)
5. Click **"Add new site" → "Import an existing project" → GitHub**
6. Select your repository
7. Leave all build settings blank (this is a plain HTML site — no build step needed)
8. Click **Deploy**
9. Netlify gives you a URL like `random-name-123.netlify.app`
10. Optional: rename it to something like `hlth207-tools.netlify.app` in Site Settings → Domain Management

From this point, every time you push a change to GitHub, Netlify republishes automatically.

---

## Files included in this repository

| File | Purpose | Who uses it |
|------|---------|-------------|
| `index.html` | Homepage linking to all tools | Students — bookmark this |
| `week10/student-app.html` | You Just Turned 65 simulation | Students — in class on phones |
| `week10/jeopardy.html` | LTC Jeopardy game | Students — pass device between teams |
| `week10/projector.html` | Scenario slides with instructor notes | Instructor — projected at front of room |
| `week10/life-cards.html` | Printable life cards | Instructor — print and cut before class |

---

*HLTH 207 · Towson University · Statistics updated 2024–2025*
