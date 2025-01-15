# IS-Shopping-app
Group project for IS 320 class @ UW Foster

Shopping App
Overview
This is a Python-based shopping application where customers can browse products, make orders, and view their order history. Managers can also monitor orders, update product prices, and manage inventory. The application allows customers to place orders, specifying the product and quantity, while handling product selection, price calculation, and order tracking. Managers have additional capabilities to edit product details and manage inventory levels.

Features
For Customers:
Login/Logout: Customers can log in using a customer ID and password.
Product Ordering: Customers can view available products and submit orders by selecting the product and specifying the quantity.
View Orders: Customers can view their past orders.
For Managers:
Login/Logout: Managers can log in using their manager ID and password.
View All Orders: Managers can view all orders placed by customers.
Price Editing: Managers can update product prices.
Inventory Management: Managers can reorder products and adjust stock levels.
Business Benefits
This system provides a centralized platform for customers to easily place orders while offering managers the flexibility to manage products, prices, and stock. With this system, businesses can streamline order management, improve inventory control, and maintain real-time insights into customer demand. This tool is ideal for businesses looking to scale their operations and provide a smooth shopping experience.

Benefits to Customers:
Convenient Ordering: Customers can quickly browse products, place orders, and view their order history.
Real-Time Updates: Instant updates on orders and product availability help customers stay informed.
Benefits to Managers:
Product Management: Managers can adjust pricing and stock levels to optimize sales.
Order Monitoring: Managers have an overview of customer orders to manage fulfillment and ensure smooth operations.
Inventory Control: Reordering functionality ensures the business maintains stock levels aligned with customer demand.
Technical Architecture
The application is built using Python and includes key components such as:

Customer & Manager Management: Handled via dictionaries with login credentials for security and identification.
Product Catalog: Managed using dictionaries for easy retrieval and updates to product information such as price and stock.
Order Management: Orders are tracked in dictionaries, linking product details and customer information to create an organized record of transactions.
Random Date Generation: Order dates are randomly generated within a specified range, offering realistic timestamps for orders.
Data Representation
Customers & Managers: Stored in dictionaries with the structure {user_id: {'login': ..., 'password': ...}}.
Products: Stored in dictionaries, with each product having attributes like ID, name, price, and stock.
Orders: Stored in dictionaries with unique order IDs, containing details like customer ID, product ID, order date, and price.
Future Enhancements
While the current version includes essential features like order placement, price editing, and inventory management, future updates will add:

User Registration: Allow new customers to create accounts.
Advanced Reporting: Offer sales insights and order analytics to help managers make data-driven decisions.
Improved UI/UX: Explore graphical user interfaces (GUIs) or web applications to enhance the customer experience.

--------------------------
Insights & Lessons Learned
Technical Insights:
Python Fundamentals: I strengthened my understanding of Python basics, including data structures like dictionaries, loops, and functions. This helped me manage user data, orders, and products effectively in the app.
Object-Oriented Design: Through this project, I became more comfortable using classes and methods to model real-world entities like customers, orders, and managers.
Data Management: I gained hands-on experience in managing and retrieving data from dictionaries, ensuring a seamless and scalable way to handle customer orders, inventory, and pricing updates.
Random Data Generation: I learned how to simulate realistic data by generating random order dates within specified ranges, which added an element of realism and testing variety to the app.
Business Insights:
Customer-Centric Development: Through the customer features of the app (e.g., order tracking, product browsing), I realized how important it is to focus on creating a smooth user experience that aligns with the needs of end users.
Inventory Management & Pricing: Working on features that allowed managers to adjust inventory and product prices highlighted the balance between user experience and back-end flexibility for managing products efficiently.
Business Scalability: I learned how tools like this can scale with a business by supporting both customer-facing functions and back-end management. This experience gave me a deeper understanding of how technology can enhance business operations, from inventory control to real-time data tracking.
Personal Growth:
Problem-Solving: This project helped me refine my problem-solving skills, as I needed to break down complex business requirements into manageable tasks and implement them step-by-step.
Cross-Disciplinary Thinking: Working on both technical and business aspects of this project taught me how important it is to approach problem-solving from a multi-faceted perspective, combining technical expertise with a business mindset to build a tool that meets the needs of both users and managers.
Project Management: Managing both development and testing phases gave me a better sense of how to structure work, plan milestones, and ensure that the product is moving forward efficiently.
