# Paradise Nursery Shopping Application

Welcome to **Paradise Nursery**, an e-commerce web application designed for plant enthusiasts to explore, select, and purchase a diverse collection of houseplants. This project was developed as part of the IBM Front-End Developer specialization using React and Redux Toolkit.

---

## Project Overview

- **Project Name:** Paradise Nursery Shopping Cart Application
- **Tagline:** Where Green Meets Serenity
- **Author:** anle26
- **Technologies:** React, Redux Toolkit, React-Redux, Vite, CSS3, HTML5

Paradise Nursery offers a curated catalog of houseplants divided into distinct functional categories, such as Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, and Low Maintenance plants.

---

## Features

### 1. Landing Page
- Engaging hero section with background imagery and branding for Paradise Nursery.
- Informational "About Us" section highlighting the company's mission, values, and passion for nature.
- "Get Started" button that transitions seamlessly into the plant catalog.

### 2. Product Catalog
- Over 30 unique houseplants categorized into 5 distinct groups (at least 6 plants per category).
- Each plant displays a high-resolution image, title, price, and description.
- Responsive "Add to Cart" button that dynamically disables itself once an item is added to the cart.
- Persistent navigation bar with direct links to Home, Plants listing, and the dynamic Shopping Cart counter.

### 3. Shopping Cart (Redux State Management)
- Live cart badge in the navbar displaying the total quantity of plants selected.
- Detailed cart summary showing thumbnail, name, unit price, quantity, and subtotal per item.
- Quantity adjustment controls (`+` and `-`) that update line-item and overall cart totals in real-time.
- Remove/Delete button to take items out of the cart (re-enabling the "Add to Cart" button in the catalog).
- "Continue Shopping" button to return to the catalog and a "Checkout" button with an interactive alert message.

---

## Project Structure

```text
├── public/
├── src/
│   ├── assets/
│   ├── AboutUs.css         # Styling for About Us section
│   ├── AboutUs.jsx         # Company background, mission, and story
│   ├── App.css             # Landing page styles and background image
│   ├── App.jsx             # Main application component & landing page view
│   ├── CartItem.css        # Styling for Shopping Cart view
│   ├── CartItem.jsx        # Shopping cart page component with totals & controls
│   ├── CartSlice.jsx       # Redux Toolkit slice (addItem, removeItem, updateQuantity)
│   ├── index.css           # Global resets and basic styles
│   ├── main.jsx            # Application entry point with Redux Provider
│   ├── ProductList.css     # Styling for product cards, grid, and navbar
│   ├── ProductList.jsx     # Houseplant catalog grouped by category
│   └── store.js            # Redux store configuration
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) (v16 or higher) installed on your system.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/anle26/DWP.git
   cd DWP
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to:
   ```text
   http://localhost:5173
   ```

---

## Submission Checklist

- [x] **Task 1:** `README.md` containing project name details.
- [x] **Task 2:** `AboutUs.jsx` containing company details.
- [x] **Task 3:** `App.css` implementing landing page background image.
- [x] **Task 4:** `App.jsx` implementing landing page with company name and "Get Started" button.
- [x] **Task 5:** `CartSlice.jsx` implementing Redux slice (`addItem`, `removeItem`, `updateQuantity`).
- [x] **Task 6:** `ProductList.jsx` displaying plants by category, navbar, and dynamic cart badge.
- [x] **Task 7:** `CartItem.jsx` displaying shopping cart, item totals, overall cart total, and quantity controls.

---

## License
This project is licensed under the Apache License 2.0.