# Online-Auction-System

This software system will be an Online Auction System, to be used by sellers to advertise their
products and for potential buyer to submit their bids, with the highest bidder automatically being
selected as the buyer. This system will be designed to provide a platform for the sellers to find the
best price for their products. At the same time, it will provide a fair opportunity to all the potential
buyers to offer their best price and get a chance to buy the product. The system will meet the needs of
the buyers and sellers, while remaining easy to understand and use. Additionally, the system will also
provide privileges to the administrator to have complete control of the users and the content posted.

Implementation:

Frontend: HTML, CSS, JavaScript, AJAX

Backend: PHP

Database: MySQL


User Interface Screenshots for Buyer:

Creating an account -> All the details filled in the form are inserted to USER table and
BUYER/SELLER depending on the values selected when creating account.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/7b0929f5-a28c-4eda-92af-573c56bd99c3)


User login -> Verifies the username and password from the database and validates the user
login.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/5e9eb981-c1c4-4246-b117-8347e28ca9e9)


Display products -> Retrieves the entries from join of Products and Categories table based on
the category given. Selects all products where All category is chosen.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/bf23efdf-4d06-4224-9aba-21c6b28b161e)


Bid on product -> Inserts the records to Bids table.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/938ec596-e638-4a6b-bf61-6bc678386224)


Bid not placed as amount less than current highest bid

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/29f50797-1fba-450a-a1b4-a2eeafbbaab3)


Bid placed

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/388317ae-33d5-42da-8649-7d56e45a2652)


User Interface Screenshots for Seller:

Add products for bid -> Inserts the product details to Products table and stores the images on to the web server image location.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/6a236778-1cc7-4c6a-85ef-de50c6510295)


![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/566f3aff-6028-40e9-980d-ea807cff838d)


View highest bid on product -> Retrieves the data using the query mentioned in Additional
queries section.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/7c7d8100-b52b-4284-a0ac-f48845cd2644)


View buyer details -> Gets the data from BUYER table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/44d457e5-43d5-466a-a675-98faa0110856)


User Interface Screenshots for Administrator:

Add category -> Inserts data to Categories table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/89fbe471-4dc3-4cd3-b226-056333f71c7a)


Filter products -> Filters the products based on the product name from Products table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/3744d1e6-f175-4793-9b6d-e9b67428f09c)


Edit user information -> Updates the info in USER table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/a692c67e-09fd-46f3-9109-654200931f10)


View all users -> Retrieves all the records present in USER table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/c464c971-9f81-4646-8e01-bf558e55b0e2)


