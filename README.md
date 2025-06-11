# 🚌 MERN Bus Ticket Booking App

A full-stack Bus Ticket Booking application built with the **MERN Stack** – MongoDB, Express.js, React.js, and Node.js.

---

## ✨ Features

### 🔐 Authentication
- Sign Up / Sign In system
- Token-based authentication using **Passport.js**
- Passwords are securely hashed
- Only logged-in users can access the app

### 👤 User Dashboard
- Profile page displaying user info
- Booking history (optional future feature)

### 🚏 Bus Search & Booking
- Select source and destination cities
- View buses from different companies with details
- Choose seats with an interactive seat selection page
- Dynamically generated passenger form
- Confirmation screen with card input (UI only)
- Final ticket page shows passenger details and a unique transaction ID

---

## 🛠 Backend Overview
- Built with **Express.js**
- Uses **MongoDB Atlas** for storing user and booking data
- **Passport.js** for authentication and password hashing
- *Note:* Seat data is not dynamically stored in this version

---

## 📁 Project Structure Highlights
- Modular **React** folder layout
- Clean backend structure with routes, models, controllers, and config

---

## 🧰 Tech Stack & Tools

| Tech             | Purpose                                     |
|------------------|---------------------------------------------|
| VS Code          | Code Editor                                 |
| Node.js          | JavaScript runtime                          |
| React.js         | Frontend framework                          |
| Express.js       | Backend framework                           |
| MongoDB Atlas    | Cloud-hosted database                       |
| Passport.js      | Authentication middleware                   |
| Axios            | API requests                                |
| Babel            | JavaScript compiler                         |
| Webpack          | Module bundler                              |
| SCSS             | Styling preprocessor                        |
| Bootstrap 4      | UI styling and responsiveness               |
| react-credit-cards | Card input component (no real payments)   |

---

## 🚧 Limitations / Future Work
- No real payment processing (UI-only card form)
- Seat availability not stored dynamically in DB
- No admin panel or booking history yet
