Choice B
🍫 Obi & Co, Ltd. — Premium Cacao E-Commerce
A luxury, animated React e-commerce interface for an artisanal chocolate brand. Built with React, Tailwind CSS, and Framer Motion.

🚀 Live Features
Premium Landing Page: Immersive dark-mode design with glassmorphic layouts.

Product Explorer: Interactive product cards showing flagship collections.

Seamless Cart & Checkout: Designed for high-conversion user pathways from browsing to buying.

🛒 User Journey
[ Browse Collections ] ➡️ [ View Product Details ] ➡️ [ Add to Cart ] ➡️ [ Secure Checkout ]
Discover: Users explore flagship bars (Dark, Milk, Hazelnut, Fruit & Nut) via an animated grid.

Select & Add: Engaging "Shop Now" micro-interactions trigger cart drawers.

Checkout: Optimized interface designed for rapid tokenized payments.

💳 Secure Payments
Integrated client-side layout for major banking networks:

Debit Cards: Real-time checking and savings authorization.

Mastercard: Secured via Mastercard Identity Check routing.

🛠️ Quick Start
1. Install Dependencies
Bash
npm install
2. Configure Tailwind Theme
Add the brand color palette to your tailwind.config.js:

JavaScript
theme: {
  extend: {
    colors: {
      cacao: '#1a0f0a',
      gold: '#d4af37',
      cream: '#f9f6f0',
    }
  }
}
3. Start Development Server
Bash
npm run dev
📂 Project Architecture
Plaintext
├── src/
│   ├── components/      # Reusable UI (Navbar, Footer, TrustBadges, GoldenRibbon, ObiLogo)
│   └── pages/           # Page layouts (Home.jsx)
└── README.md