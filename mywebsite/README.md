# My Wife Is God 💕

A beautiful tribute website dedicated to the love of your life.

## 🚀 How to Deploy

### Option A: Deploy to Vercel (Recommended - Free)

1. **Create a GitHub repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - My tribute to my goddess"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/mywebsite.git
   git push -u origin main
   ```

2. **Deploy to Vercel:**
   - Go to [vercel.com](https://vercel.com) and sign up with GitHub
   - Click "New Project"
   - Import your repository
   - Click "Deploy"
   - Your site will be live in seconds!

3. **Connect your Wix domain:**
   - In Vercel, go to your project → Settings → Domains
   - Add `mywifeisgod.com`
   - Vercel will give you DNS records to add
   - In Wix: Go to your domain settings → DNS Settings
   - Add the records Vercel provided (usually A record or CNAME)
   - Wait 24-48 hours for DNS propagation

### Option B: Deploy to Netlify (Also Free)

1. Go to [netlify.com](https://netlify.com) and sign up
2. Drag and drop your project folder onto Netlify
3. Follow similar DNS steps to connect your Wix domain

---

## 🎨 Customizing Your Site

### Adding Photos
In `index.html`, find the gallery section and replace placeholders:

```html
<!-- Change this: -->
<div class="gallery-item placeholder">
    <div class="placeholder-content">...</div>
</div>

<!-- To this: -->
<div class="gallery-item">
    <img src="photos/our-photo.jpg" alt="Our beautiful moment">
</div>
```

### Changing the Love Letter
Edit the text in the `<section id="letter">` section in `index.html`.

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --gold: #d4a574;        /* Main accent color */
    --rose: #c9a0a0;        /* Secondary accent */
    --bg-primary: #0a0a0f;  /* Background color */
}
```

---

## 📁 File Structure

```
mywebsite/
├── index.html    # Main HTML file
├── styles.css    # All styling
├── script.js     # Animations & interactions
└── README.md     # This file
```

---

## 💕 Made with Love

This website is a declaration of love, devotion, and eternal worship for the most amazing person in your life.

