# 🏡 **Property Rental Platform — MERN Stack (Airbnb-Style Clone)**

*A complete property rental application built using MongoDB, Express.js, React, and Node.js.*

---

## 🚀 **Overview**

A full-stack Airbnb-style platform where users can search properties, view listings on an interactive map, make bookings, leave reviews, and manage profiles.
Hosts can list properties, update pricing and availability, upload images, and manage bookings through a dedicated dashboard.

Built entirely with the **MERN stack**, the project showcases REST API development, secure authentication, map integrations, role-based access, and scalable design.

---

## 🗓️ **Project Duration**

**August 2024 – October 2024**

---

# 📌 **Key Features**

### 🔐 Authentication & Authorization

* JWT-based login and signup
* Role-based access: *Guest*, *Host*, *Admin*
* Secure protected routes & middleware

### 🏘️ Host Property Management

* Add/update/remove property listings
* Upload images, amenities, rules, pricing
* Manage availability & view bookings
* Host dashboard with analytics

### 🔍 Property Search + Filters

* Search by city / location
* Price, rating, date, amenities filters
* Mapbox-based interactive map
* MongoDB GeoJSON & geo-indexing

### 📆 Booking System

* Real-time availability checks
* Dynamic pricing calculation
* Prevent overlapping bookings
* Booking history & cancellation logic

### ⭐ Reviews & Ratings

* One review per booking
* Edit/delete reviews
* Average rating computation

---

# 🛠️ **Tech Stack**

### **Frontend**

* React (Hooks, Context)
* Axios
* Tailwind / Custom CSS
* Mapbox GL JS

### **Backend**

* Node.js
* Express.js
* REST APIs
* JWT Security

### **Database**

* MongoDB
* GeoJSON indexing

### **DevOps**

* Docker
* Docker Compose
* Git & GitHub

---

# 📐 **Architecture Overview**

```
 React UI  →  Express API  →  MongoDB Database
                       ↑
                  Authentication
```

* React handles UI, state, maps, booking flows
* Express manages APIs, validation, business logic
* MongoDB stores properties, bookings, users, reviews

---

# 🔧 **Installation & Setup**

### 1️⃣ Clone the repository

```bash
git clone https://github.com/dhanraj-gif/Wanderlust.git
cd property-rental-platform
```

### 2️⃣ Install backend dependencies

```bash
cd backend
npm install
npm start
```

### 3️⃣ Install frontend dependencies

```bash
cd ../frontend
npm install
npm run dev
```

### 4️⃣ Environment Variables (`.env`)

```
MONGO_URI=
JWT_SECRET=
MAPBOX_KEY=
```

### 5️⃣ Run with Docker

```bash
docker-compose up --build
```

---

# 📚 **Future Enhancements**

* Stripe/PayPal payment integration
* Real-time chat (WebSockets)
* Wishlist / Favorites
* Microservices + Kubernetes deployment

---

# 👤 **Contact**

**Dhanraj Kamuni**
📧 [dhanrajkamuni7@gmail.com](mailto:dhanrajkamuni7@gmail.com)
🔗 LinkedIn: [https://www.linkedin.com/in/dhanrajkamuni7](https://www.linkedin.com/in/dhanrajkamuni7)
🐙 GitHub: [https://github.com/dhanraj-gif](https://github.com/dhanraj-gif)

---

# 🔗 **Project Link**

👉(https://delta-project-6fua.onrender.com/)

---

If you want a **LinkedIn-optimized project description**, a **one-paragraph interview explanation**, or a **diagram for system design**, just tell me!
