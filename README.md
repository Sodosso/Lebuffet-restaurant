Author: Karim Dosso

Instructor: Poul Nichols

Course: IT125 Summer 2026

Project: LeBuffet Restaurant Database

# LeBuffet Restaurant Database Project

LeBuffet Restaurant is a restaurant management database designed for a future international buffet restaurant concept. The database supports customer management, menu organization, employee administration, vendor relationships, inventory tracking, orders, payments, reservations, and business reporting.

The restaurant concept combines multiple cuisines including Jamaican, Soul Food, American, Chinese, Mexican, Mediterranean, West African, and Italian dishes. Menu items are organized by cuisine, category, and style to support a diverse buffet experience featuring seafood, premium meats, rice dishes, pasta, wraps, sandwiches, and chef specialties.

The database uses primary keys, foreign keys, and normalized relationships to maintain data integrity while reducing redundancy. One of the primary design challenges was creating realistic relationships between menu items, ingredients, employees, customers, and transactions while maintaining scalability for future growth.

This project was created for IT125 and serves as both an academic database design project and a foundation for the future LeBuffet restaurant business concept.

Author: Karim Dosso

# Database Design Explanation

The LeBuffet Restaurant Database was designed using normalization principles to reduce data redundancy and improve data integrity.

First Normal Form (1NF) was achieved by ensuring each table contains atomic values and a unique primary key.

Second Normal Form (2NF) was achieved by separating related data into individual tables such as Customers, Orders, Employees, Menu_Items, Vendors, and Payments. This prevents partial dependencies on composite keys.

Third Normal Form (3NF) was achieved by removing transitive dependencies and storing related information in separate entities linked through foreign keys. For example, cuisine information, dish styles, vendors, and menu categories are stored independently and referenced where needed.

Primary keys and foreign keys were implemented throughout the database to enforce referential integrity and support relationships between customers, orders, payments, employees, menu items, ingredients, and suppliers.

The design supports future growth of LeBuffet as a multi-cuisine buffet restaurant offering Jamaican, Soul Food, American, Chinese, Mexican, Mediterranean, West African, and Italian-inspired dishes.
