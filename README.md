
# E-Commerce Marketplace

A lightweight e-commerce platform that allows users to browse, search, and purchase products from various sellers. The platform supports multiple payment methods, real-time order tracking, and a simple product review system.

---

## Table of Contents
1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Testing](#testing)
6. [Contributing](#contributing)
7. [License](#license)
8. [Authors and Acknowledgments](#authors-and-acknowledgments)
9. [Contact Information](#contact-information)

---

## 1. Description
The **E-Commerce Marketplace** is designed to connect buyers and sellers on a single platform. Sellers can create product listings, while buyers can explore categories, add items to their cart, and checkout securely.

### Key Features:
- User registration and login system
- Product catalog with search and filter functionality
- Shopping cart and order management
- Single payment gateways
- User reviews and ratings for products
- Seller dashboard for managing products and orders
- User notification
- Item transaction and payment history

---

## 2. Installation

### Prerequisites:
- HTML
- CSS
- JavaScript
- PHP
- MySQL
- XAMPP

### Steps:
1. Place your project in the web server directory. For XAMPP the directory is `C:\xampp\htdocs\`.

2. Create a new folder inside the `htdocs` or `www` folder for your project and put your PHP files in it.

3. Clone the repository:
    ```bash
    git clone https://github.com/username/e-commerce-marketplace.git

4. Start the XAMPP Web-Server. You can use the control panel to start/stop services like Apache and MySQL.

5. Open your web browser and enter `http://localhost/<your_project_folder_name>/` in the address bar. For example, if your project folder is named `e-commerce-marketplace`, the URL would be:
    ```bash
    http://localhost/e-commerce-marketplace/

6. If your project requires a MySQL database, open phpMyAdmin by navigating to `http://localhost/phpmyadmin/` in your browser.

7. Create a new database if needed.

8. Use the database connection details (host: `localhost`, `user: root`, `password:`, `database name`) in your project.

## 3. Usage
Once the application is running, you can access the platform via `http://localhost:8080`.

### Example User Actions:
* **Browse Products**: Visit the homepage to explore available products.
* **Search Products**: Use the search bar to find specific items.
* **Purchase a Product**: Add items to the cart and complete the checkout process.
* **Leave a Review**: After purchase, leave a review for the product.

### Admin Access:
* Use the admin dashboard at `http://localhost:8080/admin` to manage products and orders.

## 4. Configuration
You can configure the following environment variables for the project in the `database.php`:
    ```bash
    $db['default'] = array(
	'dsn'	=> '',
	'hostname' => 'localhost',
	'username' => 'root',
	'password' => '',
	'database' => 'onlineshop',
	'dbdriver' => 'mysqli',
	'dbprefix' => '',
	'pconnect' => FALSE,
	'db_debug' => TRUE,
	'cache_on' => FALSE,
	'cachedir' => '',
	'char_set' => 'utf8',
	'dbcollat' => 'utf8_general_ci',
	'swap_pre' => '',
	'encrypt' => FALSE,
	'compress' => FALSE,
	'stricton' => FALSE,
	'failover' => array(),
	'save_queries' => TRUE
    );
    ```
## 5. Contributing:
Contributions are welcome! Please follow the steps below:

* Fork the repository.
* Create a new branch (git checkout -b feature/your-feature-name).
* Commit your changes (git commit -m 'Add some feature').
* Push to the branch (git push origin feature/your-feature-name).
* Open a pull request.
* For detailed guidelines, check the `contributing.md` file.

## 6. License
This project is free to use and to contribute.

## 7. Contact Information
For questions or support, please contact:

* **Email**: `jessiegabriellaslh@gmail.com`
* **LinkedIn**: `https://www.linkedin.com/in/jessiegabriella/`