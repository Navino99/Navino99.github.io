# Naveen Jeevanantham — GRC Portfolio

> Personal portfolio website for **Naveen Jeevanantham**, GRC Analyst & ISO 27001:2022 Lead Implementer.

---

## 🚀 Quick Start

No build tools, no dependencies. It's a single HTML file.

```bash
# Option 1 — Open locally
open naveen-portfolio.html

# Option 2 — Serve locally
npx serve .
# or
python3 -m http.server 8080
```

---

## 📁 File Structure

```
naveen-portfolio.html   ← Everything in one file (HTML + CSS + JS)
README.md
```

---

## 🌐 Deployment

### Vercel (Recommended)
1. Go to [vercel.com](https://vercel.com) → **New Project**
2. Upload or drag in `naveen-portfolio.html`
3. Vercel auto-deploys → you get a live URL instantly

### GitHub Pages
1. Create a new repo (e.g. `naveen-portfolio`)
2. Rename the file to `index.html`
3. Push to the `main` branch
4. Go to **Settings → Pages → Source: main branch**
5. Live at `https://yourusername.github.io/naveen-portfolio`

### Netlify
1. Go to [netlify.com](https://netlify.com) → **Add new site → Deploy manually**
2. Drag & drop `naveen-portfolio.html`
3. Done — live URL in seconds

---

## ✏️ Customisation Guide

All content is in plain HTML. Find the section you want and edit directly.

| What to change | Where to find it |
|---|---|
| Name / title | `#hero` → `.hero-name`, `.hero-sub` |
| Stats (ISO, frameworks…) | `#hero` → `.hero-stats` |
| About text | `#about` → `.about-text` |
| Contact details | `#about` → `.info-grid` and `#contact` |
| Work experience | `#experience` → `.exp-bullets` |
| Certifications | `#certifications` → `.cert-grid` |
| Frameworks grid | `#frameworks` → `.fw-grid` |
| Case studies | `#cases` → `.case-grid` |
| Accent color (cyan) | `:root` → `--cyan` |
| Gold color | `:root` → `--gold` |
| Background color | `:root` → `--bg` |

---

## 🏅 Certifications Featured

| Credential | Issuer | Link |
|---|---|---|
| ISO/IEC 27001:2022 Lead Implementer | Mastermind Assurance | [View Certificate](https://learn.mastermindassurance.com/certificates/mqetr4cikm) |
| Cybersecurity Job Simulation | Mastercard · Forage | — |
| Cybersecurity Analyst Simulation | TCS · Forage | — |
| Shields Up Simulation | AIG · Forage | — |
| Cyber Job Simulation | Deloitte Australia · Forage | — |

---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| `--cyan` | `#00e5ff` | Primary accent, links, tags |
| `--gold` | `#f5a623` | Featured cert, highlights |
| `--bg` | `#060912` | Page background |
| `--bg2` | `#0c1120` | Card/section background |
| `--white` | `#eef2ff` | Primary text |
| `--muted` | `#7a8aaa` | Secondary text |

**Fonts:** [Syne](https://fonts.google.com/specimen/Syne) (headings) · [Fraunces](https://fonts.google.com/specimen/Fraunces) (body) · [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) (labels/code)

---

## 📬 Contact Form

The contact form uses a `mailto:` link — no backend needed. Clicking **Send Message** opens the user's email client pre-filled with the form data sent to `naveenjeeva99@gmail.com`.

To use a real form backend, replace the `handleSubmit` function with a [Formspree](https://formspree.io) or [EmailJS](https://emailjs.com) integration.

---

## 📄 License

Personal portfolio — all rights reserved © 2025 Naveen Jeevanantham.
