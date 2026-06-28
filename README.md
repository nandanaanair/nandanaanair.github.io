# ✦ nandanaanair.github.io

> Personal portfolio of **Nandana Nair**, UX/UI Designer based in Thane, Maharashtra.
> Built as a single self-contained HTML file. No frameworks, no build tools, just design.

[![Live Site](https://img.shields.io/badge/Live%20Site-nandanaanair.github.io-C94D72?style=for-the-badge&logo=github)](https://nandanaanair.github.io)
[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%20%2F%20CSS%20%2F%20JS-7858B0?style=for-the-badge)](https://nandanaanair.github.io)

---

## 🔗 Live Demo

**[https://nandanaanair.github.io](https://nandanaanair.github.io)**

---

## 📌 About

This is my personal portfolio website, designed and coded by me to showcase my UX/UI work, experience, certifications, and creative side. The design reflects my dual nature as both a creative (music, art, dance) and an analytical thinker (research, strategy, systems).

---

## 📂 What's Inside

| Section | Description |
|---|---|
| **Hero** | Animated audio waveform canvas + typewriter role cycling, with résumé and contact CTAs |
| **About** | Bio, stats, photo collage (Creative ↔ Analytical) |
| **Experience** | Work history (Website Catalog Executive @ Headphone Zone) and education timeline |
| **Work** | 7 projects with hover-reveal details and interactive case study drawers |
| **Philosophy** | How I think about design, in four principles |
| **Testimonials** | Kind words from people I've worked with |
| **Skills** | Design practice, tools, technical, and soft skills |
| **Certifications** | 8 certificates with interactive filter (Google / LinkedIn / Udemy) |
| **Creative** | Music & singing, painting & digital art, dance |
| **Contact** | Email, résumé, LinkedIn, Behance, Instagram |

### Projects

| Project | Type | Case Study |
|---|---|---|
| Netflix Redesign | UX Case Study · Streaming | ✅ Interactive drawer |
| Spotify MoodGuru | UX Design · Music Therapy | ✅ Interactive drawer |
| Domino's Pizza Redesign | UI/UX · App Redesign | ✅ Interactive drawer |
| Freelancer Dashboard | UI Design · Dashboard | ✅ Interactive drawer |
| Nike Parallax Effect | UI Design · Interaction | ✅ Interactive drawer |
| Desi Dawat | UI Design · 3D Carousel | ✅ Interactive drawer |
| HCL Tech Landing Page | UI Design · Enterprise | ✅ Interactive drawer |

Deeper case studies live on [Behance](https://www.behance.net/nandanaanair).

---

## ⚙️ Tech Stack

```
HTML5        structure and content
CSS3         custom design system, animations, responsive layout
Vanilla JS   canvas waveform, typewriter, scroll reveal, modal drawers
Google Fonts Playfair Display · Inter · Space Mono
Canvas API   animated hero waveform (no library)
```

No frameworks. No npm. No build step. One file.

### Repo files

| File | Purpose |
|---|---|
| `index.html` | The entire site (HTML + CSS + JS in one file) |
| `logo.svg` | Logo and favicon (lowercase n + cursor) |
| `Nandana-Nair-Resume.pdf` | Downloadable résumé, linked from nav and contact |
| `photo-*.jpg` | Hero and about-section photos |
| `project-*.png` | Project card images |

---

## 🖥️ Run Locally

Since it's a single HTML file, there's no setup required:

```bash
# Clone the repo
git clone https://github.com/nandanaanair/nandanaanair.github.io.git

# Open directly in browser
open index.html

# Or serve locally (optional, for testing)
npx serve .
# visit http://localhost:3000
```

---

## ✏️ How to Update

### Change personal details
Open `index.html` and search for the relevant section:

```
Ctrl+F  "nandanaanair03@gmail.com"   email
Ctrl+F  "Say hello"                  contact section
Ctrl+F  "Selected work"              work section
```

### Add a new project card
Find the `<!-- ── WORK ── -->` comment and copy an existing `.wc` block. Update the title, description, tags, and the `openCS('cs-...')` link.

### Update certifications
Find the `<!-- ── CERTIFICATIONS ── -->` comment. Copy an existing `.cert-card` block and update the issuer, title, date, and link.

### Add a case study drawer
1. Copy an existing `<div id="cs-netflix" class="cs-overlay">` block
2. Give it a new `id` (e.g. `cs-myproject`)
3. Update the content inside `.cs-dbody`
4. On the project card, point the `wc-cta` link at it:
   ```html
   onclick="event.preventDefault();event.stopPropagation();openCS('cs-myproject')"
   ```

### Update the résumé
The résumé is a real file in the repo, `Nandana-Nair-Resume.pdf`. Just replace that file (keep the same name) and the nav + contact links pick it up automatically.

---

## 🎨 Design System

| Token | Value |
|---|---|
| Background | `#FFF5F8` |
| Background alt | `#FEEAF2` |
| Rose accent | `#C94D72` |
| Amber accent | `#C46855` |
| Violet accent | `#7858B0` |
| Mint accent | `#3AA090` |
| Text primary | `#1A0C14` |
| Text muted | `#6A3858` |
| Display font | Playfair Display |
| Body font | Inter |
| Mono font | Space Mono |

> Style note: no em dashes or en dashes anywhere in the site copy. Commas, colons, and plain hyphens only.

---

## 🚀 Deployment

This site is deployed via **GitHub Pages** from the `main` branch.

To update the live site:
```bash
git add index.html
git commit -m "Update portfolio"
git push origin main
# live in ~60 seconds
```

---

## 📬 Contact

**Nandana Nair**

| | |
|---|---|
| Email | [nandanaanair03@gmail.com](mailto:nandanaanair03@gmail.com) |
| LinkedIn | [linkedin.com/in/nandanaanair](https://www.linkedin.com/in/nandanaanair/) |
| Behance | [behance.net/nandanaanair](https://www.behance.net/nandanaanair) |
| Instagram | [@nandanaanair](https://www.instagram.com/nandanaanair) |
| Art page | [@illustheticarts](https://www.instagram.com/illustheticarts/) |

---

<p align="center">Designed & coded with ♥ by Nandana Nair · Thane, Maharashtra</p>
