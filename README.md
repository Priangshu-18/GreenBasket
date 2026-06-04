# GreenBasket

A full-featured grocery e-commerce platform with product catalogue, cart, order management, and an admin analytics dashboard.

Built during internship at **Success Innovation Technologies**.

---

## Features

- Product catalogue with category filtering and inventory tracking
- Cart and checkout with order placement
- Order history and status management
- Admin dashboard with stock analytics and sales reporting
- Relational MySQL schema: products, users, cart, orders, inventory
- Complex SQL joins for admin reporting and order history queries

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | PHP |
| Database | MySQL (via XAMPP) |

## Setup

**Prerequisites:** [XAMPP](https://www.apachefriends.org/index.html)

1. Clone or download this repository
2. Copy the project folder into `C:/xampp/htdocs/`
3. Unzip the `css`, `images`, and `js` folders in place
4. Open **phpMyAdmin**, create a database named `shop_db`, and import the provided `.sql` file
5. Start Apache and MySQL from the XAMPP Control Panel
6. Navigate to `http://localhost/GreenBasket/Login.php`
