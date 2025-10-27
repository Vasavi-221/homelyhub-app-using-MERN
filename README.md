
<p align="center">
  <h1><b>🏡 HomelyHub – MERN Stack Accommodation Booking Platform</b></h1>
  <p>Find, book, and host unique stays around the world with ease!</p>
</p>

---

## 📌 Project Overview

**HomelyHub** is a full-featured accommodation booking platform built using the **MERN Stack (MongoDB, Express.js, React, Node.js)**.  
It allows users to explore, book, and manage stays at unique homes, rooms, and villas, while hosts can list their properties and earn securely.

> “Explore the world with HomelyHub for a unique and comfy adventure!”



## ✨ Key Features

✔ **User Authentication & Security**  
• Sign up, Login, Logout with JWT-based authentication  
• Update profile, change password, manage user details  

✔ **Property Search & Filters**  
• Search stays by location, price, date, property type, amenities  

✔ **Property Listings for Hosts**  
• Hosts can list properties with images, description, price & amenities  
• Manage, update or remove their listings  

✔ **View Accommodation Details**  
• View images, amenities, pricing, reviews, and availability  

✔ **Booking System**  
• Real-time booking based on selected dates  
• Check availability, confirm booking & get booking summary  

✔ **User Dashboard**  
• Track bookings, view history, manage profile and property listings  

✔ **Secure Payment Integration**  
• Payments using a trusted payment gateway (e.g., Stripe/Razorpay)  

✔ **Responsive Design**  
• Fully mobile-friendly UI for all device sizes  



## 🛠️ Tech Stack Used

| Technology | Purpose |
|------------|---------|
| **React + Vite** | Frontend UI |
| **Node.js + Express.js** | Backend API |
| **MongoDB + Mongoose** | Database |
| **JWT + bcrypt.js** | Authentication & Security |
| **Axios / Fetch API** | API calls |
| **Redux / Context (if used)** | State Management |

## 📂 Folder Structure

HomelyHub/
│
├── backend/ # Express + Node.js server
│ ├── src/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── config/
│ ├── middleware/
│ ├── package.json
│ └── .env
│
├── Frontend/ # React + Vite frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── store/
│ │ ├── utils/
│ ├── package.json
│ ├── vite.config.js
│ └── public/
│
├── .gitignore
└── README.md


## ⚙️ Installation & Setup

### 1. Clone the Repository

git clone https://github.com/Vasavi-221/homelyhub-app-using-MERN.git
cd HomelyHub

## 2. Setup Backend
cd backend
npm install


Create a .env file in /backend with:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000


Start server:

npm start

## 3. Setup Frontend
cd ../Frontend
npm install
npm run dev

🚀 Usage

Open the app at http://localhost:5173/

Register/Login to explore homes

Search & filter properties

Book your stay or list your own property

🌐 GitHub: https://github.com/Vasavi-221

🔗 LinkedIn: https://www.linkedin.com/vasavi-veeranki-041687374/


⭐ Show Support

If you like this project, feel free to ⭐ star the repository and follow for more projects!

❤️ Fun Fact

“HomelyHub brings comfort to your journey – because every stay should feel like home.”
