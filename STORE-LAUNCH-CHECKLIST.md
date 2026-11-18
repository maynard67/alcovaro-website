# Alcovaro — dropshipping-first launch plan

**Status:** Design and planning only. Do not take payments or connect the live Netlify domain until launch checks pass.

## Protect the existing site
- [ ] Download/export the **complete** existing Netlify Drop deployment (HTML, CSS, JS, images, policies, guides).
- [ ] Verify backup contents and store a copy outside GitHub.
- [ ] Recreate the full site's structure in GitHub on a **separate branch**, preserving page paths and assets.
- [ ] Review changes in an isolated preview before any production deploy.
- [ ] Keep GitHub `main` and the live Netlify project disconnected until a full-site migration is verified.

## Design
- [x] Add premium glass visual concept (`premium-preview.html`).
- [ ] Apply shared design system to the **recovered full site**, including guides and policy pages.
- [ ] Test mobile navigation, keyboard focus, contrast, reduced motion, image loading and performance.
- [ ] Replace generic concept visuals with licensed photography or supplier-authorised product images.

## Supplier and products
- [ ] Verify GoDropship account, UK dispatch locations, fulfilment flow, live stock and any order minimums.
- [ ] Select 3–5 relevant items; do not import unrelated catalogue products.
- [ ] Record supplier links, dimensions, materials, dispatch/delivery windows, product safety information and image-use permission.
- [ ] Calculate **contribution margin per order**: retail price minus product cost, shipping, payment fees, VAT where applicable, returns/defect allowance and marketing costs.
- [ ] Confirm UK customer rights and supplier return arrangements independently.
- [ ] Validate stock updates and test an order with the supplier.

## Ecommerce
- [ ] Choose a supported checkout platform/payment processor and confirm fees and integration.
- [ ] Implement secure cart, checkout, order confirmation, inventory checks and refund handling.
- [ ] Set up customer support and order-status communication.
- [ ] Prepare and review terms of sale, privacy/cookies, shipping and returns, contact/business details and required disclosures.
- [ ] Confirm consumer/product safety and tax obligations for the actual business setup.
- [ ] Run end-to-end test purchases, cancellations and refunds before going live.

## Deployment gate
Do not connect this partial GitHub repository to the existing Netlify production project. No live payment collection or unverified product claims.
