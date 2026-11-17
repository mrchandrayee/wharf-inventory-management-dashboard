# Wharf — Inventory Management Dashboard

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/wharf-inventory-management-dashboard/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A responsive, runnable HTML/CSS/JavaScript reconstruction of the supplied 36.6-second screen recording.

## Run
Open `index.html` in a modern browser. No dependencies, npm install, or build step required.

Optional local server:
```bash
python3 -m http.server 8000
```
Open `http://localhost:8000`.

## Screens recreated from the video
- **Dashboard:** revenue trend, total revenue, orders, products in stock, pending orders, order overview, low-stock alerts, recent orders and top-selling products.
- **Orders:** order list, search, status filter, create order, order detail drawer, update fulfilment status, CSV export.
- **Products:** product catalogue, search, category filter, product detail drawer and add product.
- **Inventory:** stock overview, reorder levels, low-stock labels and stock adjustment (add, remove, set exact quantity).
- **Customers:** customer cards with contact and lifetime order value.
- **Analytics:** revenue metrics, revenue trend, inventory health, category revenue and order status.
- **Settings / Appearance:** Light, System and Dark theme choices; accent colour swatches; reduce-motion and compact-density preferences.
- Responsive sidebar, top search, notifications toast and keyboard shortcut Ctrl/Cmd + K.

## Source extraction note
The video shows the product UI and interactions but does not show readable HTML/CSS/JS source editor panels. Therefore no original source code can be extracted verbatim from this recording. This project reconstructs the visible Wharf dashboard in vanilla HTML/CSS/JS. Labels, navigation, metrics and workflows are based on the visible recording; supporting order and product records are sample data.

## Demo data / backend
The visible dashboard values include revenue around `$292,520`, 1,284 orders, 8,642 products in stock and 24 pending orders; these are represented in the demo. No live inventory service, payment processor, authentication, database or order fulfilment API is connected. Changes made in the UI are local to the browser session.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
