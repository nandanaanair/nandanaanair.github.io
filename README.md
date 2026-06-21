# ✦ nandanaanair.github.io

> Personal portfolio of **Nandana Nair** — UX/UI Designer based in Thane, Maharashtra.  
> Built as a single self-contained HTML file. No frameworks. No build tools. Just design.

[![Live Site](https://img.shields.io/badge/Live%20Site-nandanaanair.github.io-F06B7A?style=for-the-badge&logo=github)](https://nandanaanair.github.io)
[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%20%2F%20CSS%20%2F%20JS-9B7FEA?style=for-the-badge)](https://nandanaanair.github.io)

---

## 🔗 Live Demo

**[https://nandanaanair.github.io](https://nandanaanair.github.io)**

---

## 📌 About

This is my personal portfolio website — designed and coded by me to showcase my UX/UI work, certifications, and creative side. The design reflects my dual nature as both a creative (music, photography, art) and an analytical thinker (research, strategy, systems).

---

## 📂 What's Inside

| Section | Description |
|---|---|
| **Hero** | Animated audio waveform canvas + typewriter role cycling |
| **About** | Bio, stats, duality visual (Creative ↔ Analytical) |
| **Work** | 6 projects with hover-reveal details and case study drawers |
| **Skills** | Design practice, tools, and technical skills |
| **Certifications** | 8 certificates with interactive filter (Google / LinkedIn / Udemy) |
| **Creative** | Music, photography, painting, dance |
| **Contact** | Email, LinkedIn, Behance, Instagram |

### Projects

| Project | Type | Case Study |
|---|---|---|
| Spotify MoodGuru | UX Design · Music Therapy | ✅ Interactive drawer + Figma proto |
| Netflix Redesign | UX Case Study · Streaming | ✅ Interactive drawer + Figma proto |
| HCL Tech Landing Page | UI Design · Enterprise | Figma proto |
| VisionVibes | App Design · E-commerce | — |
| SurMilaap | Platform Design · Music | — |
| Freelancer Dashboard | UI Design · Dashboard | ✅ Interactive drawer + Figma proto |

---

## ⚙️ Tech Stack

```
HTML5        — structure and content
CSS3         — custom design system, animations, responsive layout
Vanilla JS   — canvas waveform, typewriter, scroll reveal, modal drawers
Google Fonts — Playfair Display · Inter · Space Mono
Canvas API   — animated hero waveform (no library)
```

No frameworks. No npm. No build step. One file.

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
# → visit http://localhost:3000
```

---

## ✏️ How to Update

### Change personal details
Open `index.html` and search for the relevant section:

```
Ctrl+F → "nandanaanair03@gmail.com"   ← email
Ctrl+F → "Say hello"                  ← contact section
Ctrl+F → "Selected work"              ← work section
```

### Add a new project card
Find the `<!-- ── WORK ── -->` comment and copy an existing `.wc` block. Update the title, description, tags, and optionally add a Figma link.

### Update certifications
Find the `<!-- ── CERTIFICATIONS ── -->` comment. Copy an existing `.cert-card` block and update the issuer, title, date, and link.

### Add a case study drawer
1. Copy an existing `<div id="cs-netflix" class="cs-overlay">` block
2. Give it a new `id` (e.g. `cs-myproject`)
3. Update the content inside `.cs-dbody`
4. On your project card, update the `wc-cta` link:
   ```html
   onclick="event.preventDefault();event.stopPropagation();openCS('cs-myproject')"
   ```

### Replace the embedded CV
The CV is embedded as a base64 data URI. To update it:
```bash
# Encode your new PDF
base64 -w 0 Your_New_Resume.pdf

# In index.html, find the line starting with:
# href="data:application/pdf;base64,...
# Replace the entire base64 string with the new one
```

---

## 🎨 Design System

| Token | Value |
|---|---|
| Background | `#07051A` |
| Surface | `#100E26` |
| Rose accent | `#F06B7A` |
| Amber accent | `#F5A742` |
| Violet accent | `#9B7FEA` |
| Mint accent | `#5ECFB8` |
| Text primary | `#EDE9F9` |
| Text muted | `#7A6E96` |
| Display font | Playfair Display |
| Body font | Inter |
| Mono font | Space Mono |

---

## 🚀 Deployment

This site is deployed via **GitHub Pages** from the `main` branch.

To update the live site:
```bash
git add index.html
git commit -m "Update portfolio"
git push origin main
# → live in ~60 seconds
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
