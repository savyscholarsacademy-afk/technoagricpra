# TECHNOAGRICPRA (PVT) LTD — Official Corporate Website

**Operating as:** TECHNOAGRI PRECISION  
**Headquarters:** Marondera, Mashonaland East Province, Zimbabwe  
**Entity Registration No.:** 119164A0562026  

---

## Overview

This repository contains the official single-page corporate website for **TECHNOAGRICPRA (PVT) LTD**, a Zimbabwean agricultural extension, livestock management, rural supply chain, and AgriTech company. The website showcases the company's field services, founding leadership team, corporate credentials, and flagship digital platform (**AGRIPOT**).

---

## Design & Brand System

The website is built with semantic HTML5, Tailwind CSS (via CDN), Plus Jakarta Sans typography, and Font Awesome 6 icons, preserving the official corporate visual identity:

| Token | Hex Code | Usage |
| :--- | :--- | :--- |
| `forest` | `#0B2A1F` | Primary dark header, hero, contact section, primary headings |
| `deepgreen` | `#0F3D2A` | Secondary cards, borders, interactive hover states |
| `limebrand` | `#7ED321` | High-contrast CTAs, badges, accent icons, text highlights |
| `mintlight` | `#E8F3EC` | Highlight cards, mobile menu buttons, confirmation banners |
| `mintsoft` | `#F4FAF6` | Alternating section backgrounds (`Services`, `Leadership`) |

---

## Repository Structure

```text
technoagricpra-corporate-website/
├── index.html       # Main responsive corporate website (exact maintained design)
├── README.md        # Project documentation, brand palette, and deployment guide
├── LICENSE          # Proprietary / All Rights Reserved corporate license
└── .gitignore       # Standard OS, editor, and temporary build exclusions
```

---

## Key Sections Included

1. **Sticky Corporate Navigation Bar:** Desktop navigation with smooth-scroll anchors and a responsive mobile drawer.
2. **Corporate Hero Section:** Value proposition, Mashonaland East headquarters badge, trust pillars, and field showcase.
3. **About Us:** Company mission, hybrid human + digital operational approach, and the *TECHNOAGRI PRECISION Standard*.
4. **Core Agricultural Services:**
   - Private Agricultural Extension & Field Advisory
   - Livestock Production & Animal Health Management
   - Climate-Smart Crop & Horticulture Consulting
   - Rural Supply Chain & Village Hub Logistics
5. **AGRIPOT Platform Spotlight:** Overview of the mobile agro store, trilingual AI advisory (English, Shona, Ndebele), digital farm records, and account tiers (*Free Basic*, *Premium $5/mo*, and *Partner Portals*).
6. **Leadership Team:** Profiles of the four co-founders across Livestock, Operations/QA, Agronomy, and Technology/IT.
7. **Contact & Service Inquiry Form:** Interactive client-side inquiry form with instant confirmation feedback.

---

## Local Preview & Deployment

### Local Preview
No build step is required. Open `index.html` directly in any modern web browser, or serve locally with Python:

```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

### Git Initialization & GitHub Pages Deployment
If initializing a fresh Git repository from these files:

```bash
git init
git add .
git commit -m "Initial commit: TECHNOAGRICPRA (PVT) LTD official corporate website"
git branch -M main
git remote add origin <your-repository-url>
git push -u origin main
```

To deploy live on **GitHub Pages**, go to **Settings → Pages**, select the `main` branch and `/ (root)` folder, and click **Save**.
