<div align="center">

# 🏠 LocalNest — Website
### The landing page for the LocalNest extension

**AI that reads your project first. And changes nothing until you say so.**

[![Live Site](https://img.shields.io/badge/Live_Site-localnest.nitinkumar.me-0d9488?style=for-the-badge)](https://localnest.nitinkumar.me)
[![Extension](https://img.shields.io/badge/Extension-v0.9.25-8b5cf6?style=for-the-badge)](https://open-vsx.org/extension/localnest/localnest-antigravity)
[![Stack](https://img.shields.io/badge/Stack-HTML_%7C_CSS_%7C_JS-0f172a?style=for-the-badge)](https://github.com/1nc24cs146-cmyk/localnest-website)

[🌐 Visit the page](https://localnest.nitinkumar.me) •
[✨ Sections](#-whats-on-the-page) •
[🔄 Live numbers](#-how-the-numbers-stay-live) •
[🚀 Preview locally](#-preview-locally)

</div>

---

## 📊 At a glance

| | |
|---|---|
| **Live page** | https://localnest.nitinkumar.me |
| **Extension** | `localnest.localnest-antigravity` — v0.9.25 on Open VSX |
| **Downloads** | 2,328 on Open VSX (4 Nov 2026 — the live count is shown on the page itself) |
| **Reviews** | 2 reviews, averaging 5.0 (4 Nov 2026) |
| **Editor** | Antigravity |
| **Stack** | One self-contained `index.html` plus `CNAME` and `logo.svg` — HTML, CSS and JS, no build step |

## 🌟 What it is

The public page for LocalNest, a local-first AI coding agent for Antigravity. It runs on models pulled with Ollama on the user's own computer — code never leaves the machine, and there is nothing to sign up for. The page explains how it works, shows an interactive panel preview, and links to the install and the reviews.

## ✨ What's on the page

| Section | What you get |
|---|---|
| 🦸 **Hero** | Version pill, the pitch, install buttons, and an interactive panel preview (tabs, modes, model picker, export chat) |
| **01 — How it works** | Ask / Plan / Agent, with workspace inspection before any code is written |
| **02 — Modes** | The sidebar modes and what each one is for |
| **03 — Review first** | Code review before write — the product feature, not user reviews |
| **04 — Setup** | Install Ollama, pick a model, open the panel |
| **05 — Models** | Which local models to pull and why |
| **06 — Questions** | Frequently asked questions |
| ⬇️ **Get the extension** | Install links to the Open VSX listing |
| ⭐ **07 — Reviews** | A button straight to the extension's Open VSX page, where reviews are written (sign-in to Open VSX needed). This section is `user-reviews` so it never collides with the product's `review` section |

## 🔄 How the numbers stay live

The page fetches `https://open-vsx.org/api/localnest/localnest-antigravity` in the browser on every load and updates the version and download count shown — the numbers in this README are only a snapshot from 4 Nov 2026. If the fetch fails (offline, or the listing is down), the page keeps its fallback text instead of breaking. Note: a plain static read of the page shows the fallback numbers, not the live ones — the live numbers only appear in a real browser render.

## 🎨 Design notes

- Tighter layout (1240px wrap, 40px section gaps, 32px on mobile) with CSS-only 3D animation: floating perspective shapes in the hero and a 3D-tilting panel on hover — no JavaScript library, shapes hidden on small screens, all animation off under `prefers-reduced-motion`
- The namespace is still unverified on Open VSX, so the listing carries a not-a-verified-publisher note

## 🚀 Preview locally

```bash
# from this folder — any static server works, or just open the file
python3 -m http.server 8000
# then open http://localhost:8000/
```

## 🌍 Deploy

Hosted on GitHub Pages from this repo, served at `localnest.nitinkumar.me` via the `CNAME` file. After a push, the live page can lag a few minutes behind the repo — hard-refresh if you just pushed and the page still looks old.

## 👨‍💻 Author

**NitinKumar Hiremath** — [LinkedIn](https://www.linkedin.com/in/nitinkumar-h-701157381/) · [GitHub](https://github.com/1nc24cs146-cmyk)
