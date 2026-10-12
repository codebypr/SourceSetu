# SourceSetu Pro — Responsive Multi-page Website

## Included pages
- `index.html` — home / landing page
- `products.html` — searchable product catalogue and category filter
- `categories.html` — category overview
- `about.html` — business model
- `how-it-works.html` — sourcing steps
- `quote.html` — enquiry form with WhatsApp handoff
- `contact.html` — contact options
- `privacy.html` — privacy policy draft
- `terms.html` — terms and conditions draft

## Visual and responsive features
- Navy, white and orange corporate style
- Responsive desktop, tablet and mobile layouts
- Mobile navigation and fixed mobile CTA bar
- Product/category photography from Unsplash (internet required for remote images)
- Product search and category filter
- Quote form with required-field validation and prefilled product/category
- WhatsApp CTA on navigation, homepage, quote and footer
- Reduced-motion support and semantic image alt text

## Configure before launch
1. Open `assets/site.js` and set `CONFIG.whatsappNumber` to your business WhatsApp number using country code and digits only (e.g. `91XXXXXXXXXX`).
2. Add verified business email and contact information where appropriate.
3. The enquiry form prepares a WhatsApp message. It does **not** automatically email, save submissions, or provide server-side spam protection. For production, connect a secure backend/form provider and server-side validation. Never expose API keys in frontend code.
4. Privacy and Terms are starter drafts; obtain appropriate review before publication.
5. Images are illustrative. No prices, MOQ, supplier credentials, reviews, GSTIN or certifications are fabricated.
6. No domain, hosting, paid plan or online payment is purchased or integrated.

## Preview / deployment
Open `index.html` locally in a browser (remote photos need internet). Or upload the entire folder to any static web host. Keep the relative folder structure intact.

## Responsive UI update
This version includes additional small-screen breakpoints (including 320–360px phones), touch-friendly controls, responsive one-column product cards on mobile, improved form layout, overflow prevention, safe-area spacing for mobile action bars, subtle entry/image animations, and support for reduced-motion accessibility preferences. Keep the `assets` folder beside all HTML pages when previewing or deploying.
