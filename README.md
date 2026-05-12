# 🍃 Fresh Café — GitHub Pages Website

Your beautiful **Pimlico Fresh** café website is now live on GitHub Pages!

## 🌐 Live Website
**Visit:** `https://adityathakekar.github.io/Fresh`

---

## 📋 Quick Start

### File Structure
```
Fresh/
├── index.html          # Main website (all-in-one)
├── README.md           # This file
└── .gitignore          # Git configuration
```

### What's Included
✅ **Fully Responsive Design** - Works on desktop, tablet, mobile  
✅ **Interactive Features**:
  - Smooth scroll navigation
  - Menu filtering tabs
  - Image lightbox gallery
  - Click & Collect order modal
✅ **Modern Styling**:
  - Vibrant sage & honey accents
  - Smooth animations & transitions
  - Professional typography (Fraunces + Outfit)
  - Optimized performance

---

## 🎨 Customization Guide

### 1. **Update Business Info**
Open `index.html` and find these sections:

```html
<!-- Change phone number -->
<a href="tel:+442079320030">020 7932 0030</a>

<!-- Change address -->
<div class="val">86 Wilton Rd, SW1V</div>

<!-- Change hours -->
<div class="val">07:30 – 19:30</div>
```

### 2. **Replace Images**
- Replace Unsplash URLs with your own café photos
- Keep aspect ratios consistent
- Recommended formats: JPG (photos), PNG (graphics)

Example image URLs to update:
- Hero collage (3 images)
- Menu cards (5 images)
- Gallery section (5 images)

### 3. **Update Colors**
Edit CSS variables at the top of `<style>`:

```css
:root {
  --cream: #FAF8F3;      /* Light background */
  --sage: #4ADE80;       /* Green accent */
  --honey: #FF6B00;      /* Orange accent */
  --espresso: #1C1309;   /* Dark brown text */
}
```

### 4. **Customize Menu Items**
Find the "Popular" section in the order modal:

```html
<div class="cart-item">
  <div>
    <div style="font-weight: 700;">Item Name</div>
    <div style="font-size: 12px; color: var(--sageD);">Description</div>
  </div>
  <button class="btn btn-ghost" style="padding: 8px 16px; font-size: 11px;">+ £Price</button>
</div>
```

### 5. **Connect to Order System**
Replace this in the modal:
```html
onclick="alert('This would link directly to your Square/StoreKit Point of Sale system!')"
```

With your actual checkout URL (Square, Stripe, or custom system).

---

## 🚀 Publishing Changes

### Method 1: GitHub Web Editor (Easy)
1. Go to `https://github.com/adityathakekar/Fresh`
2. Click on `index.html`
3. Click the ✏️ (edit) icon
4. Make changes
5. Click "Commit changes"
6. Your site updates in 30-60 seconds!

### Method 2: Git Command Line
```bash
# Clone the repo
git clone https://github.com/adityathakekar/Fresh.git
cd Fresh

# Make edits to index.html

# Commit and push
git add index.html
git commit -m "Update menu and photos"
git push
```

---

## 📱 Responsive Breakpoints
- **Desktop:** 1240px max content width
- **Tablet:** 980px (adjusted grid layout)
- **Mobile:** 560px (single column)

---

## 🎯 Next Steps for Redesign

### Easy Wins
- [ ] Update your café photos
- [ ] Change color scheme
- [ ] Update business hours/location
- [ ] Add testimonials section
- [ ] Connect real order system

### More Advanced
- [ ] Add embedded Google Map (visit section)
- [ ] Add Instagram feed integration
- [ ] Create separate CSS/JS files (for scalability)
- [ ] Add reservation system
- [ ] SEO optimization

---

## ⚙️ GitHub Pages Settings

Your site is **automatically deployed** when you push to `main` branch.

To verify settings:
1. Go to repo → **Settings** → **Pages**
2. Ensure source is set to: **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**

---

## 💡 Tips

- **Performance:** Keep image file sizes under 500KB
- **SEO:** Update the `<meta>` tags with real descriptions
- **Accessibility:** All images have `alt` text
- **Mobile:** Test on your phone before committing

---

## 📞 Support & Resources

- **GitHub Pages Docs:** https://pages.github.com
- **HTML/CSS Reference:** https://developer.mozilla.org
- **Color Palettes:** https://coolors.co
- **Free Images:** https://unsplash.com, https://pexels.com

---

## 📄 License
MIT License - Feel free to customize!

---

**Built with ❤️ for Pimlico Fresh**  
Live at: `https://adityathakekar.github.io/Fresh`
