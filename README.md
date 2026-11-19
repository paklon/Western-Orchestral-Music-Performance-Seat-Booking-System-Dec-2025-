# 🎻 Western Orchestral Music Performance Seat Booking System

A full-stack, responsive web application designed for orchestral event management, interactive seat selection, secure user authentication, and administrative transaction monitoring. Developed as a comprehensive coursework project for **EIE4432 Web Systems and Technologies**.

---

## 🚀 Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap, **SVG** (Interactive Seat Mapping)
* **Backend:** Node.js, Express.js, Express-Session, Multer (File Uploads), Bcrypt (Password Hashing)
* **Database:** MongoDB, Mongoose ODM (NoSQL)
* **Utilities:** JsBarcode (Electronic Ticket Barcode Generation)

---

## 🌟 Key Features

### 👤 User Features
* **Secure Authentication & Session Management:** User registration, password encryption via `bcrypt`, login with role-based access control (User vs. Admin), and an optional *"Remember my User ID"* cookie feature.
* **Event Dashboard & Search:** Real-time event search autocomplete, dynamic filtering (by title, venue, date), and live ticket sales / seat availability tracking.
* **Interactive Seat Selection:** Dynamic venue floor plans utilizing **SVG** to visually render seat tiers (Economy vs. Premium) and real-time seat status (`available`, `booked`, `disabled`).
* **Simulated Checkout & Ticketing:** Secure payment processing page with input validation, leading to instant electronic ticket generation featuring unique barcodes (`JsBarcode`).
* **User Profile & History:** Profile management with avatar image uploads (`multer`), complete transaction/booking history logs, and access to active digital tickets.

### 🛠️ Admin Features (`Admin Only`)
* **Event Management:** Create, update, and manage upcoming orchestral performances and cover images.
* **Seat & Pricing Management:** Configure venue dimensions (rows/columns), toggle seat tier classifications, and dynamically adjust pricing for Economy and Premium sections.
* **User & Transaction Oversight:** Comprehensive platform user directory and system-wide transaction ledger tracking all customer purchases.

---

## 📱 Mobile Responsiveness
Optimized for multi-platform usage with adaptive layouts and collapsible navigation menus (tested across desktop and mobile viewports like iPhone SE).

---

## ⚙️ Installation & Quick Start

### 1. Prerequisites
* Install Node.js
* Access to a MongoDB instance (Local MongoDB or MongoDB Atlas)

### 2. Clone the Repository
git clone [https://github.com/your-username/your-repo-name.git]
cd your-repo-name

### 3. Install Server Dependencies
npm install

### 4. Configure MongoDB Connection
* Edit MongoDB URL in .env

### 5.Create the database
* Ensure MongoDB is running
* The required database and collections are automatically created when the app runs and data is added

### 6. Run the Project
npm start or node server.js

### 7. Access the Web App
* Open your browser and go to: http://localhost:8080

---

### 👤 Author
* Yuen Pak Hei — BSc in Information Security, The Hong Kong Polytechnic University 
