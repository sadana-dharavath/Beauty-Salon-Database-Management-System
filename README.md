# Beauty-Salon-Database-Management-System

# Beauty Salon Database Management System

This project is a relational database management system (RDBMS) designed for a multi-branch beauty salon chain. It supports a wide range of functionalities including service management, product sales, customer memberships, discount tracking, and appointment scheduling.

## Objective
To build a scalable and well-structured database system that streamlines salon operations, supports data-driven decision-making, and enhances customer experience across all franchise locations.

## Application Users
- **Customers** – Can register, book services, buy products, and avail discounts and memberships.
- **Staff** – Provide services and manage their schedules.
- **Administrators** – Oversee staff, services, inventory, billing, and performance across all branches.

## Key Features
- Manage salon services with pricing, duration, and category details
- Maintain product inventory and record customer purchases
- Support memberships with tiered benefits
- Apply seasonal and membership-based discounts
- Handle appointments with staff availability and service mapping
- Track ratings, reviews, and customer service history
- Manage multiple franchise branches with individual performance metrics

## Database Design
- **Normalization:** Fully normalized schema up to BCNF

## Sample Queries
- Customers with past activity who haven't visited in 30+ days : "Find customers with at least one appointment, whose last visit was over 30 days ago — re-engagement opportunity."
- What are the quietest hours to offer flash sales? : "Find least busy hours to run limited-time deals and improve slot utilization."
- Is there a mismatch between supply, usage, and sales?
- What hours are the busiest for appointments?
- What is this customer's visit history? : "Show full appointment history for a specific customer — useful for personalized recommendations or conflict resolution."

## Technologies Used
- PostgreSQL (DDL, DML, Aggregation, Joins, Subqueries)
- ER Diagram & Relational Schema Design
- SQL-based data analytics

## Future Scope
- Integration with a web-based or mobile booking system
- Real-time notifications and customer service tracking
- Role-based authentication and access control
