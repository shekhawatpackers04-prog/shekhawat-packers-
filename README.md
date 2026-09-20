# 📦 Shekhawat Packers — Official B2B Packaging Website

[![Live Demo](https://img.shields.io/badge/Live%20Demo-shekhawat--packers.netlify.app-orange?style=for-the-badge&logo=netlify)](https://shekhawat-packers.netlify.app)
[![Tech Stack](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20JavaScript-blue?style=for-the-badge&logo=javascript)](https://shekhawat-packers.netlify.app)
[![SEO Ready](https://img.shields.io/badge/SEO-Schema.org%20%2B%20Sitemap-green?style=for-the-badge&logo=google)](https://shekhawat-packers.netlify.app)
[![Location](https://img.shields.io/badge/Location-Delhi%20NCR%2C%20India-red?style=for-the-badge&logo=googlemaps)](https://shekhawat-packers.netlify.app/contact.html)

Official website and digital catalog for **Shekhawat Packers**, a trusted wholesale packaging manufacturer and distributor founded by **Himmat Singh** based in Gandhi Nagar, Delhi NCR.

---

## 🚀 Live Website
🌐 **Production URL:** [https://shekhawat-packers.netlify.app](https://shekhawat-packers.netlify.app)

---

## ✨ Features

- **🛍️ Product Showcase & Catalog ([`products.html`](products.html)):**
  - High-resolution real product photography with edge-to-edge fill (`object-fit: cover`).
  - Active products: Corrugated Boxes, BOPP Tapes, Plastic Bags, Jute Gunny Bags, Plastic Rope (Sutli), and Permanent Markers.
  - Real-time instant search bar and category filtering tabs.
- **⚡ One-Click B2B Ordering:**
  - Direct WhatsApp RFQ (Request for Quote) buttons pre-filled with product specifications.
  - Direct phone call triggers for immediate dispatch queries.
- **📖 Packaging Insights Blog ([`blog.html`](blog.html)):**
  - Industry buyer guides (Corrugated Box Ply Guide, BOPP Tape Micron Guide, Eco-Friendly packaging, Cost-saving strategies).
- **📝 Publishing Studio ([`admin.html`](admin.html)):**
  - Internal blog publishing tool with rich formatting and instant preview (protected with `noindex, nofollow`).
- **🔍 Comprehensive SEO & Social Sharing:**
  - **Schema.org JSON-LD:** `LocalBusiness`, `WholesaleStore`, `Product`, `ItemList`, and `BreadcrumbList`.
  - **Open Graph & Twitter Cards:** Rich preview cards when sharing on WhatsApp, Facebook, LinkedIn, and Twitter.
  - **Local SEO Geo Tags:** Coordinates and region metadata for Gandhi Nagar, Delhi.
  - **Search Crawler Control:** Standard [`robots.txt`](robots.txt) and XML [`sitemap.xml`](sitemap.xml).
- **📱 PWA & Mobile Installability:**
  - Configured [`site.webmanifest`](site.webmanifest) with brand theme colors (`#1E3369` / `#f5c97a`).
- **🛡️ Custom 404 Page ([`404.html`](404.html)):**
  - Brand-matched error page guiding visitors back to the product catalog and homepage.

---

## 📂 Project Structure

```text
shekhawat-packers/
├── index.html            # Homepage (Hero, core values, quick contact)
├── products.html         # Product catalogue with live filter & search
├── about.html            # Company heritage & founder profile (Himmat Singh)
├── contact.html          # Location map, contact details & WhatsApp CTA
├── blog.html             # Packaging guides & buyer insights
├── admin.html            # Internal blog publishing studio (noindex)
├── 404.html              # Custom brand 404 error page
├── robots.txt            # Search engine crawler instructions
├── sitemap.xml           # XML sitemap with image metadata
├── site.webmanifest      # Progressive Web App manifest
├── css/
│   └── style.css         # Responsive styling, color tokens, animations
├── js/
│   ├── common.js         # Navigation, utilities, global handlers
│   └── app.js            # Product filtering, dynamic rendering
├── images/               # Product photos and catalog imagery
└── blog/                 # Individual standalone blog article pages
```

---

## 🛠️ Tech Stack

- **HTML5:** Semantic markup, microdata, Schema.org JSON-LD.
- **CSS3:** Flexbox, CSS Grid, Custom Properties (variables), Backdrop filters.
- **JavaScript (Vanilla):** Zero-dependency fast client-side scripts.
- **Hosting:** Netlify (Continuous Deployment via Git / Netlify Drop).

---

## 💻 Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/shekhawat-packers.git
   cd shekhawat-packers
   ```
2. Run with any local server:
   - **VS Code Live Server:** Right-click `index.html` → *Open with Live Server*
   - **Python:** `python -m http.server 5500`
   - **Node.js:** `npx serve .`
3. Open `http://localhost:5500` in your browser.

---

## 🚢 Deployment

### Netlify Drag & Drop
1. Visit [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the project folder.

### Netlify CLI
```bash
npx netlify-cli deploy --prod --dir=.
```

---

## 📞 Business Contact

- **Company:** Shekhawat Packers
- **Founder:** Himmat Singh
- **Location:** Gandhi Nagar, Delhi NCR, India
- **Phone / WhatsApp:** [+91 95823 92131](https://wa.me/919582392131)
- **Website:** [https://shekhawat-packers.netlify.app](https://shekhawat-packers.netlify.app)
