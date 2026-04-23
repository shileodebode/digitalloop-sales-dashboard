# Digitalloop Sales Dashboard

A modern, fully interactive sales dashboard built with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools — just open and go.

**Live Demo:** [https://shileodebode.github.io/digitalloop-sales-dashboard/](https://shileodebode.github.io/digitalloop-sales-dashboard/)

---

## Features

- **Dashboard Overview** — Key KPIs at a glance: total revenue, active orders, customer count, and average sale value
- **Analytics** — Monthly revenue vs. orders trend, revenue by product, and order status breakdown with interactive charts
- **Customer Management** — Customer cards with total spend and order history; add new customers via modal
- **Inventory Tracking** — Stock levels with low-stock alerts and one-click restock functionality
- **Quick Sale Modal** — Log new transactions directly from any page
- **Dark Mode** — Toggle between light and dark themes, with charts that adapt automatically
- **Search** — Filter transactions in real time by customer name or product
- **Responsive Design** — Fully mobile-friendly with a collapsible sidebar

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Charts | [Chart.js v4](https://www.chartjs.org/) |

No npm, no bundler, no dependencies to install.

---

## Getting Started

### Run locally

Just open the file in your browser:

```bash
# Clone the repo
git clone https://github.com/shileodebode/digitalloop-sales-dashboard.git

# Open in browser
open digitalloop-sales-dashboard/dashboard.html
```

Or simply double-click `dashboard.html` in your file explorer.

### Deploy

The project is already deployed via GitHub Pages. To redeploy after making changes:

```bash
git add dashboard.html
git commit -m "Update dashboard"
git push origin main
```

GitHub Pages will automatically rebuild within a minute or two.

---

## Project Structure

```
digitalloop-sales-dashboard/
└── dashboard.html      # Single-file app — all HTML, CSS, and JS in one place
```

---

## Pages

| Page | Description |
|------|-------------|
| Dashboard | Revenue overview, category donut chart, latest transactions |
| Analytics | Dual-axis trend chart, product revenue bar chart, status doughnut, full transaction table |
| Customers | Customer card grid with spend stats; add new customers |
| Inventory | Product stock table with low-stock badges and restock modal |
| Settings | Theme toggle and notification preferences |

---

## Demo Data

The dashboard runs on in-memory demo data that resets on page refresh. To connect it to a real data source, replace the `transactions`, `inventory`, `customers`, and `performance` arrays at the top of the `<script>` block with API calls.

---

## License

MIT — free to use, modify, and distribute.
