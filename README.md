# Myntra Functional Clone 🛍️

A frontend e-commerce project inspired by Myntra, built with **HTML5, CSS3, and Vanilla JavaScript**. It features dynamically rendered products, shopping bag management, and persistent cart data.

> Educational project only. Not affiliated with Myntra. No real orders or payments are processed.

## Features

- Dynamic product cards with images, brand names, ratings, prices and discounts
- Add products to the shopping bag
- Live bag item counter
- View and remove items from the bag
- Automatic calculation of total MRP, discount, convenience fee and final amount
- Shopping bag persistence using browser `localStorage`
- Separate home and bag pages

## Tech Stack

- **HTML5** — page structure
- **CSS3** — styling and layout
- **JavaScript (ES6)** — dynamic rendering, cart logic and price calculation
- **localStorage** — saving selected products across refreshes
- **Google Material Symbols** — UI icons

## Folder Structure

```text
Myntra-Functional-Clone/
├── css/
│   ├── index.css
│   └── bag.css
├── data/
│   └── items.js
├── images/
│   ├── 1.jpg ... 8.jpg
│   └── myntra_logo.webp
├── pages/
│   └── bag.html
├── scripts/
│   ├── index.js
│   └── bag.js
├── index.html
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/akshitofficials/Myntra-Functional-Clone.git
   ```
2. Open the project folder in VS Code.
3. Open `index.html` in a browser or with the VS Code Live Server extension.
4. Select **Add to Bag** on any product and open the **Bag** page to review your selection.

No dependencies or build commands are required.

## How It Works

1. `data/items.js` stores the product information.
2. `scripts/index.js` renders products, adds items to the bag, updates the counter, and saves IDs in `localStorage`.
3. `pages/bag.html` displays the shopping bag interface.
4. `scripts/bag.js` loads saved items, renders them, removes products, and calculates totals.

**Price calculation:**

```text
Final Amount = Total MRP - Total Discount + Convenience Fee
```

The current convenience fee is fixed at **₹90**.

## Screenshots

Add your own screenshots of the home and shopping bag pages to a `screenshots/` folder. Then add the following Markdown to this section:

```markdown
![Home Page](screenshots/home.png)
![Shopping Bag](screenshots/bag.png)
```

## Live Demo

*Add your deployed website URL here.*

## Current Limitations

This is a **frontend-only** project. The search field, some navigation links, profile, wishlist, and Place Order button are not fully functional. There is no backend, user authentication, or payment integration.

## Future Improvements

- Product search and category filters
- Responsive mobile layout
- Wishlist and sorting features
- Checkout and backend integration

## Author

**Akshit Aggarwal**  
GitHub: [@akshitofficials](https://github.com/akshitofficials)

---

*Created to practice frontend development, DOM manipulation, array methods, and browser storage.*
