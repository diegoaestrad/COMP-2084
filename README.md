# COMP-2084
Server Side scripting GC

Students: -Geidy Ducuara Ruiz
          -Diego Estrada Beltran

Product Manager

a. The purpose of choosing the topic is to create a platform that allows different kind of users to manage products, for example, add products to the stock of a store, sell products to a specific customer, create orders based on multiple products, those products can be used in an Order tab.

b. The project contemplate Polymorphism and Abstraction because all objects are treated as independent objects with the functionalities that the process involves like, addProducts, this method can be used to add a new product into the products table or into the orders table to add a new one to the order, both have a different aim.


Tables Structure:

Table_Users<br />
-Id_User<br />
-User_Login<br />
-User_FirstName<br />
-User_LastName<br />
-User_Role<br />
-User_Password<br />

Table_Product<br />
-Id_Product<br />
-Product_Name<br />
-Product_Code<br />
-Product_Price<br />
-Product_Stock<br />


Table_Orders<br />
-Id_Order<br />
-Id_User<br />
-Id_Product<br />
-Product_Quantity<br />
