# 4M COFFEE

A modern-luxury coffee shop website built with Vite.

## Features
- Public storefront with menu, story, and visit sections
- Admin dashboard with sales overview and a 7-day chart
- In-store cashier / POS with payment method selection
- Product add, edit, and delete
- Transaction history
- Printable receipts (browser print dialog → Save as PDF)

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## Data note
This first version stores products and transactions in the current browser's localStorage. It is suitable as a functional prototype on one device, but it is not shared across devices and is not a secure multi-user admin system. Connect a backend and authentication before using it for real business records.

## Before publishing
Update the address, Instagram handle, WhatsApp number, opening hours, and menu/prices to the shop's real details.
