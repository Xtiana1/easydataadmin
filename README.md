# EasyData Admin Console Prototype

A responsive, front-end-only admin console prototype.

## Run it

1. Install Node.js if it is not already installed.
2. From this folder, run `npm run dev`.
3. Open `http://localhost:5173` in your browser.

You can also open `index.html` directly in a modern browser.

## Included screens

- Dashboard metrics, order-trend graph, delivery timer, day/month/year date filters, and product filter. The Recent Orders card has been removed.
- Orders with date/time, product, delivery and payment filters, search, status actions, and CSV/Excel export.
- Products & Pricing for MTN DATA, MTN INSTANT DATA, MTN AIRTIME, and AirtelTigo.
- Product Routing with product-specific fulfillment providers: E-Top Up is available for MTN DATA only; MTN INSTANT DATA, MTN AIRTIME, and AirtelTigo offer Resello or Off.
- Payment Collections, SMS & Announcements, USSD Metrics, Sales Metrics, Accounts, and sign-in screens.
- Insert Order modal with single/bulk order entry and CSV/Excel upload support.

## Notes

This is a front-end prototype only. Authentication, APIs, payment processing, live fulfillment, SMS delivery, and database persistence are not connected. Demo order data and sample metrics are illustrative. Product names, prices, and settings may be held in browser memory or local storage depending on the feature.
