# DELIVERY_APP - A Food Delivery Database Project

This project is a complete relational database schema for a food delivery application, built using MySQL. It handles all core functionalities, including managing customers, restaurants, drivers, orders, and menu items.

## Database Schema

The database is designed with six interconnected tables to ensure data integrity and efficiency.

-   **Customers**: Stores unique information for each user.
-   **Restaurants**: Contains a list of all partner restaurants and their ratings.
-   **Drivers**: Manages a roster of delivery personnel.
-   **MenuItems**: Lists all food items, each linked to a specific restaurant.
-   **Orders**: Records every transaction, linking customers, restaurants, and drivers.
-   **OrderDetails**: A junction table that connects `Orders` and `MenuItems`, allowing a single order to contain multiple food items.


## How to Use

To get this project running, simply execute the complete SQL script in a MySQL environment like MySQL Workbench. This will create the `DELIVERY_APP` database, build all the tables, and populate them with over 100 rows of sample data.

## Sample Queries

The database is designed to answer key business questions. Here are a few examples of what it can do:

-   **Find Top Customers:** Identifies high-value customers by calculating their total spending.
-   **Track Recent Orders:** Lists all orders placed after a specific date, along with the specific items in each order.
-   **View Customer History:** Fetches the complete order history for any specific user.
-   **Find the Most Popular Item:** Determines the best-selling menu item based on the total quantity sold.
-   **Manage Restaurant Quality:** Filters restaurants that have a rating below a certain threshold (e.g., 4.5).
