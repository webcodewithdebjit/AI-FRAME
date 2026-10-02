# FrameAI — AI Content Studio for Brands & Creators

FrameAI is a single-page, dark-themed marketing website (exported from Adobe Express) for a fictional AI content studio that turns a brief into ready-to-post content for Instagram, LinkedIn, and X.

The page walks through a four-step workflow, then highlights features like **Brand Voice Lock**, **HyperFrames** short-form video, and **AI avatar presenters**. It follows with platform-specific content cards, three pricing tiers ($29 Starter, $89 Pro, $249 Agency), stats and testimonials, and a closing call to action.

It includes a **"live demo" popup**, but that only fills text templates with whatever you type rather than calling a real AI — the numbers, quotes, and company names are placeholder content. This is a **concept / showcase site**, not a working product.

## Live site

View it here: *(add your GitHub Pages link once enabled — Settings → Pages)*

## What's inside

- `index.html` — the entire site in one self-contained file (styles, layout, demo logic, and all images embedded as base64, so nothing else needs to be uploaded).

## Running it locally

No build step needed — just open `index.html` in a browser, or serve the folder with any static server:

```bash
python3 -m http.server
```

## Deploying with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Set the source to your main branch, root folder.
4. Your site goes live at `https://<your-username>.github.io/<repo-name>/`.

## Disclaimer

This project was built as a hackathon idea/concept piece (BFWAI/HACK 26, PS-02: *AI Content Studio for Brands & Creators*). The "Generate content" demo on the page simulates output by inserting your typed brief into pre-written templates — it does not call any real AI model. Pricing, testimonials, and stats shown are illustrative placeholders, not real figures.
