# Personal Portfolio & Learning Roadmap Website

A fast, modern, and forward-looking one-page scrolling portfolio designed specifically for a prospective **B.Tech Artificial Intelligence student** aiming toward **Machine Learning Engineering** and **Software Development** roles.

Built with pure, zero-dependency **HTML5, CSS3, and JavaScript**, making it instant to load, responsive across all devices, and free to deploy anywhere.

---

## 📁 Project Structure

```
d:/darshan/
├── index.html        # Main single-page website with all scrolling sections
├── resume.html       # ATS-friendly, clean printable HTML resume & CV
├── css/
│   └── style.css     # Modern CSS custom properties, dark/light themes, animations
├── js/
│   └── main.js       # Theme toggle, clipboard copy toast, scroll spy, menu drawer
└── README.md         # Customization and deployment guide
```

---

## ⚡ Key Features Included

- **Forward-Looking & Credible**: Avoids empty placeholders by structuring planned work into deliberate **Project Blueprints / Architecture Specs** and an **Evolving Competency Tree** (Foundations -> Applied ML -> Future Horizons).
- **High-Visibility Contact & Resume**: Sticky header resume link, 1-click email copy button with toast animation, and a dedicated contact card.
- **Dark / Light Mode**: Defaults to a developer-friendly dark theme with full light mode toggle support, persisted in `localStorage`.
- **ATS-Friendly Printable Resume**: Standalone `resume.html` with a one-click **"Print / Save as PDF"** button.
- **100% Lightweight & Zero Bloat**: No framework lock-in or heavy npm build steps required.

---

## 🛠️ How to Customize

All key customization points are marked with `<!-- EDIT: ... -->` comments in the HTML files.

### 1. Update Name & Personal Bio
- Open `index.html`.
- Search for `Darshan` and replace with your full name.
- Customize the tagline in the `<section id="hero">` and `<section id="about">`.

### 2. Update Social & Contact Information
- Open `index.html` and `resume.html`.
- Replace `darshan@example.com` with your real email address.
- Update the GitHub and LinkedIn profile links in the hero and contact sections.

### 3. Updating the Learning Tree / Skills
- In `index.html`, navigate to `<section id="skills">`.
- As you master new libraries or courses, you can easily move cards between **Tier 01 (Core Foundations)**, **Tier 02 (Applied ML)**, and **Tier 03 (Future Horizons)**.

### 4. Updating Project Blueprints
- In `index.html`, locate `<section id="projects">`.
- As you build projects, update the status chips (e.g., from `In Development` to `Completed`), add live demo links, and link your real GitHub repositories.

### 5. Adding New Field Notes / Blog Posts
- In `index.html`, locate `<section id="notes">`.
- Add new `<article class="note-card">` cards whenever you publish a writeup or want to highlight a learning milestone.

---

## 🚀 1-Minute Deployment Options (100% Free)

### Option A: GitHub Pages (Recommended)
1. Initialize git and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
2. On GitHub, go to your repository **Settings** -> **Pages**.
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Your website will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/` in under 60 seconds!

### Option B: Vercel or Netlify
1. Drag and drop this folder directly into [Vercel](https://vercel.com) or [Netlify Drop](https://app.netlify.com/drop).
2. It deploys immediately with SSL and custom domain support.

---

## 📄 Generating Your PDF Resume
1. Open `resume.html` in any browser (Chrome, Edge, Safari, Firefox).
2. Click the top-right **"Print / Save as PDF"** button (or press `Ctrl+P` / `Cmd+P`).
3. Set destination to **"Save as PDF"** and margins to **"Default"**.
4. You now have a clean, ATS-compliant PDF resume ready to send out!
