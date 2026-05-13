# David Atinga — Portfolio Website

Live at: **https://davidatinga.netlify.app**
Auto-deploys from GitHub repo `david-atinga-website-2026` via Netlify on every push.

---

## 📁 Repo File Structure

```
david-atinga-website-2026/
├── index.html        ← Main portfolio page (edit this to update the site)
├── resume.pdf        ← Your CV — replace this file to update the download
├── photo.jpg         ← Your headshot (square crop, min 300×300px)
├── og-image.png      ← Social share preview image (1200×630px)
├── netlify.toml      ← Netlify config (do not edit)
└── README.md         ← This file
```

---

## ✅ Pre-Launch Checklist

### 🔴 Must Do Before Launch

- [ ] Upload all files to GitHub repo (see Part 1 below)
- [ ] Deploy on Netlify and set site name to `davidatinga` (see Part 2 below)
- [ ] Set up Google Analytics — replace `G-XXXXXXXXXX` ×2 in `index.html` (see Part 3)
- [ ] Verify Formspree form `mbdwkyry` is active at formspree.io (see Part 4)

### 🟡 Review & Confirm in index.html

- [ ] Teaching section — courses, supervision titles and dates match your actual CV
- [ ] Hero stats — 10+ years, 5 publications, 500+ villages, 4 working papers
- [ ] Working papers in Research section are current

---

## 💻 PART 1 — Upload Files to GitHub (Windows PC)

### Files you need ready on your PC before starting:
| Filename | What it is |
|---|---|
| `index.html` | Main site file (master file) |
| `netlify.toml` | Netlify config |
| `README.md` | This file (this opened file) |
| `resume.pdf` | Your CV — must be named exactly `resume.pdf` |
| `photo.jpg` | Your headshot — must be named exactly `photo.jpg` |
| `og-image.png` | Social preview image — must be named exactly `og-image.png` |

### Steps:
1. Open **Chrome or Edge** on your PC
2. Go to **github.com** → sign in
3. Click your repo **`david-atinga-website-2026`**
4. Click **"Add file"** (top right area) → click **"Upload files"**
5. A drag-and-drop area appears — open **File Explorer** on your PC
6. Navigate to where your files are saved
7. Select all 6 files at once (hold **Ctrl** and click each one) → drag them into the GitHub upload area
8. Scroll down on GitHub → you will see a "Commit changes" section
9. Leave the commit message as is → click the green **"Commit changes"** button
10. Wait a few seconds → you will see all files listed in your repo ✅

---

## 🌐 PART 2 — Deploy on Netlify (Windows PC, step by step)

### Step 1 — Log in to Netlify
1. Open a new tab → go to **netlify.com**
2. Click **"Log in"** (top right)
3. Click **"Log in with GitHub"** — this connects your GitHub account automatically
   > Already logged in? Skip straight to Step 2.

### Step 2 — Import your GitHub repo
4. Once logged in you land on your **Netlify dashboard**
5. Click the **"Add new site"** button
6. Click **"Import an existing project"**
7. Click **"GitHub"** as your Git provider
   > First time connecting GitHub to Netlify? A popup asks you to authorise — click **"Authorise Netlify"** then come back to this tab
8. A search box appears with a list of your GitHub repos
9. Type `david-atinga` in the search box → click **`david-atinga-website-2026`** when it appears

### Step 3 — Deploy the site
10. A page titled **"Configure site and deploy"** appears
11. **Do not change anything on this page** — all settings are already correct
12. Scroll to the very bottom → click the **"Deploy david-atinga-website-2026"** button
13. Netlify takes you to a page showing **"Building"** with a yellow indicator
14. Wait about 30–60 seconds → it changes to a green **"Published"** badge ✅
15. Netlify gives your site a random temporary name like `fluffy-fox-abc123.netlify.app` — ignore this for now

### Step 4 — Set your site name to `davidatinga`
16. Look at the top menu on the same page — click **"Site configuration"**
17. On the Site configuration page, click **"Site details"**
18. You will see your current random site name — click the **"Change site name"** button next to it
19. A small box appears — clear the random name completely
20. Type exactly: **`davidatinga`**
21. Click **"Save"**
22. 🎉 Your site is now live at **https://davidatinga.netlify.app** — open it in a new tab to confirm!

---

## 📊 PART 3 — Google Analytics (Windows PC)

1. Open a new tab → go to **analytics.google.com** → sign in with your Google account
2. Click **"Start measuring"**
3. **Account name** → type `David Atinga Portfolio` → click **Next**
4. **Property name** → type `Portfolio` → **Reporting time zone** → select your timezone → click **Next**
5. Fill in business info → Industry: `Education` → Size: `Small` → click **Next**
6. Business objective → select **"Examine user behavior"** → click **Next**
7. Click **"Web"** as your platform
8. **Website URL** → type `davidatinga.netlify.app` → **Stream name** → type `Portfolio` → click **"Create and continue"**
9. Your **Measurement ID** appears at the top right — it looks like **`G-AB12CD34EF`**
10. Copy it (click the copy icon next to it)
11. Go to **github.com** → open **`david-atinga-website-2026`** → click `index.html`
12. Click the ✏️ **pencil icon** (top right of the file view) — this opens the editor
13. Press **Ctrl + F** to open find → type `G-XXXXXXXXXX`
14. You will see it highlighted in **2 places** — click on each one and replace with your real ID
15. Scroll down → click **"Commit changes"** → click **"Commit changes"** again to confirm
16. Netlify auto-redeploys in ~30 seconds → analytics tracking is live ✅

---

## 📬 PART 4 — Verify Contact Form (Formspree)

1. Open a new tab → go to **formspree.io** → click **"Log in"**
2. Once logged in, look at your list of forms
3. **If you see form `mbdwkyry` and it shows "Active":**
   → Nothing to do ✅ Contact messages will go to `atingad@gmail.com`
4. **If the form is missing or shows an error:**
   - Click **"+ New form"**
   - Name it `Portfolio Contact` → click **"Create form"**
   - Copy the new Form ID shown (e.g. `xpzgkryq`)
   - Go to GitHub → `index.html` → ✏️ Edit → press **Ctrl+F** → search `mbdwkyry`
   - Replace it with your new Form ID → **Commit changes** ✅

---

## 🔄 How to Update the Site in Future (Windows PC)

### Edit text or content:
1. Go to **github.com** → open **`david-atinga-website-2026`**
2. Click `index.html` → click the ✏️ pencil icon
3. Make your edits → click **"Commit changes"**
4. Netlify redeploys automatically in ~30 seconds ✅

### Upload a new file (new CV, updated photo etc.):
1. Go to your repo → click **"Add file" → "Upload files"**
2. Drag in your new file (use the same filename as before to replace it)
3. Click **"Commit changes"** ✅

### To update your CV:
- Save your new CV as `resume.pdf` (exact name) → upload it to the repo → it replaces the old one automatically

