Inventory Management System
Overview
The Inventory Management System (IMS) is a modern, web-based application designed to efficiently manage products, users, and transactions within an organization.It supports role-based access for Admin, Staff, and Customers, ensuring secure operations and real-time inventory tracking.
Features
•	Role-Based Access Control:Separate modules for Admin, Staff, and Customer with specific permissions.
•	Secure User Authentication:Login and registration system for all user roles.
•	Inventory Management:Add, update, delete, and view products with images, SKU, and descriptions.
•	Stock Tracking:Real-time stock quantity updates.
•	Order & Transaction Management:Track customer orders and transaction details.
•	CSV Export:Download product and transaction reports in CSV format.
•	Search & Filter:Easily search for products and transactions.
•	Responsive UI:Modern and user-friendly React frontend.
•	Backend Management:Java Spring Boot backend handling APIs and business logic.
•	Database Integration:MySQL database for storing products, users, and transaction data.
Tech Stack:
•	Frontend: React.js, HTML, CSS, JavaScript
•	Backend: Java, Spring Boot
•	Database: MySQL
•	Version Control: Git & GitHub
Project Structure:
Inventory-Management-System/
│
├── frontend/                     # React frontend
├── backend/                      # Java Spring Boot backend
├── customer/                     # Customer-related files
├── Agile_Template_v0.1.xlsx      # Agile documentation
├── Defect_Tracker_Template_v0.1.xlsx # Defect tracker
├── Inventory_Management_System.pptx  # Project presentation
├── Unit_Test_Plan_v0.1.xlsx      # Unit testing document
├── LICENSE                       # MIT License
└── README.md                     # Project documentation

How to Run the Project:
Backend (Spring Boot):
cd backend
mvn clean install
mvn spring-boot:run
Frontend (React):
cd frontend
npm install
npm start
Database (MySQL):
 Create a MySQL database
 Update database credentials in: backend/src/main/resources/application.properties
 Start the backend server
License:
This project is licensed under the MIT License.
See the LICENSE file for details.


Contact:
•	Developer: Venkattalakshmi S
•	GitHub: https://github.com/venkattalakshmi/Inventory-Management-System
•	Email: venkattalakshmivenky@gmail.com

