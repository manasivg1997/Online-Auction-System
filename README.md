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

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/6e06d47a-9928-4337-b95d-a182e175fcdf)

User login -> Verifies the username and password from the database and validates the user
login.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/c17b5c8b-236e-4aae-a864-2954f6cb4938)

Display products -> Retrieves the entries from join of Products and Categories table based on
the category given. Selects all products where All category is chosen.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/4aede528-4ab4-4ce6-8602-861021b209f6)

Bid on product -> Inserts the records to Bids table.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/19f89b04-6c18-4ce6-b48c-9cb5c1f83183)

Bid not placed as amount less than current highest bid

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/e5e7a9cc-0561-43ba-a559-1f45207e19d6)

Bid placed

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/dd6d6e1d-b1d4-409b-b50a-775943bfe369)

User Interface Screenshots for Seller:

Add products for bid -> Inserts the product details to Products table and stores the images on to the web server image location.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/d476a2f6-29f4-4785-84e8-f3927c04896b)

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/a159d5f8-fcbf-48e2-8692-5818551dcb7a)

View highest bid on product -> Retrieves the data using the query mentioned in Additional
queries section.

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/51899f1c-2c74-416e-bbdd-c795f65ff1c1)

View buyer details -> Gets the data from BUYER table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/90326a8b-8833-49a0-8cbd-d35abcad5a22)

User Interface Screenshots for Administrator:

Add category -> Inserts data to Categories table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/276b53f9-8b4f-4456-bca4-d4f5fb92c3f1)

Filter products -> Filters the products based on the product name from Products table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/6f2369a2-4b76-4a59-9bed-48d5f2473c2a)

Edit user information -> Updates the info in USER table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/8bfa2976-8317-44be-8d35-1a901f99aedc)

View all users -> Retrieves all the records present in USER table

![image](https://github.com/manasivg1997/Online-Auction-System/assets/24837305/2fd04079-dcc6-4458-bf1e-fee390d95f46)

