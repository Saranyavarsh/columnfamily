cassandra
A Column family database is similar to a table in Relational Database Management System that stores data in rows and columns.

STEPS INVOLVLED IN CREATING COLUMN FAMILY DATABASE USING CASSANDRA

      1)Create a  keyspace in cassandra.
      2)Create column families to store data.
      3)Insert the data into the column families.
shop management system: Creation of a KEYSPACE called shop_management. The database includes three tables

     1)products
     2)customer
     3)orders
The products table stores information about products such as

     product_id
     product_name
     stock
     price
The orders table stores infofrmation about orders such as

     order_id
     customer_id
     order_date
     quantity
     product_id
     price
The customer table stores informatiom about customer such as

   customer_id
   customer_name
   customer_email
And the tables are modifided using insert,update and delete commands.        
