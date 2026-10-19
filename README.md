# Johnson Ojo — Portfolio

Single-file portfolio site, ready for GitHub Pages.

## 1. Personalise it (5 minutes)

Open `index.html` and edit the block at the top marked **EDIT EVERYTHING ABOUT YOU HERE**:

- `linkedin` — your full LinkedIn URL
- `github` — your full GitHub URL
- `booking` — optional Calendly link (adds a "Book a call" button)
- `cv` — optional, e.g. `assets/Johnson-Ojo-CV.pdf` (adds a "Download CV" button)

### Your photo
Create a folder called `assets` next to `index.html` and put your photo inside it named **`profile.jpg`**.
Portrait (taller than wide) works best — about 800×1000px. Until it's there, the card shows your initials.

### Adding e-commerce (or any) projects
In the `PROJECTS` list there's a commented-out E-commerce template. Copy it once per store:

```js
{
  category: "E-commerce",
  tag: "New build",
  title: "Store name",
  scope: "Catalogue · Checkout · Paystack · Admin dashboard",
  outcome: "Live in 4 weeks, 1,200 orders in month one",
  url: "https://the-live-store.com",
  stack: ["ASP.NET Core", "SQL Server", "Azure"]
},
```

- Projects **with** a `url` show a **Visit site ↗** button and are listed first.
- Projects **without** a `url` show an **Under NDA** badge.
- Each new `category` becomes a filter tab automatically.

## 2. Host it on GitHub Pages (free)

This repo is `Johnfrosh11/JohnsonOjo`, so the site lives at **https://johnfrosh11.github.io/JohnsonOjo/**.

1. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, Save.
2. Every push to `main` redeploys in 1–2 minutes.

Want the shorter address `https://johnfrosh11.github.io`? Rename this repo to `Johnfrosh11.github.io` (Settings → General → Repository name).

Want a custom domain like `johnsonojo.dev`? Buy it, then add it under Settings → Pages → Custom domain and follow GitHub's DNS instructions.
