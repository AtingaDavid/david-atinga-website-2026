# David Atinga — Portfolio Website

Auto-deploys from this GitHub repo via Netlify on every push.
Free hosting + free domain on `.netlify.app` — no cost at all.

---

## 📁 Repo File Structure

```
/
├── index.html        ← Main portfolio page (edit this to update the site)
├── resume.pdf        ← Your CV — replace this file to update the download
├── photo.jpg         ← Your headshot (square crop, min 300×300px)
├── og-image.jpg      ← Social share preview image (1200×630px)
├── netlify.toml      ← Netlify config (do not edit)
└── README.md         ← This file
```

---

## ✅ Pre-Launch Checklist

### 🔴 Must Do

- [ ] **Choose your free domain name** — e.g. `davidatinga.netlify.app` (see guide below)
- [ ] **Update `og:url` in `index.html`** — replace `YOUR-CHOSEN-NAME` with your real subdomain
- [ ] **Upload `photo.jpg`** — your headshot, square crop
- [ ] **Upload `resume.pdf`** — your latest CV
- [ ] **Create & upload `og-image.jpg`** — see guide below
- [ ] **Verify Formspree** — log in at formspree.io, confirm form `mbdwkyry` is active and emailing `atingad@gmail.com`. If not, create a new form and replace `mbdwkyry` in `index.html`
- [ ] **Set up Google Analytics** — replace both `G-XXXXXXXXXX` in `index.html` with your real ID (see guide below)

### 🟡 Review & Confirm

- [ ] Teaching section courses, supervision titles and dates match your actual CV
- [ ] Hero stats correct: 9+ years, 5 publications, 108 villages, 4 working papers
- [ ] Working papers in Research section are current

---

## 🌐 Setting Your Free Netlify Domain (100% free, forever)

Your site will be at `davidatinga.netlify.app` — completely free, no card needed.

**Good name ideas for your profile:**
- `davidatinga.netlify.app`
- `atinga-economist.netlify.app`
- `david-atinga.netlify.app`
- `atingaeconomics.netlify.app`

**How to set it (on your phone):**
1. Go to **app.netlify.com** → tap your site
2. Tap **Site configuration → Site details → Change site name**
3. Type your preferred name (it checks availability instantly)
4. Tap **Save** → your site is immediately live at that address ✅
5. Then edit `index.html` on GitHub and replace `YOUR-CHOSEN-NAME` in the `og:url` line with your real subdomain name

---

## 🖼 How to Create og-image.jpg (on your phone)

This is the preview image when you share your link on WhatsApp, LinkedIn, Twitter etc.

### Option A — Screenshot (easiest, 2 minutes)
1. Download `index.html` and open it in your phone browser
2. Scroll to the top hero section
3. Take a **screenshot**
4. Open it in your phone's photo editor (Photos on iPhone / Gallery on Android)
5. **Crop to wide landscape** — roughly 2:1 ratio (wide, not tall)
6. Save as `og-image.jpg`
7. Upload to your GitHub repo

### Option B — Canva (free, more polished)
1. Go to **canva.com** on your phone — sign up free
2. Tap **"Create a design"** → search **"Open Graph"** or **"Presentation 16:9"**
3. Add your name + title using the site colours:
   - Dark green background: `#2C4A3E`
   - Cream text: `#FDFAF5`
4. Download as **JPG**
5. Upload to GitHub repo as `og-image.jpg`

---

## 📊 Google Analytics Setup (free, ~5 minutes)

1. Go to **analytics.google.com** on your phone
2. Sign in with Google → **"Start measuring"**
3. Account name: `David Atinga Portfolio` → Next
4. Property name: `Portfolio` → Next → choose **Web**
5. Enter your `.netlify.app` domain → **Create stream**
6. Copy your **Measurement ID** — looks like `G-AB12CD34EF`
7. Open your GitHub repo → tap `index.html` → ✏️ Edit
8. Search `G-XXXXXXXXXX` → replace **both** instances with your real ID
9. Commit changes → done ✅

---

## 🔄 How to Update the Site (all on your phone)

**Edit text / content:**
1. Open repo on **github.com** on your phone browser
2. Tap `index.html` → ✏️ pencil (Edit) icon
3. Make your edits → scroll down → **"Commit changes"**
4. Netlify redeploys automatically in ~30 seconds ✅

**Upload new files (photo, CV, og-image):**
1. Open repo → tap **"Add file" → "Upload files"**
2. Choose your file → **"Commit changes"** ✅

**Pro tip:** Install the free **GitHub Mobile app** (iOS / Android) for a much smoother editing experience on your phone than the browser.

---

## 🔗 Useful Links

- Netlify dashboard: https://app.netlify.com
- Formspree dashboard: https://formspree.io
- Google Analytics: https://analytics.google.com
- ORCID profile: https://orcid.org/0000-0002-3281-3175
- GitHub Mobile app: https://github.com/mobile
