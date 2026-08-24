# Swiggy-Inspired Food Delivery UI

A responsive food-delivery web application inspired by Swiggy, built with **React, TypeScript, Tailwind CSS, and Vite**.

The project focuses on recreating a modern food-delivery experience with reusable components, responsive layouts, client-side routing, and functional interactions such as restaurant browsing, menu selection, cart management, search, offers, and support.

Originally developed as part of the **UI Arena UI Clone Challenge** and now maintained as a portfolio project.

## 🚀 Live Demo

**[View Live Demo](https://ui-arena-ui-clone-challenge-lake.vercel.app/)**

## 📌 Overview

This project recreates the core user experience of a modern food-delivery platform through a responsive React application.

It includes multiple pages and interactive UI components rather than being limited to static screen designs.

### Main Functionality

- Restaurant browsing
- Restaurant-specific menus
- Food category browsing
- Search
- Cart management
- Item customization
- Offers and coupons
- Sign-in drawer
- Help and FAQ sections
- Checkout flow
- Order confirmation
- Responsive layouts

## ✨ Features

### 🏠 Home Page

- Food category browsing
- Restaurant listings
- Restaurant cards with ratings, cuisines, delivery information, and offers
- Responsive restaurant grid and layouts

### 🍽️ Restaurant & Menu

- Restaurant-specific menu pages
- Categorized menu sections
- Expandable menu sections
- Add-to-cart functionality
- Item customization modal

### 🛒 Cart & Checkout

- Add and remove items
- Increase and decrease item quantities
- Automatic subtotal calculation
- Bill summary
- Checkout flow
- Order confirmation screen

### 🔎 Search

- Search interface for restaurants and dishes
- Search results page
- Responsive search experience

### 🎁 Offers

- Restaurant offers
- Coupon section
- Bank offers
- Reusable offer cards

### 👤 Sign-In Drawer

- Slide-in sign-in interface
- Shared UI state management
- Accessible from the application header

### ❓ Help & Support

- Help sidebar
- FAQ accordion
- Categorized support content

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React | UI development |
| TypeScript | Type-safe development |
| Vite | Development and build tooling |
| Tailwind CSS | Responsive styling |
| React Router | Client-side routing |
| React Context API | Shared cart and UI state |
| Lucide React | Interface icons |
| Oxlint | Code quality and linting |

## 🧩 Project Structure

The application is organized around reusable components, route-level pages, shared state, data modules, and utility functions.

```text
src/
├── components/
│   ├── Button/
│   ├── Cart/
│   ├── CartDrawer/
│   ├── FAQAccordion/
│   ├── FoodCategory/
│   ├── Header/
│   ├── HelpSidebar/
│   ├── MenuItem/
│   ├── OfferCard/
│   ├── RestaurantCard/
│   ├── RestaurantGrid/
│   ├── SearchBar/
│   ├── SearchResults/
│   ├── SignInDrawer/
│   └── common/
│
├── pages/
│   ├── Home/
│   ├── Restaurant/
│   ├── Search/
│   ├── Offers/
│   ├── Cart/
│   ├── Help/
│   └── OrderConfirmed/
│
├── context/
│   ├── CartContext.tsx
│   └── UIContext.tsx
│
├── hooks/
│   ├── useCart.ts
│   └── useUI.ts
│
├── data/
│   ├── restaurants.ts
│   ├── menu.ts
│   ├── categories.ts
│   └── offers.ts
│
├── types/
├── utils/
├── App.tsx
├── main.tsx
└── index.css
````

## 🧠 Key Implementation Details

### Reusable Components

The interface is divided into reusable components for elements such as:

* Restaurant cards
* Restaurant grids
* Menu items
* Cart items
* Offer cards
* Search components
* FAQ accordions
* Sign-in drawer
* Help sidebar

This keeps the UI modular and makes individual sections easier to maintain and reuse.

### State Management

The application uses the **React Context API** for shared application state.

* `CartContext` manages cart items and cart operations.
* `UIContext` manages shared UI state such as the sign-in drawer.

Custom hooks provide convenient access to these contexts:

* `useCart`
* `useUI`

### Routing

React Router is used for client-side navigation between the application's main sections, including:

* `/`
* `/restaurant/:id`
* `/search`
* `/offers`
* `/cart`
* `/help`

### Responsive Design

The interface is designed to adapt across:

* Desktop
* Tablet
* Mobile

Responsive styling is implemented using Tailwind CSS.

## 📱 UI Highlights

The project includes multiple interactive interfaces such as:

* Restaurant discovery
* Menu browsing
* Search
* Cart drawer
* Full cart and checkout
* Offers
* Sign-in drawer
* Help sidebar
* FAQ accordion
* Order confirmation

## ⚙️ Getting Started

### Prerequisites

Make sure you have **Node.js** and **npm** installed.

### Installation

Clone the repository:

```bash
git clone https://github.com/bhavyasraghu/Swiggy-UI-Clone.git
```

Navigate into the project:

```bash
cd Swiggy-UI-Clone
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL displayed by Vite, typically:

```text
http://localhost:5173
```

## 📦 Production Build

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## 🚀 Deployment

The project is deployed using **Vercel**.

**[View the deployed application](https://ui-arena-ui-clone-challenge-lake.vercel.app/)**

## 📊 Project Status

**Completed**

Originally created for the UI Arena UI Clone Challenge, this project is now maintained as a portfolio project demonstrating frontend development, responsive UI implementation, component-based architecture, state management, and client-side routing.

## ⚠️ Disclaimer

This is an **independent educational project inspired by the Swiggy user interface**.

It is not affiliated with, endorsed by, or officially connected to Swiggy.

The project uses mock/local data and does not implement Swiggy's backend, authentication system, payment processing, or production APIs.
