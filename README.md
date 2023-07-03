General structure

Description of the elements of the online store. Includes: product categories, products, customers, orders.

Product category description consists of: name and position in the category tree.

Product description consists of: title, short description, full description, image ID list, base price, current price, stock quantity, article, color list, size list, minimum quantity per order.

Description of the client consists of: name, phone, address, email.

The description of the order consists of: customer indication, order number, payment method, delivery method, list of goods, cost of goods at the time of the order, total cost of the order including delivery, date of order.

A product can only belong to one category. The order contains information about the size and color of the product

task2.sql
0. Select the total cost of all goods in the online store, taking into account their quantity.

1. Choose the average number of orders for all customers (ratio of total orders to total number of customers).

2. Select the smallest order and the largest order in terms of the number of goods in one request.

3. Delete all categories of products that do not have products of direct descendants in the tree or products of indirect descendants of the second level (previously add a cascade replacement to NULL in category links from categories).

4. Add yellow to all products containing the word "dress" in the name, if it is not there.

5. Add new customer information to the database: discount, with a default value of 0%.

6. Add an integrity constraint to prevent discounts greater than 75%.

task1.sql
0. The trigger does not allow adding directories more than the third level of nesting.

1. Write a function that returns the total cost of all orders that include this product for the specified article of the product.

2. Write an aggregate function that, for a set of product identifiers, calculates the number of products ordered at least once.

3. Create a view that displays product names, articles, and quantities in stock (and key fields in the products table). Implement the ability to change the number of products through this view in a real table.

4. Use a table and a set of procedures (or functions) to implement the One-way Queue data representation structure. The structure should allow strings to be stored in the queue, no more than 64 characters long. Actions enqueue - adding an element to the end of the queue, dequeue - removing an element from the head of the queue, empty - clearing the queue, init - initializing the queue, top - viewing the beginning of the queue, tail - viewing the end of the queue
