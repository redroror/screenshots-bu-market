
# BU-Market 

BU-Market is a web-based platform that centralizes merchandise being sold by accredited/re-accredited organizations in Bicol University. 
## Features

System Administrator
- Access admin's panel
- View and manage users
- Ban a buyer
- View feedbacks
- View recently created accounts


Organization/Seller
- Access seller's panel
- Upload product
- Modify product details
- View product reports
- Manage orders (Approve and Cancel)
- Add and modify payment methods (GCash and POP)
- Chat with users
- Manage profile
- Send feedback to System Administrator
- Add and remove moderators

Registered Buyer
- Browse products
- Browse Organizations\Sellers
- Add-to-Cart
- Place order
- Checkout product via POP (Payment-on-Pickup) and GCash
- Cancel, Return, and Refund an Order
- Rate product
- Chat with sellers
- Manage profile 
- Send feedback to System Administrator

Guest 
- Register as buyer
- Register as seller (must provide proof of accreditation)
- Browse products
- Browse organizations
- Send feedback

## Requirements
- PHP 8.0.0+
- VSCode or any preferred IDE
- XAMPP 
- Download the file or source code 
## Installation

1. Download the file/system first. 

2. Navigate to the root directory and install dependencies:
```bash
 composer install
```


    
## Usage
1. Find the .env file and configure environment variable
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```
2. Open XAMPP and start Apache and MySQL
3. Start the server
```
php artisan serve
```
4. Visit http://127.0.0.1:8000/
5. By following the link provided, you will be redirected to the landing page. To access the admin panel, use the login credentials below:
- Email: admin@gmail.com
- Password: 12345678

If you're interested in using our platform as a registered user, you can create an account by clicking the 'Register' on the navigation bar. Or use the login credentials provided below: 
- Email: testone@gmail.com
- Password: 12345678

6. To access the seller's panel, you may use the login credentials below: 
- Email: buss@gmail.com
- Password: password

## Screenshots
![App Screenshot](https://github.com/redroror/screenshots-bu-market/blob/0bc9f48b82971e4912e3e3991bd4100fe02375fb/Landing%20Page.png)
![App Screenshot](https://github.com/redroror/screenshots-bu-market/blob/main/Profile.png)
![App Screenshot](https://github.com/redroror/screenshots-bu-market/blob/main/Products.png)
![App Screenshot](https://github.com/redroror/screenshots-bu-market/blob/main/PRoduct%20View.png)
![App Screenshot](https://github.com/redroror/screenshots-bu-market/blob/main/Cart.png)
![App Screenshot](https://github.com/redroror/screenshots-bu-market/blob/main/Checkout%20Page.png)
![App Screenshot](https://github.com/redroror/screenshots-bu-market/blob/main/Order%20Page.png)

