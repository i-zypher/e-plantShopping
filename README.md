e-plantShopping

Paradise Nursery is a React-based online shopping app for houseplants, built as the final project for IBM's Front-End Development course.

I'm so excited to start this project! This repo is my practice project for learning front-end programming with React and Redux.

About the App

Paradise Nursery lets customers browse houseplants grouped by category (air-purifying, aromatic, insect-repellent, medicinal, and low-maintenance), add plants to a shopping cart, and manage quantities before checkout.

Features
Landing page with company background image, welcome message, and "Get Started" button
About Us section describing the company
Product listing page with plants grouped into multiple categories, each showing a thumbnail, name, description, and price
"Add to Cart" functionality with a button that disables once a plant is added
Shopping cart page showing:
Total cart amount across all items
Per-item subtotal, quantity, and unit price
Increment/decrement controls and a delete button per item
"Continue Shopping" button back to the product listing
"Checkout" button (placeholder for future functionality)
Cart icon in the navbar that dynamically shows the total number of items
Tech Stack
React
Redux Toolkit (@reduxjs/toolkit, react-redux)
Vite
CSS
Project Structure
App.jsx / App.css — landing page and app shell
AboutUs.jsx — company description
ProductList.jsx / ProductList.css — product listing page and navbar
CartItem.jsx / CartItem.css — shopping cart page
CartSlice.jsx — Redux slice managing cart state (add, remove, update quantity)
store.js — Redux store configuration
main.jsx — app entry point, wraps App in the Redux Provider
Running Locally
bash
npm install
npm run dev
Deployment

This project is configured for deployment via GitHub Pages using gh-pages:

bash
npm run deploy
