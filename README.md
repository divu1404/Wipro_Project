# ShopForHome  
_Wipro Capstone Project_

## 🎯 Project Overview  
ShopForHome is a full-stack e-commerce application developed as the capstone project for Wipro. It enables users to browse home décor & furnishing products, manage shopping carts, place orders, and handles backend operations including product, user and order management.

## 🧩 Key Features  
- User registration/login with role-based access (customer/admin)  
- Product listing, search & category filters  
- Shopping cart & checkout flow  
- Order tracking and history  
- Admin dashboard for managing products, users and orders  
- Responsive front-end UI with modern technologies  
- Clean RESTful backend API

## 🛠️ Tech Stack  
- **Frontend:** TypeScript, HTML, CSS, JavaScript  
- **Backend:** Java (Spring Boot or equivalent)  
- **Database / ER Diagram:** MySQL (see `Ecart2.mwb`)  
- **Other:** REST APIs, Role-based authentication, MVC architecture

## 🚀 Getting Started (for Developers)  
### Prerequisites  
- Java JDK (version 11 or higher)  
- MySQL server setup  
- Node.js & npm (to build frontend if needed)  

### Setup Steps  
1. Clone the repo:  
   ```bash
   git clone https://github.com/yash0672/Wirpo_Capstone_Project.git
Configure database:

Create a MySQL database (e.g., shopforhome_db)

Update application settings (application.properties or .env) with DB credentials

Backend:

cd Wirpo_Capstone_Project/ShopForHome
./mvnw clean install
./mvnw spring-boot:run


Frontend:

cd Wirpo_Capstone_Project/FrontEnd
npm install
npm start


Open in browser:

http://localhost:4200   (or specified port)

📁 Project Structure
/Frontend/           → Front-end source code  
/ShopForHome/        → Back-end Java source code  
Ecart2.mwb           → MySQL database diagram  
README.md            → Project documentation  

✅ Usage

Register as a user or login as admin

Browse products, add to cart & proceed to checkout

Admin can add/edit/remove products, view orders & users

View order history and track status

🧪 Testing & Deployment

Use Postman (or similar) to test backend APIs

Run frontend dev server for UI testing

For production: build the frontend (npm run build), deploy backend and serve static files via web-server

📚 Documentation

Database ER diagram: Ecart2.mwb

API endpoints: List and descriptions can be found in /ShopForHome/src/main/resources/api-docs (or equivalent)

Frontend components & routing: Detailed in Frontend/src/app

👥 Contributors

Yash (Primary developer)

(Add names here if more contributors)

📄 License

This project is licensed under the MIT License (or whichever you prefer).
See LICENSE file for details.

📝 Contact

For queries or feedback, contact [yash@example.com
] (update with your email).
