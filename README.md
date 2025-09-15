🚀 FoodHub – Food Delivery Web Application 🍔🍕🍜

FoodHub is a Full Stack Java Web Application built as part of my training at Tap Academy. It’s a complete food delivery solution that brings together frontend, backend, and database development in one project.

💻 Tech Stack & Tools

Frontend: HTML, CSS, JSP

Backend: Java Servlets, JDBC, Java EE

Database: MySQL

Architecture & Patterns: MVC Architecture, DAO Design Pattern

IDE & Tools: Eclipse IDE, MySQL Workbench, Apache Tomcat Server

🧩 Features

1️⃣ User Account Management – Signup & login system with authentication and validation, 2️⃣ Restaurant Listings – Dynamic display of restaurants fetched from the database, 3️⃣ Dynamic Menus 🍽 – Menus auto-update based on selected restaurant, 4️⃣ Cart System 🛒 – Add, remove, and update item quantities (with same-restaurant restriction), 5️⃣ Order Placement 📦 – Delivery address and payment integration before confirmation, 6️⃣ Login Redirection 🔐 – Redirect non-logged-in users to login before ordering, 7️⃣ Reorder Function 🔄 – Place repeat orders from order history, 8️⃣ Order History & Tracking 📜 – View past orders with time and date, 9️⃣ Admin Functionalities ⚙ – Manage restaurants, menus, and orders from the backend, 🔟 Responsive UI 📱 – Optimized for desktop and mobile, 📂 Project Structure Project/ │── src/ # Source code │ ├── Dao/ # DAO interfaces │ ├── DaoImp/ # DAO implementations │ ├── Pojo/ # Model/Entity classes │ ├── DBConnection/ # Database connection utility │ ├── launch/ # Servlet classes │── WebContent/ # JSPs, CSS, JS, images │── build/ # Compiled .class files │── .settings/, .classpath # IDE configs

⚙️ Setup Instructions

Clone the repository

git clone https://github.com/Ayesha1417/foodzy.git- cd foodhub

Import into Eclipse IDE as a Dynamic Web Project

Deploy on Apache Tomcat

Access the app at:

http://localhost:8080/Project/login.jsp

📸 Screenshots Login image
<img width="1918" height="968" alt="1" src="https://github.com/user-attachments/assets/81dcb934-99ab-4dca-9899-2b1ed9c2082f" />

Restaurant image
<img width="1918" height="967" alt="2" src="https://github.com/user-attachments/assets/34d26088-fdc8-4bad-b897-b4c5fd45fd41" />

Menu image
<img width="1918" height="972" alt="3" src="https://github.com/user-attachments/assets/6390e350-f676-404d-9ef6-441fd4288eca" />

Cart image
<img width="1918" height="970" alt="4" src="https://github.com/user-attachments/assets/8d6dc947-ce0d-4251-8b4e-db0bfe272f44" />

Order tracking image
<img width="1918" height="972" alt="5" src="https://github.com/user-attachments/assets/a7048f54-6ade-4659-b784-d1a6787c44c2" />


✨ Key Takeaways

Applied Java EE, JSP, and Servlets in a real-world project

Implemented MVC architecture for scalability

Worked with JDBC & MySQL for database operations

Designed user-friendly UI/UX for better customer experience

Managed session tracking, validations, and database integrity

💡 Challenges Overcome

Restricting cart items to a single restaurant

Implementing login redirection before order placement

Optimizing SQL queries for performance

Designing reusable DAO methods
