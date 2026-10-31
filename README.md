# 🌿 Delizia – Vegetarian Food Delivery Website

## About the Project

Delizia is a responsive, frontend-only vegetarian food delivery website developed using HTML, CSS, and JavaScript.

It provides an interactive food-ordering experience where users can explore vegetarian restaurants, browse food menus, add items to a shopping cart, manage quantities, and proceed through a checkout process with different demo payment options.

The website is designed with a modern interface, attractive food imagery, smooth animations, and a mobile-friendly layout.

## Features

### 🏠 Home Page
- Attractive hero section with a food-themed background.
- Navigation links to different website sections.
- Highlights vegetarian food and delivery features.
- Responsive navigation menu for smaller screens.

### 🍽️ Restaurant Listings
- Three featured restaurants:
  - Spice Garden
  - Green Bowl
  - Pasta Palace
- Restaurant ratings, cuisine information, and estimated delivery times.
- Select a restaurant to view its food menu.

### 📋 Food Menu
- Displays vegetarian dishes from different restaurants.
- Filter dishes by category:
  - Indian
  - Healthy
  - Italian
- Displays food images, names, categories, and prices.
- Add food items directly to the cart.

### 🛒 Shopping Cart
- Add food items to the cart.
- Increase or decrease item quantities.
- Remove items from the cart.
- Automatically calculates:
  - Subtotal
  - Delivery fee
  - 5% tax
  - Final total
- Displays the total number of selected items.

### 📦 Checkout System
- Three-step checkout process:
  1. Delivery Details
  2. Payment Method
  3. Order Confirmation
- Collects customer name, phone number, delivery address, city, and PIN code.
- Includes basic form validation.
- Generates a demo order ID after simulated payment.

### 💳 Payment Options

The checkout interface provides three payment options:

- **UPI QR Code:** Generates a scannable demonstration QR code.
- **Credit / Debit Card:** Provides a simulated card payment interface.
- **Cash on Delivery:** Provides a simulated cash-on-delivery confirmation.

**Important:** All payment methods are for demonstration purposes only. No real payment is processed. The UPI QR code uses a demo payment address and must not be used for actual transactions.

### 📩 Contact Section
- Contact form with name, email, subject, and message fields.
- Basic input validation.
- Displays success and error notifications using toast messages.

### 📱 Responsive Design
- Adapts to desktop, tablet, and mobile screen sizes.
- Includes responsive navigation and flexible layouts.
- Uses CSS animations and interactive visual effects.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling, animations, layouts, and responsiveness |
| JavaScript | Menu rendering, cart management, checkout, and validation |
| QRCode.js | Generates demonstration UPI QR codes |
| Google Fonts | Typography using Playfair Display and Poppins |

## Project Structure

```text
Delizia/
│
├── index.html
└── README.md
```

The HTML file contains the website structure, CSS styling, and JavaScript functionality.

## External Resources

The project uses the following external resources:

- Google Fonts for typography.
- QRCode.js library through CDN for QR code generation.
- Online image URLs for restaurant and food images.

An internet connection is required for these external resources to load correctly.

## How to Run the Project

No Python installation, backend server, or package installation is required.

**Step 1:** Download or clone this repository.

**Step 2:** Open the `Delizia` folder.

**Step 3:** Locate the `index.html` file.

**Step 4:** Double-click `index.html` to open the website in your browser.

Alternatively, open the project folder in Visual Studio Code and open `index.html` in your browser.

## How to Use

1. Open the Delizia website.
2. Explore the available vegetarian restaurants.
3. Select a restaurant or browse dishes using the menu filters.
4. Click **Add** to add food items to your cart.
5. Open the shopping cart to manage quantities and view the total amount.
6. Click **Proceed to Checkout**.
7. Enter the required delivery details.
8. Select a payment method: UPI, Card, or Cash on Delivery.
9. Complete the simulated payment process.
10. View the order confirmation and generated demo order ID.

## Project Limitations

Delizia is a frontend demonstration project and does not have a connected backend or database.

- Orders are not sent to actual restaurants.
- Payments are simulated; no real transactions take place.
- Customer and delivery details are not stored on a server.
- Contact form messages are not actually delivered.
- Cart information is not permanently saved after the page is refreshed.
- Restaurant listings, ratings, and delivery estimates are demonstration content.

## Purpose of the Project

The purpose of Delizia is to demonstrate frontend web development concepts through an interactive vegetarian food delivery website.

It showcases website design, responsive layouts, JavaScript-based dynamic content, shopping cart calculations, form validation, and a multi-step checkout interface.

## Author

Developed as a frontend web development project.
