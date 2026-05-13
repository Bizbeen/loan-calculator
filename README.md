# 💰 Loan Calculator — Hosted on GitHub Pages

A free, fast, and beautiful EMI loan calculator with Google AdSense support.

**Live Demo:** `https://YOUR-USERNAME.github.io/loan-calculator`

---

## ⚡ Features
- Monthly EMI calculation
- Total interest & total payment
- Visual donut chart breakdown
- Full amortization schedule (month-by-month)
- 4 Google AdSense ad slots built in
- Fully responsive (mobile + desktop)
- Zero dependencies — pure HTML/CSS/JS

---

## 🚀 Setup in 5 Minutes

### 1. Fork or Clone this repo
```bash
git clone https://github.com/YOUR-USERNAME/loan-calculator.git
cd loan-calculator
```

### 2. Enable GitHub Pages with Actions
1. Go to your repo on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select **GitHub Actions**
4. That's it — the workflow runs automatically on every push

### 3. Push any change to trigger deployment
```bash
git add .
git commit -m "Initial deploy"
git push origin main
```

Your site will be live at:
```
https://YOUR-USERNAME.github.io/loan-calculator
```

---

## 💡 Adding Google AdSense (after approval)

1. Sign up at https://adsense.google.com
2. Open `index.html` and find the comment:
   ```html
   <!-- GOOGLE ADSENSE — Replace ca-pub-XXXXXXXXXXXXXXXX -->
   ```
3. Replace `ca-pub-XXXXXXXXXXXXXXXX` with your Publisher ID
4. Uncomment the `<script>` tag in the `<head>`
5. Replace each ad placeholder `<div>` with your `<ins>` ad unit code
6. Push to main — GitHub Actions auto-deploys in ~30 seconds

---

## 📁 Project Structure
```
loan-calculator/
├── index.html                  # Main calculator app
├── README.md                   # This file
└── .github/
    └── workflows/
        └── deploy.yml          # GitHub Actions auto-deploy
```

---

## 🌐 Moving to a Custom Domain (Later)

1. Buy a domain (e.g., `loanemicalculator.in`)
2. In GitHub → Settings → Pages → **Custom domain**, enter your domain
3. At your domain registrar, add a CNAME record:
   - Type: `CNAME`
   - Name: `www`
   - Value: `YOUR-USERNAME.github.io`
4. Check **Enforce HTTPS** in GitHub Pages settings

---

## 📜 License
MIT — free to use and modify.
