Parcel Delivery Management System

Overview

This project is a SQL-based Parcel Delivery Management System developed as part of the Introduction to Database course at the American International University-Bangladesh (AIUB), Faculty of Science & Technology, for the Fall 2022-2023 semester. The system is designed to streamline parcel delivery operations, ensuring timely and accurate delivery to customers while minimizing human effort and errors associated with traditional systems. The database is implemented using Oracle 10g.

The system manages key entities such as customers, orders, products, payments, delivery personnel, and hub stations, with a focus on data normalization, relational integrity, and efficient querying.

Features





Database Structure: Normalized tables (up to 3NF) to ensure data integrity and eliminate redundancy.



Entities and Relationships: Manages customers, orders, products, payments, delivery personnel, and hub stations with defined relationships (e.g., one-to-many, many-to-one).



SQL Implementation:





Table creation with primary and foreign key constraints.



Sequence generation for auto-incrementing IDs.



Data insertion for sample records.



Queries including single-row functions, group functions, subqueries, joins, views, and relational algebra expressions.



Schema Diagram: Visual representation of the database structure (included in the project documentation).



Error-Free Delivery: Focus on accurate and timely parcel delivery with electronic payment integration.

Project Structure

The project is documented in a 36-page PDF (Parcel Delivery Management System.pdf), which includes:





Title Page: Project and group details.



Table of Contents: Overview of sections.



Introduction: Purpose and objectives of the system.



Scenario Description: Detailed explanation of entities, attributes, and relationships.



Normalization Steps: Steps to achieve 1NF, 2NF, and 3NF for each entity.



Temporary and Final Tables: Intermediate and finalized table structures.



Schema Diagram: Entity-Relationship Diagram (ERD).



Table Creation: SQL scripts for creating tables with constraints.



Sequence: SQL sequences for generating unique IDs.



Data Insertion: Sample data for all tables.



Query Writing: Examples of SQL queries, including:





Single-row functions (e.g., ROUND, LOWER).



Group functions (e.g., SUM, MIN with HAVING).



Subqueries and joins.



Views for simplified data access.



Relational Algebra: Expressions for querying specific data.



Conclusion: Summary and future improvements.

Database Schema

The final database consists of the following tables:





Customer: Stores customer details (ID, name, email, phone numbers, address).



Address: Stores customer address details (apartment number, street, postal code, city).



Orders: Tracks order details (ID, date, customer ID, payment ID).



Product: Manages product details (ID, name, price, quantity, delivery date, order ID, customer ID, deliveryman ID).



Payment: Records payment details (ID, amount, date, customer ID).



HubAddress: Stores hub station address details.



HubStation: Tracks packages at hub stations (package ID, hub address, payment ID, deliveryman ID).



DeliveryMan: Stores delivery personnel details (ID, name, salary, phone numbers).

Installation and Setup





Prerequisites:





Oracle 10g or a compatible SQL database system.



SQL client (e.g., Oracle SQL Developer, Oracle Application Express).



Steps:





Clone the repository: git clone <repository-url>.



Execute the table creation scripts (CREATE TABLE statements) in the order specified in the documentation (pages 17-21).



Create sequences for auto-incrementing IDs (CREATE SEQUENCE statements, page 22).



Insert sample data using the provided INSERT statements (pages 23-29).



Run the sample queries to verify functionality (pages 29-34).

Usage





Use the SQL scripts to set up the database.



Execute queries to perform operations such as:





Retrieving customer names in lowercase.



Calculating the sum of delivery personnel salaries.



Finding products delivered on a specific date.



Creating views for simplified data access.



Refer to the relational algebra section for theoretical query representations.

Future Improvements

The project outlines potential enhancements:





Real-Time Vehicle Tracking: Integrate GPS data to monitor delivery progress and reduce delays.



Distributed Database: Transition from a centralized to a distributed system for scalability and stability.



Customer Updates: Provide real-time shipment and delivery status updates to customers.

Contributors





Noushin, Radia (ID: 22-46268-1)



Mosammat Tasnin Nafisa (ID: 21-45439-3)



Md Shariful Aman (ID: 21-45890-3)



Fardin Hossain Pulak (ID: 21-45891-3)

Course Teacher: Juena Ahmed Noshin
Section: B, Group: 01
Course: Introduction to Database, Fall 2022-2023

License

This project is for educational purposes and is not licensed for commercial use. All rights reserved by the contributors and AIUB
