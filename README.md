# 🌍 WanderLust Project 🏡

## Project Summary
**WanderLust** is a comprehensive Full Stack Web Development project designed to facilitate the browsing and booking of vacation accommodations, including houses, villas, and farmhouses.  

Users can **add their own properties** to the listing, book accommodations seamlessly, and view real-time property locations via the **Mapbox API**.  

It supports fast login options through **Google OAuth** and **GitHub OAuth**, features a dynamic and responsive server, and offers an intuitive, aesthetically pleasing UI for an engaging user experience.

---

## ✨ Features Overview

### Front-end 🌐
**Technologies:** HTML, CSS, JavaScript, Bootstrap, EJS  
**Framework:** React.js  

- 📱 **Responsive Design**: Optimized for all devices  
- 🔍 **User-friendly Interface**: Easy property search and listing  
- 🗺️ **Mapbox API Integration**: Location-based search & property mapping  

### Back-end 🛠️
**Technologies:** Node.js, Express.js  

- 🧩 **RESTful API** for user interactions  
- 🔒 **Authentication & Authorization** using Passport.js & JWT  
- 📄 Endpoints for property listing, login/sign-up, and user management  
- 🏷️ **Seamless Booking System** for easy reservations  

### Database 🗄️
**DBMS:** MongoDB Atlas  

- 🗂️ Structured schema for efficient data management  
- 🔍 Fast queries for retrieving and storing property & user data  

### Cloudinary Image Storage ☁️
- Securely stores all listing images  
- Optimized for fast load times and better performance  

### Additional Features 🌟
- 🔍 Advanced Search & Filter  
- ⭐ User Reviews & Ratings  
- 🔐 Data encryption & validation  
- 📊 Client/Server-side validations  
- 🎨 EJS Templates for dynamic views  
- 🍪 Cookies & Sessions for authentication & notifications  
- 🏗️ MVC Architecture for scalability  
- 💾 Multer for file uploads  

---

## 🛠️ Technologies & Packages Used
- **MongoDB**, **Express.js**, **Node.js**  
- **Passport.js** for Authentication  
- **Cloudinary** for Image Storage  
- **Connect Flash**, **Connect Mongo** for sessions & messages  
- **Cookie Parser** for parsing cookies  
- **Dotenv** for environment variables  
- **EJS** for templating  
- **Express Session** for session handling  
- **Joi** for validation  
- **Mongoose** for MongoDB object modeling  
- **Multer** for file uploads  
- **Passport Local** & **Passport Local Mongoose** for authentication  

---

## 🚀 Deployment
The project is deployed using **Render** and connected to **MongoDB Atlas** for database management.  

**Live Application:** *[WanderLust Project](https://wanderlust-gnhu.onrender.com/)*

---

## 📥 Installation Guide

Follow these steps to run WanderLust locally:

### Prerequisites
- Node.js (**v18 recommended**)  
- MongoDB  
- Nodemon (**installed globally**)  

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Kris143k/wanderlust
   
2. Set up Environment Variables
Create a .env file in the root directory and add:
```
env
Copy
Edit
ATLASDB_URL=mongodb://127.0.0.1:27017/wanderlust
CLOUD_NAME=your_cloud_name
CLOUD_API_KEY=your_api_key
CLOUD_API_SECRET=your_api_secret
SECRET=your_cloudinary_secret
```

3. Install Dependencies
```
bash
npm install
```

4. Run the Application
```
bash
nodemon app.js
```

5. Access the App
```
Open http://localhost:8080 in your browser.
```

✍️ Author
@kris143k

🛫 Happy Traveling!
