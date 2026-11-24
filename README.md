# e-plantShopping 🌿

A front-end web application for an online houseplant nursery built with React. Users can explore the nursery on a landing page, browse a categorized catalog of houseplants, add plants to their cart, and manage item quantities in real time during checkout.

## Features

### 1. Landing Page
- Full-screen background image showcasing indoor greenery.
- Prominent company branding and nursery name.
- Introductory paragraph detailing the company's mission and plant care philosophy.
- **Get Started** button that navigates directly to the product listing page.

### 2. Navigation Header
- Displayed across both the Product Listing and Shopping Cart pages.
- Dynamic shopping cart icon displaying a live badge with the total number of items currently in the cart.
- Contextual navigation links to switch smoothly between the Landing Page, Product Listing Page, and Shopping Cart Page.

### 3. Product Listing Page
- Catalog of **6+ unique houseplants** organized into **3+ distinct categories** (e.g., *Air Purifying*, *Aromatic & Fragrant*, *Low Maintenance*).
- Each plant card displays:
  - Thumbnail image
  - Plant name
  - Unit price
  - **Add to Cart** button (dynamically updates state/disables once added to prevent duplicate entries).

### 4. Shopping Cart Page
- Prominent summary displaying the **total number of plants** and the **total cost** of all items in the cart.
- Itemized list of every plant type in the cart, including:
  - Plant thumbnail and name
  - Unit price and real-time item subtotal
  - **Increase (`+`)** and **Decrease (`-`)** buttons to adjust quantities in real time, automatically syncing both the cart totals and the header's cart icon count
  - **Delete** button to remove a plant type completely from the cart
- Action buttons to **Continue Shopping** (returns to the product listing) or **Checkout**.

## Tech Stack

- **Frontend:** React (Functional Components & Hooks)
- **State Management:** Redux Toolkit (`CartSlice` & Store)
- **Styling:** CSS3 (Flexbox & CSS Grid)
- **Build Tool:** Vite
