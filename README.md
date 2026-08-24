# Swiggy-Inspired Food Delivery UI

A responsive food-delivery web application inspired by Swiggy, built with **React, TypeScript, Tailwind CSS, and Vite**.

The project focuses on recreating a modern food-delivery experience with reusable components, responsive layouts, client-side routing, and functional interactions such as restaurant browsing, menu selection, cart management, search, offers, and support.

Originally developed as part of the **UI Arena UI Clone Challenge** and now maintained as a portfolio project.

## 🚀 Live Demo

**[View Live Demo](https://ui-arena-ui-clone-challenge-lake.vercel.app/)**

## 📌 Overview

This project recreates the core user experience of a modern food-delivery platform through a responsive React application.

It includes multiple pages and interactive UI components rather than being limited to static screen designs.

### Main functionality

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
