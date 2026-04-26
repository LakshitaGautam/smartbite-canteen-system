# smartbite-canteen-system
college canteen pre-order and billing system with normalized MySQL database and Python Flask backend

 Project Overview

Managing canteen queues and manual billing in college environments is 
inefficient and error-prone. SmartBite solves this with a structured 
database-driven pre-order platform where students can place orders in 
advance and billing is automated server-side.


| MySQL | Relational database management |
| PL/SQL | Stored procedures, triggers, DCL |
| Python Flask | REST API and server-side logic |
| HTML/CSS | Frontend structure and styling |
| Bootstrap 5 | Responsive UI components |
Key Features

- Normalized relational database schema (3NF) designed for a 
  canteen pre-ordering platform
- DDL, DML, and DCL operations implemented with complex multi-table joins
- Stored procedures and triggers for automated order and billing logic
- RESTful backend built with Python Flask for server-side processing
- Indexing strategies applied to optimize SQL query retrieval time
- Responsive Bootstrap 5 frontend integrated with Flask templates

 Database Design

- Tables: Students, Menu, Orders, OrderItems, Billing, Staff
- Constraints: Primary keys, foreign keys, NOT NULL, UNIQUE
- Stored Procedures: Place order, generate bill, update inventory
- Triggers: Auto-update stock on order placement

 How to Run

1. Clone the repository
   git clone https://github.com/LakshitaGautam/smartbite-canteen-system.git

2. Set up the database
   - Open MySQL Workbench
   - Run the schema.sql file to create tables and procedures

3. Install dependencies
   pip install flask mysql-connector-python

4. Run the app
   python app.py

5. Open in browser
   http://localhost:5000

---

## 👩‍💻 Developer

Lakshita Gautam
Jaypee Institute of Information Technology, Noida
B.Tech CSE | 2023–2028
