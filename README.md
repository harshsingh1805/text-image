# 🖼️ Imagify - AI Image Generation & Editing Platform

Imagify is a full-stack web application that allows users to generate and edit images using AI (via the ClipDrop API), manage user authentication using JWT, and integrate payment processing with Razorpay and Stripe.

## 🚀 Features

- ✨ AI image editing and background removal (ClipDrop API)
- 🔐 JWT-based authentication
- 💳 Payment integration with Razorpay & Stripe
- 🌐 Fully responsive frontend
- 📦 MongoDB for secure user data and session storage

---

## 🧰 Tech Stack

**Frontend:**  
- React / Next.js  
- TailwindCSS  
- Clerk (for auth)  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT  

**APIs & Integrations:**  
- ClipDrop API  
- Razorpay  
- Stripe  

---

## 🛠️ Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/imagify.git
cd imagify
```

### 2. Install Dependency at at both frontend and backend root folder
```bash
npm install
```

###3. Create .env File at at backend root folder
```bash
# JWT Secret
JWT_SECRET=your_jwt_secret_here

# MongoDB URI
MONGODB_URI=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/imagify

# ClipDrop API
CLIPDROP_API=your_clipdrop_api_key

# Razorpay Payment Integration
CURRENCY=INR
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret

# Stripe Payment Integration
STRIPE_SECRET_KEY=your_stripe_secret_key
```

###4. Create a .env file at Frontend root Folder
```bash
VITE_BACKEND_URL = 'your-backend-url'
VITE_RAZORPAY_KEY_ID = "----- Razorpay_KEY_ID_here (Optional) ------"
```

###5. Run dev Server at Frontend at root folder
```bash
npm run dev
```

###6. Run backend Server at Backend at root folder
```bash
npm run server
```

