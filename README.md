🛒 Image E-Commerce

A full-stack E-commerce web application built with Next.js, TypeScript, TailwindCSS, and NextAuth.
This project supports user authentication, product management, image uploads, and secure payment integration with Razorpay.
It also includes an admin dashboard to manage products and orders.

🚀 Features

🔐 Authentication: Secure login & registration using NextAuth.

📦 Product Management: Add, update, delete, and view products (Admin only).

🖼 Image Uploads: Integrated with ImageKit for optimized image storage.

💳 Payments: Seamless checkout experience with Razorpay integration.

🛍 Cart & Orders: Add products to cart, place orders, and track history.

⚡ Responsive UI: Built with TailwindCSS for modern, mobile-friendly design.

🛠 Admin Dashboard: Manage products and orders easily.

🏗 Tech Stack

Frontend: Next.js 14, TypeScript, TailwindCSS

Backend: Next.js API Routes

Auth: NextAuth

Payments: Razorpay

Image Handling: ImageKit

Database: (likely Prisma + PostgreSQL/MySQL – confirm based on setup)
⚙️ Installation & Setup

Clone the repository

git clone https://github.com/your-username/image-ecommerce.git
cd image-ecommerce-main


Install dependencies

npm install


Setup environment variables
Copy .env.example → .env and configure:

DATABASE_URL=your_database_url
NEXTAUTH_SECRET=your_secret
NEXTAUTH_URL=http://localhost:3000
IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_PRIVATE_KEY=your_key
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_key


Run the development server

npm run dev


Open http://localhost:3000
 


📂 Project Structure
image-ecommerce-main/
 ├── app/               # Next.js App Router (pages, API, components)
 ├── components/        # Reusable UI components
 ├── api/               # API routes (auth, products, orders, payments)
 ├── public/            # Static assets
 ├── styles/            # Global styles
 └── package.json       # Dependencies & scripts
