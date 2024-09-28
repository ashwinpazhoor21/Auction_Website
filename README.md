# Auction Website (Ebay-inspired)

## Project Overview

This project is a web-based auction platform inspired by eBay, developed using Django. It allows users to browse, bid on, and list items for auction, with a focus on providing a seamless user experience for managing transactions and item listings.

## Project Structure

- **.vscode/**: Contains the configuration settings required to run the project in Visual Studio Code.
  
- **auctions/**: The main directory for the application, including:
  - **_pycache_/**: Stores session data and compiled Python files.
  - **migrations/**: Handles database migration files for seamless updates.
  - **static/auctions/**: Houses all CSS files to style the website.
  - **templates/auctions/**: Contains HTML templates that define the front-end of the site.
  - Additional Python files that implement Django's core functionality.

- **commerce/**: Another folder containing Django-related files and additional _pycache/_ for application caching.

- **db.sqlite3**: A SQLite database file that stores all site data, including users, bids, listings, and transaction history.

- **manage.py**: The main Python script that orchestrates the entire project, allowing developers to run the server, manage the database, and handle migrations.

## Objective

The objective of this project was to build a full-stack web application that replicates the core functionalities of popular auction websites like eBay. It offers features such as user registration, item listings, bidding, and transaction management, all while maintaining a clean and user-friendly interface.

## Lessons Learned

Throughout the development process, I gained valuable experience in Django, web development, and database management. I enhanced my understanding of front-end and back-end integration, improving my skills in HTML, CSS, and Python. Additionally, working with migrations and handling user sessions helped me grasp the intricacies of maintaining a web application's state across multiple users.