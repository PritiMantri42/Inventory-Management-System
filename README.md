# Inventory-Management-System
IMS is Python Project for managing and maintaining Products and generating Sales using JSON and dictionary.

## Brief Description
This project helps us for managing an Inventory. The main purpose of inventory management is to help businesses easily and efficiently manage the ordering, stocking, storing and using an inventory.In this a Dictionary is created in which records of Products are stored.For maintaining these records JSON is used.For these Importing JSON is necessary. JSON is a standardized format commonly used to transfer data as text that can be sent over a network.In order to transfer records to JSON file i.e. conversion from dict to str format is done using dumps(). <br/>
          In this Project Seller can add new products to inventory and maintain a record of Products. For Purchasing Products an updated records are displayed and by entering details about the product Bill is generated and customer can buy products.And after generating bill the quantities in the record.json file are updated.So that whenever Shops open next day the seller will have this updated json file. Along with this, Whenever a Customer buys a product that transaction is saved to Sales.json file. So that record of transaction is maintained.


## About Files
This Project mainly Consist of five files:
#### 1.Record.json: 
This file contains the records of Products like product_id,prod_name,category,expiry_date,Product_price and Available_quantites.The data is stored in this file in the Str format.Whenever Seller wants to perform modification in this file they need to open in write mode and load data to dict for this loads() is used.
#### 2.Adding_New_Products.ipynb : 
In this file Seller can add new products to inventory.For this the input is taken from seller about details of product like Seller have to give prod_id,prod_name,category,Expiry date,Price and Available quantities.For these Seller have two options:
   i) If Seller enters the prod_id which is already present in record then the number of quantities entered to add #####add_quantities will be added to Available_quantities of already present prod_id.
   ii) If Sellers enters new prod_id the details of product is taken from seller and added to inventory.
   After adding records then this record is saved in record.json file.
   
#### 3.Purchaing_Products.ipynb :
This files is used to purchase product from record. In this file we upload the updated json file generated after adding new records.Then user need to enter the prod_id, name and number of quantities of Products they want to buy and Billing Amount is generated.With this whenever a customer buys a product, this number of quantities are removed from Available_quantities.And updated record is saved using record.json file.

#### 4.Sales.json :
Whenever a customer buys product that tranasaction which contains details like prod_id,quantities and Total Amount generated is saved to sales.json file. So that record of transaction is maintained.
#### 5.README.md :
It will guide you, how do my project work.

## How to use
* Download this project in local system.

* Upload Inventory Management System.ipynb file in Google colab

 * Run all cell by type " Ctrl + F9" from keyboard


## Features
 * easy to use
 * Seller can add new products in an inventory by entering new product details.
 * If Seller enters the prod_id which is already present in record then the number of quantities entered to add i.e. add_quantities will be added to Available_quantities of      already present prod_id.
 * Sellers can view only the names of products or any attribute they wish to.
 * While Purchasing, users have given various choices to enter product details.
 * While Purchasing, whenever a customer buys a product, this number of quantities are removed from Available_quantities.
 * After transaction this details are saved directly to Sales.json file
 * Various instructions are given to user while buying products
 

### Product Features:
Produts have attribute like Product ID, Name of the product,Category to which this product belongs,Expiry date,Price and number of available quantities.

### Transaction Features
Transaction have attributes like prod_id,quantities and Total Amount generated. This will help in maintaing record.

## About Me : 
I am Priti Mantri , a Third Year Student. I am highly interested in Programming Languages Python & Java. I am also interested on working on various database Softwares.

## Links :
 Github : https://github.com/PritiMantri42/Inventory-Management-System <br/>
 Linkedin : https://www.linkedin.com/in/priti-mantri-87233521a <br/>
 Instagram : https://www.instagram.com/pritimantri42/ <br/>
 Facebook : https://www.facebook.com/priti.mantri.79
 
 
 Thank You! 


 

