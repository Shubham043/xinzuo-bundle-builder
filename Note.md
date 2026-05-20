## What I picked
Fixed the dead Bundle Builder page (`/pages/bundle-builder`).

## Why it's the highest-impact thing here
A dead conversion page kills an entire revenue channel. Every other issue affects existing flow — a dead Bundle Builder means zero bundle sales. It's the biggest gap between the clone and live xinzuo.com.au.

## What I did
- Created `templates/page.bundle-builder.liquid` with a full working Bundle Builder
- Tabbed discount tier display (Buy 2 save 5%, Buy 3 save 10%, Buy 4+ save 15%)
- Sticky cart sidebar showing selected items, subtotal, discount, and total
- Add/remove items with live price calculation
- Created the page in Shopify admin with the bundle-builder template
- Pushed theme via Shopify CLI

## What I'd do next
- Add product images and real variant data from collections
- Wire up "Add All to Cart" to Shopify's `/cart/add.js` API
- Add series filter tabs (MO, LAN, Supreme etc) like the live xinzuo.com.au
- Mobile layout polish
- Animate the discount tier highlight when threshold is reached