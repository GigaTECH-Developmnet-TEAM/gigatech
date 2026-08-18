# GigaTECH DEVELOPMENT — Website

A single-file, self-contained website for **GigaTECH DEVELOPMENT** covering Home, About, Journey, Team, Service, Technologies, Project and Contact sections on one scrollable page.

---

## 📁 Files in this project

| File | Purpose | Required on server? |
|---|---|---|
| `gigatech-website.html` | The entire website (HTML + CSS + JS + logo + team photos, all embedded) | ✅ Yes |
| `robots.txt` | Tells search engines they're allowed to crawl the site | ✅ Yes |
| `sitemap.xml` | Lists all page sections for search engines | ✅ Yes |
| `README.md` | This file — documentation only | ❌ No (don't upload) |

**Important:** Rename `gigatech-website.html` to `index.html` before uploading — most web servers look for `index.html` as the homepage by default.

---

## 🚀 How to deploy

1. Log in to your hosting control panel (cPanel, Hostinger, GoDaddy, etc.) or connect via FTP.
2. Open **File Manager** and go to the root folder — usually `public_html`, `www`, or `htdocs`.
3. Rename `gigatech-website.html` → `index.html`.
4. Upload `index.html`, `robots.txt`, and `sitemap.xml` into that same root folder.
5. Visit `https://gigatech.net.in` to confirm the site loads.
6. Visit `https://gigatech.net.in/robots.txt` and `https://gigatech.net.in/sitemap.xml` to confirm those load too.
7. (Recommended) Add the site to [Google Search Console](https://search.google.com/search-console) and submit the sitemap URL.

No build step, no npm install, no database — it's a static file that works on any standard web host.

---

## 🧩 What's inside the page

| Section | Anchor | Notes |
|---|---|---|
| Home | `#home` | Hero, trust stats, process steps |
| About | `#about` | Company info + **Meet the Founder** + **Our Team** + brand values |
| Journey | `#journey` | Company timeline / growth story |
| Service | `#service` | 9 service categories with details |
| — | — | Certified Partners (PayU, Cashfree) strip |
| — | — | Technologies marquee (tech stack logos) |
| Project | `#project` | Sample project cards |
| Contact | `#contact` | Lead form + WhatsApp + map |

---

## ✏️ How to edit content

Everything is plain HTML/CSS/JS inside one file — open it in any text/code editor (VS Code, Notepad++, etc.) and search for the text you want to change.

Quick reference of where things live in the file:

- **Company phone/WhatsApp number:** search for `917233023547`
- **Address:** search for `Jahangirpuri`
- **Team members:** search for `team-card` — each person is one block
- **Services:** search for `service-detail`
- **Meta title/description (SEO):** near the top, inside `<head>`
- **Colors:** defined once at the top of the `<style>` block under `:root { --navy: ...; --royal: ...; }` — change a color there and it updates everywhere

---

## 📲 How the Contact Form works

The "Send us your requirements" form does **not** email anyone or use a server. When submitted, it:
1. Formats the entered details into a message.
2. Opens WhatsApp (web or app) with that message pre-filled, addressed to `+91 7233023547`.
3. The visitor just has to press **Send** in WhatsApp.

No backend, no database, no monthly form-service cost.

---

## 🤖 About the AI Assistant (chat widget)

The floating chat bubble is a **rule-based assistant**, not a live AI model. It matches keywords in the visitor's message against a built-in knowledge base covering:
- Company info (services, pricing approach, team, founder, process)
- 18+ project types (e-commerce, CRM, delivery app, etc.) with feature suggestions
- 18+ technology topics (React, Flutter, AI/ML, databases, cloud, etc.)
- Basic Hindi/Hinglish detection and replies

**Limitation:** It cannot answer arbitrary/unexpected questions the way a real AI model (ChatGPT/Claude) can — it will fall back to a generic helpful response instead. Connecting a real AI backend would require a server and an API key, which is outside the scope of a static file.

---

## 🌐 External dependencies (needs internet to load fully)

Everything essential (logo, team photos, layout, forms) is embedded and works **offline**. A few decorative/enhancement pieces load from the internet:

| What | Source | Fails gracefully if offline? |
|---|---|---|
| Fonts (Poppins, Inter, Manrope) | Google Fonts | Yes — falls back to system font |
| Technology logos (React, Java, Python, etc.) | Devicon (cdnjs, MIT license) | Yes — icon just won't render |
| Section banner photos (team collaboration, code screens, etc.) | Pexels (free stock photos) | Yes — image space stays blank |
| Office location map | Google Maps embed | Yes — map area stays blank |

---

## 🔍 SEO notes

Already configured:
- Title, meta description, keywords
- Open Graph + Twitter Card tags (for social sharing previews)
- JSON-LD structured data (`ProfessionalService` schema — address, phone, services, founder, socials)
- `robots.txt` + `sitemap.xml`
- Favicon (browser tab icon)
- Single `<h1>`, proper heading hierarchy

**What SEO code alone cannot do:** guarantee a top Google ranking. That also depends on things outside this file — a live HTTPS domain, a **Google Business Profile**, genuine customer reviews, backlinks from other sites, and regular content updates. See the deployment section above to get the technical side live first.

---

## 🖥️ Browser support

Works in all modern browsers (Chrome, Edge, Firefox, Safari — desktop and mobile). Uses standard CSS Grid/Flexbox and vanilla JavaScript — no framework, no build tools required.

---

## 🎨 Brand reference

Built to match the GigaTECH DEVELOPMENT brand guide:
- **Colors:** Deep Navy, Royal Blue, Purple accent, Orange/Green supporting
- **Fonts:** Poppins (headings), Inter (body), Manrope (labels/UI)
- **Tagline:** Build. Innovate. Scale.

---

*Last updated: August 2026*
