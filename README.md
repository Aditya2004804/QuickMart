🛒 Quick Mart
Quick Mart is a full-fledged MERN stack grocery e-commerce website that allows users to browse products, add them to their cart, proceed with payment, and manage their shopping experience seamlessly.

🚀 Features
User Authentication – Signup/Login functionality

Product Listings – Dynamic product catalog with categories

Search & Filter – Quickly find products by name or category

Shopping Cart – Add, remove, and update product quantities

Checkout & Payment – Secure order placement with integrated payment system

Responsive UI – Mobile-first design using Tailwind CSS / Bootstrap

Admin Panel (optional, if you built it) – Manage products and orders

🛠️ Tech Stack
Frontend: React.js, Tailwind CSS / Bootstrap

Backend: Node.js, Express.js

Database: MongoDB

State Management: Context API / Redux (if used)

Authentication: JWT (JSON Web Token)

Payment Integration: Razorpay / Stripe (if implemented)

📂 Project Structure
Quick-Mart/
│-- backend/            # Node.js + Express APIs
│-- frontend/           # React.js UI
│   │-- src/
│       │-- components/ # Reusable components
│       │-- context/    # Context API for state
│       │-- pages/      # Product, Cart, Checkout pages
│       │-- assets/     # Images, icons, etc.
│-- .env                # Environment variables
│-- package.json
│-- README.md
⚡ Getting Started
1. Clone the repository
git clone https://github.com/your-username/quick-mart.git
cd quick-mart
2. Install dependencies
For backend:

cd backend
npm install
For frontend:

cd frontend
npm install
3. Setup Environment Variables
Create a .env file in the backend/ folder:

PORT=5000
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret-key
PAYMENT_SECRET=your-payment-key (if used)
4. Run the project
Start backend server:

cd backend
npm start
Start frontend:

cd frontend
npm run dev
Now open 👉 http://localhost:5173 in your browser.

📸 Screenshots 

<img width="1851" height="889" alt="Screenshot 2025-09-17 175101" src="https://github.com/user-attachments/assets/491bc082-aefb-4395-8c04-4d971d7dd692" />
<img width="1795" height="852" alt="Screenshot 2025-09-17 175114" src="https://github.com/user-attachments/assets/f7824bfb-11de-44ee-9bd3-7d2aaa5ab3be" />
<img width="1795" height="852" alt="Screenshot 2025-09-17 175114" src="https://github.com/user-attachments/assets/faab3d0d-cef9-4ec1-a20b-3367934b1ca7" />

🏠 Homepage

🛒 Product Listings

🛍️ Cart Page

💳 Checkout

