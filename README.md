# 🌐 My Web Development Portfolio  

Welcome to my collection of **MERN stack and full-stack web development projects**, showcasing scalable architectures, authentication flows, REST APIs, and React-based frontends.  

---

## 1. 🏡 Nestify – Home Rental Web App  
**Live Demo:** [Nestify on Render](https://nestify-homerentalapp.onrender.com/listings)  
**GitHub Repo:** [ManikPandey/nestify_HomeRentalApp](https://github.com/ManikPandey/nestify_HomeRentalApp)  

A full-stack **Airbnb-style home rental platform** built with **Node.js, Express, MongoDB, and EJS**. Features secure authentication, image uploads to Cloudinary, RESTful routing, and session handling.  

### 🚀 Key Features  
- 🏘️ Users can create, view, and rent listings with media  
- 🔐 Authentication & Authorization with **Passport.js**  
- ☁️ **Cloudinary integration** for smooth image uploads  
- 💬 Flash messaging for instant user feedback  
- 🧠 Joi-based schema validation  
- 🏗 Organized **MVC architecture**  
- 📦 Deploy-ready (Render + MongoDB Atlas + Cloudinary)  

### 🧰 Tech Stack  
- **Frontend:** EJS + CSS  
- **Backend:** Node.js, Express.js, MongoDB (Mongoose)  
- **Auth:** Passport.js + Sessions  
- **Media:** Multer + Cloudinary  

### 📌 Getting Started  
```bash
git clone https://github.com/ManikPandey/nestify_HomeRentalApp.git
cd nestify_HomeRentalApp
npm install
```
Add your .env with DB_URL, CLOUDINARY creds `node app.js`

---

## 2. 🎓 LogiStudent – Full-Stack Campus Logistics Platform  
**Live Project:** [LogiStudent Client (Netlify)](https://imaginative-hotteok-8268cb.netlify.app/)  
**Live API:** [LogiStudent Backend (Render)](https://logistudent.onrender.com)  
**GitHub Repo:** [ManikPandey/LogiStudent](https://github.com/ManikPandey/LogiStudent)  

A **production-ready MERN stack platform** developed to help students securely manage their luggage during semester breaks. Inspired by a **real-life logistics service for 50+ students**, it digitizes bookings, payments, and admin workflows.  

### 🚀 Key Features  

**👩‍🎓 Student Side:**  
- JWT Authentication & bcrypt-secured logins  
- Multi-step booking with slot availability  
- Real-time booking + payment status tracking  
- Manual UPI transaction submission & validation  
- Testimonial-driven homepage  

**🛠 Admin Side:**  
- Role-based access control (RBAC)  
- Centralized booking dashboard  
- Real-time slot management with CRUD ops  
- Status updates synchronized across dashboards  
- Automatic slot capacity tracking  

### 🧰 Tech Stack  
- **Frontend:** React, Redux Toolkit, Material UI  
- **Backend:** Node.js, Express.js, Mongoose  
- **Database:** MongoDB Atlas  
- **Auth:** JWT, bcrypt.js  
- **Deployment:** Netlify (UI) + Render (Backend)  

### 📌 Getting Started 
```bash
git clone https://github.com/ManikPandey/LogiStudent.git
cd logistudent
```
Backend Setup
```bash
cd server
npm install
```
add .env -> MONGO_URI, JWT_SECRET
```bash
npm run dev
```
Frontend Setup
```bash
cd ../client
npm install
npm start
```
---
## 3. ⛅ React + Vite Weather App  
**Live Demo:** [WeatherApp Project](https://github.com/ManikPandey/WeatherApp_using_Reactjs)  
**GitHub Repo:** [ManikPandey/WeatherApp_using_Reactjs](https://github.com/ManikPandey/WeatherApp_using_Reactjs)  

A lightweight **weather application** built with **React (Vite)** and styled with Material UI. Fetches real-time weather data by city name and displays it in a modern, responsive UI.  

### 🚀 Key Features  
- 🔍 Search weather by **city name**  
- 🌡️ Displays temperature, humidity, min/max, and sky conditions  
- 📱 Responsive UI with Material UI cards  
- ⚛️ Built using **React (Vite) + Axios API calls**

### 📌 Getting Started  
```bash
git clone https://github.com/ManikPandey/WeatherApp_using_Reactjs.git
cd weather-app-react
npm install
npm run dev
```
## 4. :rose: Olcademy Internship Assignment - Full Stack Perfume Shop
**GitHub Repo:** [ManikPandey/Perfume-Shop_Web](https://github.com/ManikPandey/Perfume-Shop_Web)  

The application is designed with a strong focus on a clean, premium user interface and a seamless user experience, drawing inspiration from high-end e-commerce designs. All data is dynamically served from a custom-built backend API.

### 🚀 Key Features  
- 🔍 **Responsive Navigation Bar:** A clean and sticky navbar that collapses into a hamburger menu on mobile devices. 
- 🌡️ **Detailed Product Information:** Dynamically loads product name, full description, price, and available sizes
- 📱 Responsive UI with Material UI cards  
- ⚛️ Built using **React (Vite) + Axios API calls**

### 📌 Getting Started  
Terminal 1
```bash
git clone https://github.com/ManikPandey/WeatherApp_using_Reactjs.git
```
Terminal 1
```bash
cd server
npm install
npm run dev
npm run data:import
npm run dev
```
Terminal 2
```bash
cd client
npm install
npm start
```
---

# 🌍 Deployment Overview  
- **Nestify:** Render (Backend + Frontend), MongoDB Atlas, Cloudinary  
- **LogiStudent:** Netlify (Frontend), Render (API), MongoDB Atlas  
- **Weather App:** Vite (Local/Netlify), OpenWeather API  
- **Perfume-Shop:** Vite (Local/Netlify), Interactive , Dynamic , Attractive , Userfriendly 
--- 

# 🙌 Author  
👨‍💻 **Manik Pandey**  
📎 GitHub: [@ManikPandey](https://github.com/ManikPandey)  

