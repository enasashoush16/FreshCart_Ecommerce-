# FreshCart Ecommerce 🛒

A modern, responsive full-stack e-commerce web application built using **React**, **Bootstrap**, and integrated with external APIs for dynamic product management and secure payment processing. 

The application utilizes a custom-built routing structure optimized for seamless navigation and smooth user experience.

---

## 🚀 Live Demo
Check out the live application here:  
👉 **[[Your Live GitHub Pages URL Goes Here]](https://fresh-cart-ecommerce-xmla.vercel.app/)**

---

## ✨ Features

* **Dynamic Product Catalog:** Browse a wide variety of items featuring responsive layout carousels for showcasing daily deals.
* **Authentication State Management:** Utilizes a custom dynamic token-based context logic (`authContext`) to securely persist and handle user sessions across components via `localStorage`.
* **Full-Featured Shopping Cart:** Add products, update quantities dynamically, calculate total price summaries, and clear items natively with real-time feedback.
* **Integrated Checkout System:** Seamless order fulfillment using Formik validation, capturing user shipping addresses, and linking to external secure checkout sessions.
* **Wishlist Integration:** Keep track of your favorite products effortlessly.
* **Robust Client-Side Routing:** Utilizes `createHashRouter` to manage multiple views cleanly without broken deep links on deployment platforms.

---

## 🛠️ Tech Stack & Architecture

This project is built using modern frontend tools and libraries:

* **Core:** React (Functional Components & Hooks), JavaScript (ES6+), HTML5, CSS3
* **Routing:** `react-router-dom` (configured with `createHashRouter`)[cite: 5]
* **State Management:** React Context API (`authContext`[cite: 2], `cartContext`[cite: 3], `WishlistContextProvider`[cite: 5])
* **Styling & UI Components:** Bootstrap 5[cite: 7], FontAwesome[cite: 7], `react-slick` (Carousels)[cite: 1]
* **Form Handling:** Formik & Axios (API interaction)[cite: 4]
* **Data Fetching:** React Query (`QueryClientProvider`)[cite: 5]
* **Feedback:** `react-hot-toast` (Notifications)[cite: 3, 4, 5], `react-loader-spinner`[cite: 3]

---

## 📂 Project Structure Highlights

Here are some of the key files handling the core application logic:
* **`App.jsx`**: Houses the core router setup (`createHashRouter`), global context providers mapping, and error-handling boundaries (404 views)[cite: 5].
* **`index.js`**: Controls the foundational React DOM tree rendering, styling attachments, and performance auditing triggers[cite: 7].
* **`components/Home.jsx`**: Handles the primary landing environment displaying promotional product sliders and primary item collections[cite: 1].
* **`components/authen.jsx`**: Manages user authentication tokens state hooks natively mapping local cache checks (`tkn`)[cite: 2].
* **`components/Cart.jsx`**: Houses operational logic for basket changes, quantity adjustments, item deletions, and layout rendering[cite: 3].
* **`components/CheckOut.jsx`**: Manages shipping validation constraints through Formik and manages successful external payment gateway handoffs[cite: 4].

---

## 🔧 Installation & Local Setup

Follow these steps to run the project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/enasashoush16/FreshCart_Ecommerce-.git](https://github.com/enasashoush16/FreshCart_Ecommerce-.git)
   cd FreshCart_Ecommerce-

### Install dependencies:

``` Bash
npm install --legacy-peer-deps

npm start

npm run build ```
