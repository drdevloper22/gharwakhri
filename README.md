# Gharwakhari — Authentic Style for Every Home & Lifestyle

A static e-commerce showcase website for **Gharwakhari**, featuring home decor, gift items, and lifestyle products. Hosted via GitHub Pages.

## Live URL

`https://<your-username>.github.io/<repo-name>/`

## GitHub Pages Setup

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under Source: choose branch `main`, folder `/docs`
4. Click **Save** — your site goes live in ~1 minute!

## Project Structure

```
gharwakhri/
├── docs/               ← GitHub Pages root (served publicly)
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   └── css/
│       ├── style.css
│       ├── contact.css
│       └── login.css
├── static/             ← Original CSS source files
├── templates/          ← Django backend templates
├── .gitignore
└── README.md
```

## Features

- Responsive navbar with hamburger menu
- Product catalogue: Home Decor, Gifts, Lifestyle
- Add to Cart and Wishlist (localStorage)
- Google Maps store location
- Newsletter subscription
- Contact & About pages
