## 
  Retrieve data from multiple table at once
  - Inner join = intersection, selects rows from t1 and t2 where they match the selecting column
    SELECT * FROM Customers INNER JOIN Orders ON Customers.ID = Orders.Customer_ID

  - Left join, select all rows from the t1, and the rows from t2, if they match.
    SELECT * FROM Customers LEFT JOIN Orders ON Customers.ID = Orders.Customer_ID

  - Right join, select all rows from the t2, and the rows from t1, if they match.
    SELECT * FROM Customers RIGHT JOIN Orders ON Customers.ID = Orders.Customer_ID

  - Full join, select all rows from both tables.
    SELECT * FROM Customers FULL JOIN Orders ON Customers.ID = Orders.Customer_ID