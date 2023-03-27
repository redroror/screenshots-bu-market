
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
5. By following the link provided, you will be redirected to the landing page. To access the admin panel, use the login credintials below:
- Email: admin@gmail.com
- Password: 12345678

If you're interested in using our platform as a registered user, you can create an account by clicking the 'Register' on the navigation bar. 

6. To access the seller's panel, you must create an organization first by navigating to the admin's panel. 

![Admin Panel](https://github.com/redroror/screenshots-bu-market/blob/7e90ae8486360872196dbd3464e8e71e53b43032/Admin%20Panel.png)
## Screenshots



