This is an Inventory Management System.

This Management System has two users Employee and Customers whose features asre as mentioned below:
1. Employee
    1. See inventory
    2. Add new items
    3. See the sales of the day
2. Customer
    1. See inventory
    2. Purchase items and see bill
    
#### Making Initial Inventory and Sales Using JSON.ipynb
This Jupyter file is used to make the initial inventory and sales JSON record files. (**records.json and sales.json**)

#### Inventory Management System.ipynb
This Jupyter file contains the code for the Management Sytem.
It follows the following steps:
1. Asks what kind of user you are.
2. If you're an Employee, you can:
   1. See inventory (items that are available that day)
   2. Add new items (add new inventory)
   3. See the sales of the day (check items sold)
3. If you're an Customer, you can:
   1. See inventory (available items that you can buy)
   2. Purchase items and see bill (expired and out of stock items will be called out and not sold, discounts on items will be applied, total amount to be paid will be shown at the end)
   
