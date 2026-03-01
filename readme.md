# abhisheksriram.com

Personal website and professional portfolio for Abhishek Sriram.

Built with:
- Hugo (extended)
- Blowfish theme
- Cloudflare Pages

---

## Overview

This repository contains the source for my personal website.
It highlights:
- Experience
- Projects
- Writing
- Contact / booking

The goal is to keep the system lightweight, fast, and easy to maintain.

---

## Local development

Install Hugo (extended version recommended).

macOS (Homebrew):

```bash
brew install hugo
```

Run the dev server (includes drafts):

```bash
hugo server -D
```

Open:

```text
http://localhost:1313/
```

Hugo will live-reload when you edit files in `content/` or `hugo.toml`.

---

## Production build

Generate a production build:

```bash
hugo
```

Output directory:

```text
public/
```

Note: `public/` is build output and should not be committed.

---

## Deployment (Cloudflare Pages)

Cloudflare Pages is connected to the `main` branch.

Build settings:
- Framework preset: Hugo
- Build command: `hugo`
- Output directory: `public`

Every push to `main` triggers an automatic deployment.

---

## Project structure

```text
content/     Site content (pages, posts, sections)
static/      Static assets (images, resume PDFs, favicons)
themes/      Blowfish theme
hugo.toml    Site configuration
public/      Generated site output (ignored)
```

---

## Notes

- Keep `public/` out of git.
- Put your resume PDF in `static/resume/` (ex: `static/resume/Abhishek_Sriram_Resume.pdf`).

---

© 2026 Abhishek Sriram