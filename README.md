# Best Spices & Agro Impex Pvt Ltd — premium storefront demo

A responsive, static HTML/CSS/JavaScript B2B spice trading demo for GitHub Pages.

## Features
- Spice categories, live search, quantity selectors and illustrative INR prices
- Add to cart, increment/decrement, remove, clear cart and browser-local cart persistence
- Responsive cart drawer and checkout modal with functioning payment method radio buttons
- **Simulated checkout only**: no real payments, orders, customer data transmission or inventory reservations
- Bulk enquiry and contact forms using `mailto:` once the actual email is configured
- About Us with requested November 2026 founding date and spice heritage notes
- Responsive mobile navigation, hover effects, subtle animations, keyboard Escape handling

## Preview
Open `index.html` locally or use a local web server. Images and fonts require internet. Product photographs are illustrative stock images, not verified photographs of the listed spices or company stock. Replace them with properly licensed, product-accurate photos before going live.

## Deploy to GitHub Pages
1. Create a **public** repository on GitHub, e.g. `best-spices-demo`.
2. Upload the contents of this folder to the **repository root**: `index.html`, `styles.css`, `script.js`, and `assets/`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. Once deployment finishes, the site should be accessible at `https://YOUR-USERNAME.github.io/best-spices-demo/`.
6. Test on mobile and desktop, including cart and checkout.

## Using the Wix-purchased domain
The domain registrar and hosting are separate. Keep the domain registered at Wix and update its DNS records only after GitHub Pages is working. In GitHub Pages settings, set your custom domain, then follow GitHub's current DNS instructions for your apex domain or `www` subdomain. Changes can take time to propagate. **Do not change DNS blindly**, especially if business email uses the domain; preserve MX, SPF, DKIM and other mail records. For production commerce, use a supported e-commerce platform and payment integration instead of static GitHub Pages.

## Before real business launch
- Verify the **exact registered company name**, founding date, business address and all claims.
- Replace placeholder `hello@example.com` in `script.js` and `index.html` with a verified company email.
- Replace demo prices, photos, origins and descriptions with verified catalogue data.
- Add privacy policy, terms, returns/shipping policy, tax, duties, company registrations and required disclosures.
- Implement an actual secure checkout with a compliant payment gateway and backend; **do not collect card details directly on this static site**.
- This demo has no server-side order management, email delivery, fraud controls or inventory system.

## Photography update
All product images are bundled locally under assets/ as illustrative AI-generated spice photographs. No remote image URLs are required. Replace with genuine product photographs before selling or making claims about actual inventory.
