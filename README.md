# COMP-2084
Server Side scripting GC

Students: -Geidy Ducuara Ruiz
          -Diego Estrada Beltran

Product Manager

a. The purpose of choosing the topic is to create a platform that allows different kind of users to manage products, for example, add products to the stock of a store, sell products to a specific customer, create orders based on multiple products, those products can be used in an Order tab.

b. The project contemplate Polymorphism and Abstraction because all objects are treated as independent objects with the functionalities that the process involves like, addProducts, this method can be used to add a new product into the products table or into the orders table to add a new one to the order, both have a different aim.


Tables Structure:

Table_Users
          Id_User
          User_Login
          User_FirstName
          User_LastName
          User_Role
          User_Password
Table_Product
          Id_Product
          Product_Name
          Product_Code
          Product_Price
          Product_Stock
Table_Orders
          Id_Order
          Order_User
          Order_Product
          Product_Quantity
