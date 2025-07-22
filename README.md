# ShopNest---Real-Time-E-Commerce-Platform
**ShopNest** is a dynamic and responsive **E-Commerce Web App** built with **React**, **Node.js**, and **Stripe**. Inspired by platforms like **BigBasket**, it provides users with a real-time, modern shopping experience and includes a complete **admin panel** for inventory and order management.
## 🚀 Live Demo

🌐 [https://shop-nest-19f8cc.netlify.app/]
## 🖼️ Features

### 🛍️ Customer Side
- 🔍 Real-time product search with filters (category, price, rating)
- 🧺 Live cart management — add/remove items without reload
- 📦 Stock-aware cart with auto-updating quantities
- 🧾 Product detail page with images, reviews, pricing
- 💳 Stripe-powered secure checkout
- 📱 Mobile-responsive UI + dark mode toggle

### 👨‍💼 Admin Panel
- 🧩 Add, edit, delete products with instant updates
- 📦 Track stock and manage inventory in real-time
- 📊 View orders and basic dashboard analytics
- 🔐 Role-based access (admin vs. user)

---

## 🧰 Tech Stack

| Layer         | Technology              |
|---------------|--------------------------|
| Frontend      | React.js / Vite or Next.js |
| Styling       | Tailwind CSS             |
| State Mgmt    | Redux / Context API      |
| Real-Time     | Socket.io / Firebase DB  |
| Auth          | Firebase / JWT           |
| Backend       | Node.js + Express        |
| Database      | MongoDB / PostgreSQL     |
| Payments      | Stripe API               |
| Deployment    | Netlify (Frontend), Render/Heroku (Backend)

---

## 📦 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Arpan110/shopnest.git

# Navigate into the project
cd shopnest

# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

# Run the development servers
npm run dev
🛡️ License
This project is licensed under the MIT License.
