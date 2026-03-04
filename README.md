<p align="center">
  <img src="logo.png" alt="Kanoz Bio Energy" width="200">
</p>

<h1 align="center">Kanoz Bio Energy</h1>

<p align="center">
  <strong>Powering Industry with Clean Biomass Energy</strong>
</p>

<p align="center">
  <a href="https://kanoz.in">🌐 Website</a> ·
  <a href="https://wa.me/919839788886">💬 WhatsApp</a>
</p>

---

## About

Kanoz Bio Energy is a leading manufacturer of **premium biomass pellets** for sustainable energy across India. We convert agricultural waste into clean, high-performance fuel — helping industries reduce carbon footprints while cutting energy costs.

## Product Specifications

| Parameter       | Value            |
|-----------------|------------------|
| GCV             | 3400+ Kcal/kg    |
| Moisture        | < 8%             |
| Ash Content     | < 5%             |
| Pellet Size     | 8mm              |
| Emissions       | Low              |
| Availability    | Bulk supply, pan-India |

## Website

This repository contains the source code for [kanoz.in](https://kanoz.in) — a single-page responsive marketing website.

### Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, flexbox/grid, responsive design
- **Vanilla JavaScript** — form validation, scroll interactions, mobile menu
- **Fonts** — Inter + Playfair Display (Google Fonts)

### Key Features

- Fully responsive (mobile-first design)
- WCAG 2.1 AA accessible (ARIA labels, focus management, screen reader support)
- SEO optimized (Open Graph, Twitter Cards, JSON-LD structured data)
- WhatsApp CTA integration
- Contact form with client-side validation
- Smooth scroll navigation with active section highlighting
- iOS safe-area support for notched devices
- Prefers-reduced-motion support

### Sections

| Section          | Description                                      |
|------------------|--------------------------------------------------|
| Hero             | Main headline with call-to-action buttons        |
| About            | Company mission and background                   |
| Products         | Pellet specifications and features               |
| Process          | Manufacturing journey — field to fuel             |
| Why Us           | Key differentiators (24/7 production, ISO, etc.) |
| Testimonials     | Customer reviews with aggregate rating           |
| Sustainability   | Environmental impact messaging                   |
| Contact          | Inquiry form with WhatsApp integration           |

## Getting Started

No build step required — it's a static site.

```bash
# Clone the repo
git clone https://github.com/raaghavk/kanoz-website.git
cd kanoz-website

# Open in browser
open index.html
# or use a local server
python3 -m http.server 8000
```

## Project Structure

```
kanoz-website/
├── index.html      # Complete website (HTML + CSS + JS)
├── logo.png        # Company logo
└── README.md
```

## Feature Roadmap

Below are suggested enhancements to take the site further:

### High Priority

- [ ] **Dark Mode** — Toggle between light and dark themes; respect `prefers-color-scheme`
- [ ] **Backend Form Handling** — Connect the contact form to an actual endpoint (Formspree, Netlify Forms, or a custom API) so inquiries aren't lost
- [ ] **Image Optimization** — Convert `logo.png` to WebP/AVIF with fallback; add product and factory photographs with lazy loading
- [ ] **Analytics** — Add privacy-friendly analytics (Plausible, Umami, or GA4) to track visitor behavior

### Medium Priority

- [ ] **Blog / Resources Section** — Publish articles on biomass energy, sustainability, and case studies to boost SEO and authority
- [ ] **Multi-language Support (i18n)** — Add Hindi and other regional language options to reach a wider Indian audience
- [ ] **Product Catalog Page** — Dedicated page with detailed specs, certifications, datasheets, and downloadable PDFs
- [ ] **Pricing Calculator** — Interactive tool letting prospects estimate cost based on quantity, delivery location, and frequency
- [ ] **Customer Portal** — Login area for existing customers to view order history, invoices, and reorder

### Nice to Have

- [ ] **PWA Support** — Service worker + manifest for offline access and "Add to Home Screen" functionality
- [ ] **Animated Infographics** — Interactive data visualizations for the sustainability/process sections
- [ ] **Live Chat Widget** — Tawk.to or Crisp for real-time visitor support beyond WhatsApp
- [ ] **Testimonials Carousel** — Auto-rotating testimonials with pagination for when more reviews are added
- [ ] **CI/CD Pipeline** — GitHub Actions to auto-deploy to Netlify/Vercel/GitHub Pages on push
- [ ] **Cookie Consent Banner** — GDPR/IT Act compliance for analytics and any future tracking

## License

All rights reserved. &copy; Kanoz Bio Energy.

---

<p align="center">
  Made with 🌿 for a cleaner planet
</p>
