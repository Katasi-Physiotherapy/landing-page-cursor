# Katasi Physiotherapy Website

A world-class digital presence for Katasi Physiotherapy in Westlands, Nairobi. Built with Astro, designed to convert visitors into appointments via call and WhatsApp.

## Features

- **Hero landing** with clear CTAs (Call, WhatsApp)
- **Floating WhatsApp button** on every page
- **Service listing** with back pain, sports injuries, posture, rehab, advanced therapy
- **Blog** with Decap CMS for easy content publishing
- **Social media** integration (Facebook, Instagram)
- **Google Maps** embed for location
- **SEO optimized** with sitemap, meta tags, target keywords

## Tech Stack

- **Frontend:** Astro
- **CMS:** Decap CMS (Netlify)
- **Hosting:** Netlify

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
src/
├── components/     # Reusable UI components
├── content/        # Blog posts (Markdown)
│   └── blog/
├── layouts/        # Page layouts
├── pages/          # Routes
│   ├── index.astro      # Home
│   ├── services/        # Services page
│   ├── about/           # About page
│   ├── blog/            # Blog index + [slug]
│   └── contact/         # Contact page
└── styles/         # Global CSS
```

## Deployment (Netlify)

1. Push to GitHub
2. Connect repo to Netlify
3. Build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
4. Add custom domain (e.g. katasi.co.ke)
5. Enable **Identity** and **Git Gateway** in Netlify for Decap CMS
6. CMS available at: `yoursite.com/admin`

## Content Management

- **Blog:** Visit `/admin` to add/edit posts
- **Categories:** Back pain, Sports injuries, Posture, Recovery tips, Lifestyle
- **Fields:** title, description, date, category, cover image, body

## Contact Info

- **Phone:** 0705 717 353
- **Address:** Mogotio Road, Westlands, Nairobi
- **WhatsApp:** [wa.me/254705717353](https://wa.me/254705717353)

## Design System

- **Primary:** #1E6F9F (Medical blue)
- **Secondary:** #3CBFA6 (Teal)
- **Fonts:** Poppins/Inter (headings), Open Sans (body)

---

Built for Katasi Physiotherapy. Move without pain. Recover stronger.
