# Swiggy-Inspired Food Delivery UI

A responsive food-delivery web application recreating the core user experience and visual patterns of Swiggy using **React, TypeScript, Tailwind CSS, and Vite**.

Built as part of the **UI Arena UI Clone Challenge**, with a focus on UI accuracy, reusable components, responsive design, and functional interactions.

## 🚀 Live Demo

**[View Live Demo](https://ui-arena-ui-clone-challenge-lake.vercel.app/)**

## 📌 Overview

This project recreates a modern food-delivery platform interface with multiple pages and interactive UI elements.

Rather than building only static screens, the application includes functional navigation, restaurant browsing, menu interactions, cart management, search, offers, help/support content, and a sign-in drawer.

## ✨ Features

### 🏠 Home Page

* Food category browsing
* Restaurant listings
* Restaurant cards with ratings, cuisines, delivery information, and offers
* Responsive layouts for different screen sizes

### 🍽️ Restaurant & Menu

* Restaurant-specific menu pages
* Categorized menu sections
* Expandable menu accordions
* Add-to-cart functionality
* Item customization modal

### 🛒 Cart

* Add and remove items
* Increase/decrease item quantities
* Automatic subtotal calculation
* Bill summary
* Checkout flow
* Order confirmation screen

### 🔎 Search

* Search restaurants and dishes
* Search results interface
* Responsive search experience

### 🎁 Offers

* Restaurant offers
* Coupons
* Bank offers
* Offer cards with reusable components

### 👤 Sign-In Drawer

* Right-side sign-in drawer
* Reusable UI state management
* Accessible from the application header

### ❓ Help & Support

* Help/support sidebar
* FAQ accordion
* Categorized support content

## 🛠️ Tech Stack

| Technology        | Purpose                                  |
| ----------------- | ---------------------------------------- |
| React             | UI development                           |
| TypeScript        | Type-safe development                    |
| Vite              | Development and production build tooling |
| Tailwind CSS      | Responsive styling                       |
| React Router      | Client-side routing                      |
| React Context API | Global cart and UI state                 |
| Lucide React      | Icons                                    |
| ESLint/Oxlint     | Code quality                             |

## 🧩 Architecture

The application is organized around reusable components and route-level pages.

```text
src/
├── components/
│   ├── Header/
│   ├── RestaurantCard/
│   ├── RestaurantGrid/
│   ├── MenuItem/
│   ├── Cart/
│   ├── CartDrawer/
│   ├── OfferCard/
│   ├── SearchBar/
│   ├── SearchResults/
│   ├── SignInDrawer/
│   ├── FAQAccordion/
│   └── ...
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
│   ├── offers.ts
│   └── help.ts
│
├── types/
├── utils/
└── App.tsx
```

## 🧠 Key Implementation Details

### Reusable Components

The UI is broken into reusable components such as restaurant cards, menu items, offer cards, search components, cart components, and FAQ accordions.

This keeps the interface consistent while making individual sections easier to maintain.

### State Management

The application uses the **React Context API** for shared state.

* `CartContext` manages cart items and cart operations.
* `UIContext` manages UI-level state such as the sign-in drawer.

Custom hooks such as `useCart` and `useUI` provide convenient access to these contexts.

### Routing

React Router is used for client-side navigation between:

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

The layouts and reusable components use responsive styling to maintain usability across screen sizes.

## ⚙️ Getting Started

### Prerequisites

Make sure you have **Node.js** and **npm** installed.

### Installation

Clone the repository:

```bash
git clone https://github.com/bhavyasraghu/UI-Arena-UI-Clone-Challenge.git
```

Navigate into the project:

```bash
cd UI-Arena-UI-Clone-Challenge
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

A GitHub Pages deployment workflow is also included in the repository through GitHub Actions.

## 📊 Project Status

**Completed**

This project was created as a submission for the UI Arena UI Clone Challenge. The challenge has now concluded, and the repository is maintained as a portfolio project demonstrating frontend development and UI implementation skills.

## ⚠️ Disclaimer

This is an **independent educational project inspired by the Swiggy user interface**.

It is not affiliated with, endorsed by, or officially connected to Swiggy.

The project uses mock/local data and does not implement Swiggy's backend, authentication system, payment processing, or production APIs.
