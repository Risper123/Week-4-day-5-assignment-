# Week-4-day-5-assignment-
 My assignment for week 4 day 5
Assignment Questions
✨ Write an SQL query to create an index named IdxTotalAmount on the TotalAmount column to enhance query performance for bills table.

CREATE INDEX IdxTotalAmount ON bills (TotalAmount);

🗑️ Write an SQL query to drop an index named IdxEmail from customer table.

DROP INDEX IdxEmail ON customer;

👤 Write an SQL query to create a user named bob with the password 'S$cu3r3!' , restricted to the localhost hostname.

CREATE USER 'bob'@'localhost' IDENTIFIED BY 'S$cu3r3!';

🔑 Write an SQL query to grant the INSERT privilege to the user bob on the bills database.

GRANT INSERT ON bills.* TO 'bob'@'localhost';



🔐 Write an SQL query to change the password for the user bob to 'P$55!23'

SET PASSWORD FOR 'bob'@'localhost' = PASSWORD('P$55!23');
