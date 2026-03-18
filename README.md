# Sri Vijaya Lakshmi Silver Palace — Vercel Deployment

## 📁 Project Structure

```
silver-shop/
├── index.html        ← Main website (pure static, no Flask needed)
├── vercel.json       ← Vercel config
├── images/           ← Put your images here
│   ├── logo.jpg
│   ├── banner.jpg
│   ├── item1.jpg
│   ├── item2.jpg
│   └── item3.jpg
└── README.md
```

## 🚀 How to Deploy on Vercel (Free, Fast — No Spin-Down!)

### Step 1 — Add your images
Create an `images/` folder and add:
- `logo.jpg` — your shop logo
- `banner.jpg` — your banner image
- `item1.jpg` — Silver Glasses photo
- `item2.jpg` — Toe Rings photo
- `item3.jpg` — Silver Jewellery photo

### Step 2 — Upload to GitHub
1. Go to https://github.com → New repository → name it `silver-shop`
2. Upload all files (index.html, vercel.json, images/ folder)
3. Click "Commit changes"

### Step 3 — Deploy on Vercel
1. Go to https://vercel.com → Sign up free (use GitHub login)
2. Click "Add New Project"
3. Import your `silver-shop` GitHub repo
4. Click "Deploy" — done! ✅

Your site will be live at: `https://silver-shop.vercel.app` (or your custom domain)

## ⚡ Why Vercel is much faster than Render
- Render free tier "sleeps" after 15 mins → slow cold start (10-30 sec)
- Vercel static sites load in < 1 second, globally, every time
- No Flask server = nothing to spin up

## 🔧 No more Flask needed!
This site is pure HTML/CSS/JS — no Python, no Flask, no gunicorn.
All the speed, none of the complexity.
