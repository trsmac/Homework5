## Part 1
CREATE an ER diagram for a Collectible Store, Your ER diagram may be hand drawn,** You need to submit in PDF format**. Please follow this below diagram style to make your ER diagram(**PLEASE ALSO SPECIFY multiplicities**):

![image-7](https://github.com/uniquefeelings/Homework5/assets/156957954/9b1e6522-ba76-4fee-840c-9dda259beec7)

This store will have various types of items such as baseball cards, old video game systems, antique lamps, etc …  The store owner wants to be able to track information about customers who make purchases from him.  He may wish to contact the customers. The owner also needs to be able to keep track of his inventory.  The owner will need to know what items have sold, and which ones are still available.  The owner should be able to create an invoice which has information about the items sold in a purchase, and which customer the items were sold to.

The owner of the store also needs a list of suppliers.  These are people who have brought in items and sold them to the store.  Therefore, each item should be mapped to the person who sold it to the shop owner.  Contact information should be stored for the suppliers as well.

The database should store information about employees as well.  Checks that are issued to employees should be tracked in the database.  Additionally, there should be a way to track payments from customers.  There should be a relationship between the payment, the invoice, and the customer.  (One possible attribute is “payment type” – credit, check, or cash, and of course, the amount).

Start by creating a list of Entities you want to track with the database.  These will become your entity sets.  Then decide how these entity sets will be related.

- Be detailed!
- You MUST specify **multiplicities** -> **many-many**, **many-one**, **one-one**
- Be sure to specify **keys**
- You must be able to list the quantity and the price of an item as a function of the item, and the customer who made the purchase.
- Don’t use weak entity sets
Recall that each Entity Set must have a key.

## Part 2
Convert your ER diagram into a set of Tables (Relations)
Every year on this type of assignment groups lose points because they don’t convert their relationships into tables.  Be sure to do this!  If you are unsure, please ask me and I will clarify it for you.

You do not need to show what data is stored in each table.  Just give a list of tables (name of table and a list of column names).  It may be helpful to think about what data will go into each table, but I am not looking for this information as part of the assignment.

 

- Deliverable: PDF
