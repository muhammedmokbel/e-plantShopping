# `e-plantShopping`

A React-based e-commerce shopping application for purchasing plants online. Built with Vite, Redux Toolkit, and React.

## Features

- Browse plants organized by category (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, Low Maintenance)
- Add plants to a shopping cart
- View cart with item quantities and per-item totals
- Increment or decrement item quantities directly in the cart
- Remove individual items from the cart
- Running total displayed at the top of the cart
- Continue shopping from the cart view

## Tech Stack

- **React** — UI components and state management hooks
- **Redux Toolkit** — global cart state (`CartSlice`)
- **Vite** — fast development server and build tool
- **CSS** — custom component-level styling

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm

### Installation

```bash
git clone https://github.com/<your-username>/e-plantShopping.git
cd e-plantShopping
npm install
```

### Running the App

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production

```bash
npm run build
```

## Project Structure

```
e-plantShopping/
├── public/
├── src/
│   ├── App.jsx           # Root component and landing page
│   ├── ProductList.jsx   # Plant catalogue with add-to-cart logic
│   ├── CartItem.jsx      # Cart view with quantity controls
│   ├── CartSlice.jsx     # Redux slice for cart state
│   ├── store.js          # Redux store configuration
│   └── AboutUs.jsx       # About page
├── index.html
└── vite.config.js
```

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file included in this repository.
