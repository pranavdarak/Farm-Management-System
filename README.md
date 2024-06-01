# 🌾 Farm Product System

This is a web application designed to connect farmers with consumers. Farmers can add their products to the platform, and users can browse and purchase these products by sending an email to the respective farmer. The system is built using Flask for the backend, with HTML, CSS, and JavaScript for the frontend. It uses XAMPP as the server for MySQL database integration.

## 🌟 Features

- **Farmers**: 
  - 📝 Register and log in to their accounts.
  - ➕ Add, update, and delete products.
  - 📋 View a list of all their products.

- **Users**:
  - 🛒 Browse available farm products.
  - 🔍 View detailed information about each product.
  - 📧 Contact farmers directly via email to purchase products.

## 🚀 Installation

### Prerequisites

- ![Python](https://img.shields.io/badge/Python-3.x-blue)
- ![XAMPP](https://img.shields.io/badge/XAMPP-orange)
- ![Flask](https://img.shields.io/badge/Flask-1.1.2-blue)
- ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1.3.20-blue)

### Steps

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/farm-product-system.git
   cd farm-product-system
   ```
2. **Set up the database**:
   - Install [XAMPP](https://www.apachefriends.org/index.html).
   - Start the Apache and MySQL modules from the XAMPP control panel.
   - Create a new MySQL database.
   - Update the database configuration in `config.py` with your database details.

3. **Run the Flask application**:
   ```sh
   flask run
   ```
   The application will be available at `http://127.0.0.1:5000`.

## ⚙️ Configuration

Make sure to update the `config.py` file with your database configuration:

```python
import os

class Config:
    SQLALCHEMY_DATABASE_URI = 'mysql+pymysql://username:password@localhost/database_name'
    SQLALCHEMY_TRACK_MODIFICATIONS = False
    SECRET_KEY = os.urandom(24)
```

## 🖥️ Tech Stack

![Flask](https://img.shields.io/badge/Flask-1.1.2-blue) 
![HTML](https://img.shields.io/badge/HTML-5-orange) 
![CSS](https://img.shields.io/badge/CSS-3-blue) 
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)
![XAMPP](https://img.shields.io/badge/XAMPP-orange)

## 📚 Usage

1. **Farmer Registration and Login**:
   - Navigate to the registration page to create a new farmer account.
   - Log in to access the farmer dashboard where you can manage your products.

2. **Adding Products**:
   - After logging in, use the dashboard to add new products by providing details such as name, price, description, and image.

3. **Browsing and Purchasing Products**:
   - Users can browse the products listed on the homepage.
   - To purchase a product, click on the product to view details and find the contact email to send a purchase request.

## 📬 Contact

For any questions or inquiries, please contact [darakpranav9@gmail.com].
