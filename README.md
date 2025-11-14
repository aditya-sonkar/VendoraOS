VendoraOS is a modern SaaS Point of Sale (POS) system that simplifies billing, inventory management, customer tracking, and analytics for stores, supermarkets, and retail chains.
It features multi-store support via a Super Admin panel and integrates secure payment gateways.

Features

Real-time billing and invoicing

Inventory & stock management with low-stock alerts

Customer order history and tracking

Sales analytics and reports

Multi-store management through Super Admin

JWT-based authentication and role-based access control

Technology Stack

Backend: Java Spring Boot, Spring Security

Frontend: React / Angular (optional)

Database: MySQL

Authentication: JWT

Payment: Razorpay / Stripe (optional)

Build Tools: Maven

Getting Started
Backend

Update application.properties with your MySQL credentials.

Run the backend server:

cd backend
mvn spring-boot:run

Frontend (Optional)
cd frontend
npm install       # or yarn install / pnpm install
npm start         # or yarn start / pnpm start
