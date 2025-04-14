# medical-supplychain-kits
This is the website where you can find a supply chain managment in the medical tablets distribution.

User can find the path from where the tablet is getting manufactured and who is distributing and also who is suppliying  The main objective of this project is to provide an accurate path of tablet journey and You will 
be able to search for products by name You will be able to search for products by Product Id also or else By Scanning also you can find all details.

## Getting Started
These instructions will make you to run this project on your local PC's for development and testing purposes.

1. Clone or download the repository from GitHub: []()

#### Technologies Used

Front-end  - HTML, CSS, Script
Backend    - Python (Flask)
Database   - Ganache
Technology - Block-chain

### Prerequisites
1. You need to have Ganache installed on your computer, which can be downloaded here  [Ganache](https://www.trufflesuite.com/ganache).

2. And you have to install libraries  that are required by the application, which include: Python:3.7+ and 
libraries are :   
         You need to install it first by running pip install 
        
3. Installation  
   - Python (version >=3.6)  
     Download it [here](https://www.python.org/downloads/)  
   
   - pip (Python package installer):  
     This comes with python installation  

     Now install Libraries  using command prompt(CMD)/Terminal : pip install (file name).

     from flask import Flask,render_template,redirect,request,session,send_file
        from web3 import Web3,HTTPProvider
        import json
        import qrcode
        from io import BytesIO
        - `Web3`: This module allows us to interact with Ethereum blockchains.  
     
#### Running the program 
1. Now open Ganache and create a new workspace, ( Remember the password of that account because it is needed when connect with Meta) now give  a name for workshop and add project by selecting truffle-config.js.

2. To run the program locally follow these steps:

     Open Command Prompt / Terminal.

     Navigate to the directory containing the cloned files.
     Run the following commands:Now open cmd and make sure you  are in the correct directory by using the following commands. 
     Now run command in cmd as : truffle migrate (contract is created in the ganache in that the data will be stored).
     Now run command in same cmd as : truffle compile

3. Open Python file and name it as as you  wish let say "app.py" then run following commands : app.py

     Note : If there are any errors please check if all dependencies installed correctly and also check whether Ganache is installed properly or not

4. In browser type http://127.0.0.5001  which shows your localhost server home page.

Now you are ready to use our application.

Note: If you face any error please check if all libraries have been installed properly.

# Usage of Application

# User Usage

## Home Page 

This is the main page where the user can scan the product 's QR code or search for products directly.

### About us Page 
In About us page you can find the answer Why we created this platform and also you can see the developers info also.

# What manufacturer can do?
    Manufacturer can add  their own product on the platform by generating the unique QR code of that product, in the QR different type of details can be integrated i.e, Product Id, Product Name, Manufacturer information, Unique Id, Cost etc.....

    Manufacturers can create their own products, set up an account on the platform, generate a unique QR code for each product and uploads in the QR.

Now he adds the distributor with some specfic details.

1. Add Distributors Details: The manufacturer can add the distributor's information such as Name, Address, Contact Number...

    For every  new Distributor, Manufacture has to register himself on platform first with Address which is presented in the Ganache Platform.

After registration , He will get his own unique ID (Manufacturers_ID), Address with a unique password.

Now the Manufacturer can send the product to specfic  Distributors, who needs that product.


# What Distributor Can do?
Distibutor will adds the Supplier with Address and some appropriate details he can sends the product to specfic Supplier.

# What Supplier can do?
Supplier will distributes goods to retailer. Retailer sells these goods to end users.

Supplier also can also distributes goods to Hospitals etc...........


This is our Application.

If any queries regarding this application feel free to ask.

Contact details - Name       : Karthik
                  Gmail      : karthikgudavalli7@gmail.com
                  Linkedin : [https://www.linkedin.com/in/karthikgudavalli].
