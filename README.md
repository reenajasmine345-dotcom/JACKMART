Sports Zone – Problem Statement

Title Sports Zone – Online Sports Shopping Marketplace
Domain E-Commerce / Online Sports Shopping
Who is the User?
Customer Register and login. Browse sports products. Search and filter products. Add products to cart. Place orders and view order history.
Admin Manage products and categories. Manage users. Manage customer orders.
Seller Add and manage sports products. Update product details and availability. View orders related to their products.
What Problem Are We Solving? Customers often need to visit multiple sports shops or websites to purchase sports equipment, clothing, footwear, and accessories. This makes shopping time-consuming and makes it difficult to compare products, prices, and availability in one place. For example, a customer looking for a cricket bat, football shoes, and a badminton racket may need to search different stores. Sports Zone provides a single platform where customers can easily find, compare, and purchase different sports products.
Proposed Solution The Sports Zone application will provide: User registration and login. Role-based access for Customer, Admin, and Seller. Sports product listing. Product categories. Product search and filtering. Product details. Add to cart. Update or remove cart items. Place orders. View order history. Admin product management. Admin category management. Admin user management. Admin order management. Seller product management. Seller product availability management.
Core Entities / Database Tables Users Roles Products Categories Sellers Cart Cart_Items Orders Order_Items
User Roles & Permissions Customer Register and login. View sports products. Search and filter products. Add products to cart. Place orders. View order history. Admin Login to admin panel. Add, update, and delete products. Manage categories. Manage users. View and manage orders. Seller Login to seller account. Add products. Update product details. Manage product availability. View orders related to their products.
Success Criteria A user should be able to register and login successfully. A user should be able to find products using search or categories. A user should be able to add or remove products from the cart. A user should be able to place an order successfully. Admin should be able to manage products, categories, users, and orders. Seller should be able to manage their products and availability. The application should provide a simple and user-friendly shopping experience.
Out of Scope The following features will not be included in the initial version: Real-time delivery tracking. International shipping. AI-based product recommendations. Voice-based shopping. Multiple payment gateway integrations. Live customer support. Mobile application. Real-time seller-to-customer chat.
Chosen Track Java (Spring Boot) Technologies Frontend: HTML, CSS, JavaScript Backend: Java Spring Boot Database: MySQL API: REST API IDE: Visual Studio Code Version Control: Git & GitHub
