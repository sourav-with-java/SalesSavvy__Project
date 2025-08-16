🛒 Sales Savvy - Your Smart E-commerce Platform
Welcome to Sales Savvy — My grand finale Java Full Stack project!
This is an e-commerce solution built using Spring Boot, React.js, and MySQL, designed to empower small and medium businesses with seamless online selling and user management.

🚀 Project Overview
Sales Savvy offers a scalable and secure platform for businesses to manage their online stores with ease.

✨ Features
🔐 Separate Login Systems

Admin and Customer logins with JWT-based authentication
Forgot Password? Send OTP via JavaMailSender to the registered email
🛠️ Admin Panel

Manage products, users, and orders
Assign roles, generate reports
🛍️ Customer Interface

Browse products by category, add to cart, and track orders
Make secure payments via Razorpay, PayPal, or Stripe
📦 Order & Product Management

Full CRUD operations for products and categories
Real-time order status tracking (Pending ➡ Approved ➡ Shipped ➡ Delivered)
💳 Secure Payments

Payment gateway integration with Razorpay, PayPal, or Stripe
💻 Tech Stack
🔧 Backend
Java, Spring Boot, Spring MVC, Spring Security
Hibernate, Spring Data JPA
JavaMailSender for OTP on Forgot Password
RESTful APIs
🎨 Frontend
React.js
CSS / Bootstrap
🛢 Database
MySQL
📦 DevOps
Docker & Docker Compose (for containerized deployment)
📸 Screenshots
Login Page Customer------>

Screenshot 2025-04-07 174510

Register Page Customer ------>

Screenshot 2025-04-07 174520

Forgot Password / Password Recovery----->

Screenshot 2025-04-07 175153

OTP sent to that register mail ------>

Screenshot 2025-04-07 175309

OTP enter for recovery page ---->

Screenshot 2025-04-07 175226

Set new password ----->

Screenshot 2025-04-07 175237

Customer Dashboard ----->

Screenshot 2025-04-07 174547

Add to cart and order summary ----->

Screenshot 2025-04-07 174605

RazorPay Integerated Pay Via different method ----->

Screenshot 2025-04-07 174623

Payment successfull and order submission ------>

Screenshot 2025-04-07 174753

Order history ------>

Screenshot 2025-04-07 174830

That specific user profile and logout ------>

Screenshot 2025-04-07 174906

Admin Login Page ------>
Screenshot 2025-04-07 174928

Admin Dashboard with all modal ----->

Screenshot 2025-04-07 175000

⚙️ Functional Modules
Module	Description
🧑‍💼 Admin Panel	Manage users, products, orders, and reports
👨‍💻 Customer Portal	Register, browse products, shop, track orders
🛒 Shopping Cart	Add, update, remove items with price totals
🔐 Security	JWT Authentication, HTTPS, encrypted data
📧 OTP on Forgot	Forgot password sends OTP via JavaMailSender
🚚 Getting Started
Clone the repository
Import backend into Spring Tool Suite / IntelliJ
Setup frontend in React and install dependencies
Create & import MySQL DB from database/database.sql
Configure application.properties for DB & email
Run backend & frontend
Test features
📌 Future Enhancements
Product reviews and ratings
Inventory tracking
Multi-language support
Admin dashboard with charts & analytics
🤝 Contributing
Pull requests are welcome! If you find bugs or want to add features, feel free to fork and contribute.

📃 License
This project is open-source under the MIT License.
