# RentalPanda local storefront

A responsive, static MVP for the RentalPanda Mallorca holiday rental business. It uses the supplied RentalPanda logo and product photos in `RentalPanda/`.

## Preview locally

From this folder, run:

```sh
python3 -m http.server 4173
```

Then open [http://localhost:4173](http://localhost:4173). The demo basket is saved in this browser. Clear the browser's local storage to reset it.

## Demo pages

- `index.html` — homepage and featured products.
- `shop.html` — searchable, filterable catalogue.
- `product.html?id=stroller` — product details, rental dates and extras. Product cards open this page.
- `cart.html` — basket with quantities and bundle savings.
- `checkout.html` — delivery, address and payment choice.
- `thank-you.html` — booking confirmation preview.

## MVP flows

- English / Spanish language toggle and EUR / USD display toggle.
- Search, category filters, product details, optional extras and persistent basket.
- Rental duration pricing, bundle discounts and delivery estimates.
- Stay delivery, airport handoff and warehouse collection options.
- Demo full payment or 25% advance payment selection and confirmation screen.
- Demo Google, Facebook and email sign-in buttons.

Basket, language, currency and selected rental dates persist while navigating between pages in the same browser.

All products, rental rates, delivery amounts, discounts and booking confirmations are sample data. Payments and social sign-in are visual demo flows; no payment is processed and no reservation is sent to a back end.

## Vercel

This is a static site and can be deployed from the repository root as a Vercel project. Add a real booking service, verified operational prices, delivery zone rules and payment provider before accepting live reservations.
