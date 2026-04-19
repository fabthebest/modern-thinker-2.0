# Fabrice Fils-Aimé - Modern Thinker 2.0

## 🔗 Repository

👉 https://github.com/fabthebest/modern-thinker-2.0

---

## 🧠 Overview

Official website of **Fabrice Fils-Aimé** — writer, essayist, and independent researcher exploring literature, philosophy, and artificial intelligence.

This project is a **high-performance, zero-dependency web experience**, designed to combine:

* aesthetic depth
* intellectual identity
* technical efficiency

---

## ⚙️ Tech Stack

* HTML5 (W3C standard)
* CSS3 (Grid, Flexbox, Animations, Custom Properties)
* JavaScript (ES2020)
* No frameworks, no dependencies

---

## 🚀 Features

* Fully responsive design
* SEO optimized (meta tags + structured data JSON-LD)
* Accessibility (WCAG 2.1 AA)
* High performance (Core Web Vitals optimized)
* Custom animations & immersive UI
* Multilingual-ready (FR / EN)

---

## 📁 Project Structure

```bash
modern-thinker-2.0/
│
├── index.html
├── livre.html
├── modern-thinker.html
├── vercel.json
├── LICENSE
├── README.md
│
├── css/
│   └── style.css
│
├── js/
│   └── main.js
│
├── assets/
│   └── images/
```

---

## 🌐 Live Deployment

👉 https://modern-thinker-2-0.vercel.app *(à adapter après déploiement)*

---

## ⚡ Deployment (Vercel)

1. Push your code to GitHub
2. Go to https://vercel.com
3. Click **"Add New Project"**
4. Select repository: `modern-thinker-2.0`
5. Deploy

✔️ No build step required
✔️ Automatic HTTPS
✔️ Global CDN

---

## ⚙️ Vercel Configuration

Create a file at the root:

```json
{
  "cleanUrls": true,
  "trailingSlash": false
}
```

---

## 🌍 External Services

This project uses a **minimal set of external services** for performance and usability:

* **Google Fonts** → typography optimization
* **IPAPI** → optional geolocation (used to redirect users to the correct Amazon region)
* **Amazon links** → book distribution (ISBN: 2386170993)

All of these are **optional** and the website remains fully functional without them.

---

## 🔐 Security

This project follows standard **front-end security best practices**:

* Content Security Policy (CSP)
* Referrer Policy
* Permissions Policy

As a static website, it does not process sensitive user data or include backend services.

Additional headers can be configured via Vercel:

```bash
X-Frame-Options: DENY
X-Content-Type-Options: nosniff
Strict-Transport-Security: max-age=31536000
```

---

## 📬 Newsletter

👉 Substack: https://substack.com/@modernthinker20

Optional integrations:

* ConvertKit
* Mailchimp

---

## 💰 Future Integrations

* Stripe (payments / ebooks)
* Gumroad (digital products)
* Printful (physical products)
* AI assistant (interactive writing / research)

---

## 🧩 Development

Run locally:

```bash
npx serve .
# OR
python3 -m http.server 8000
```

---

## 👤 Author

**Fabrice Fils-Aimé**
Writer · Essayist · Researcher

---

## 📜 License

This project is proprietary and protected under an **All Rights Reserved** license.

Unauthorized copying, modification, distribution, or use of this code, design, or content is strictly prohibited without prior written permission from the author.
