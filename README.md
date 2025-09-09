# sthef-silva.github.io
Personal résumé website built with HTML and CSS

# CIS 4004 Résumé — GitHub Pages


## 1) Repository setup (first time)
1. Create a GitHub account if needed.
2. Click **New repository** and name it **USERNAME.github.io** (YOUR GitHub username exactly).
3. Set **Public**. Create repo.


## 2) Get it on your computer
```bash
# Install Git (if not already). On Windows, open Git Bash.
# Clone the repo and enter it
git clone https://github.com/USERNAME/USERNAME.github.io.git
cd USERNAME.github.io
```


## 3) Add these files
Create folders/files exactly like the tree above. Put your images into `assets/images/`.


## 4) Commit & push
```bash
git add .
git commit -m "Initial resume site"
git push origin main # or 'master' depending on your repo's default
```


## 5) Enable GitHub Pages
Settings → **Pages** → Source: *Deploy from a branch* → Branch: `main` (root) → Save.
Your site will be live at `https://USERNAME.github.io` within ~1 minute.


## 6) Editing workflow
- Edit files → `git add .` → `git commit -m "Describe change"` → `git push` → refresh site.


## 7) Assignment ZIP for WebCourses
Zip the entire folder (including `assets/`) and upload the ZIP along with your live URL.


---


## Content checklist (meets rubric)
- Name, UCF email, LinkedIn
- Objective (1–2 sentences)
- Education
- Work Experience (omit if none)
- Projects (summary cards on Home + 2 dedicated pages)
- Skills
- Awards/Honors (optional; omit if none)


## Accessibility checklist
- Images have meaningful `alt` text
- Color contrast (AA) — use High Contrast toggle to verify
- Logical heading order: only one `<h1>` per page
- Keyboard: focus rings visible; hamburger & toggles focusable
- Links are descriptive (no "click here")


## Validation
- HTML: https://validator.w3.org/ (Upload each .html or paste URL)
- CSS: https://jigsaw.w3.org/css-validator/
- WAVE: https://wave.webaim.org/ (Enter your site URL)
