# 🏨 Luxovia

Luxovia is a full-stack hotel booking web application built using the **MERN** stack. It allows users to seamlessly browse, search, and book hotels across various cities. User authentication is powered by **Clerk**, images are hosted via **Cloudinary**, and secure payments are handled through **Stripe**.

## 🌐 Live Demo

🔗 [Click here to visit Luxovia](https://luxovia-ridima-shrotriyas-projects.vercel.app/)

---

## 🚀 Features

- 🔐 User authentication with **Clerk**
- 🏨 Hotel listing and room booking functionality
- 🔍 Search hotels by **city** based on user preference
- 🖼️ Image upload and storage using **Cloudinary**
- 💳 Secure payments with **Stripe**
- 📱 Responsive design for all devices

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Vite

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose

**Third-party Services:**
- Clerk (Authentication)
- Cloudinary (Image Storage)
- Stripe (Payment Gateway)


## 🔧 Getting Started

### 1. Clone the Repository
git clone https://github.com/ridimashrotriya12/Luxovia.git
cd Luxovia  

**Install Dependencies**
npm install


**Configure Environment Variables**
Create a .env file in both the frontend and backend directories with the following (replace with your own keys):
# Backend
MONGODB_URI=your_mongodb_uri
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
CLERK_SECRET_KEY=your_clerk_secret_key
PORT=5000


**Run the Application**

npm run dev


