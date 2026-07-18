# M.R. Saree Emporium — Website Redesign Concept

Redesign demo for **M.R. Saree Emporium** (currently live at mrse.in) — built to show what a modern, premium wholesale textile site can look and feel like, using the business's **real products, photos, pricing and details**.

## What this demo includes (all working, single file — `index.html`)

- **Real catalogue data from mrse.in**: actual products (Bandhani Chiffon sets, Kimora Sindhuri Maharani Dola Silk, STYLE VOL 10 Kurti), real photos, real set-based wholesale pricing (e.g. "6 Pcs — ₹2,130 · ₹355/pc")
- **Working cart drawer**: add sets, change quantities, live totals, and a one-tap **"Place Order on WhatsApp"** that composes the full order message to +91 99796 30465
- **Live search** with instant thumbnail results (by product, brand, fabric, category)
- **Quick View modal** with multi-image gallery from the real product photo sets
- **Category filtering + sorting** without page reloads
- Wishlist toggles, toast notifications, animated stats, brand marquee (Ek Stree, Laxmipati, Kayaan, Palav, Subhash, RajYog, Kimora, TFH…)
- **5-branch section**: Surat HQ (full Kohinoor Textile Market address) + Varanasi, Kolkata, Ranchi, Raipur
- Real trust claims from the business: 60+ years, 50,000+ retailers, 2–3 day dispatch, worldwide export, COD/secure payment
- Premium design system: Cormorant Garamond + Archivo, wine/ivory/gold palette, editorial layouts, scroll reveals, reduced-motion support
- Mobile: slide-out menu, sticky bottom Call/WhatsApp/Search/Cart bar
- Correct social links (their current site's Facebook link is broken — fixed here)

## Notes for the client

- Product data is a **sample slice** of the real catalogue to demonstrate functionality; the full build connects to live inventory
- Testimonials are placeholders to be replaced with real reviews
- Checkout button is a demo — production version integrates Razorpay + GST invoicing

## Full build roadmap

Next.js + TypeScript + Tailwind · PostgreSQL + Prisma · buyer accounts & wholesale approval · full catalogue with filters (brand / price / set size, matching current site's filter model) · admin dashboard & CMS · English/Telugu language support · SEO (schema, sitemaps) · Lighthouse 90+ targets.

## Viewing live

Enable GitHub Pages (Settings → Pages → `main` branch, root) to get a shareable URL.
