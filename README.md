# MeroShop - Ecommerce Website using Laravel

MeroShop is an online shopping platform developed as part of our 6th-semester project. This project is a group effort and is designed to provide a user-friendly online shopping experience with features like product browsing, shopping cart, order management, and user authentication.

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)

## 🧑‍💻 Team Members

*   **Saugat Dhungana** - [GitHub](https://github.com/SaugatDh) - Project setup, backend development (Laravel), authentication setup.
*   **Anup Ghimire** -(https://github.com/anupghimire12),backend development (Laravel), shopping cart functionality,authentication setup..
*   **Anil Tajpuriya** -Frontend, Backend API development, order management.
*   **Nikesh Dhakal** - Admin dashboard, order management.
*   **Suman Basnet** - Final testing and deployment setup.

## ✨ Features

*   **User Registration & Authentication**: Users can create accounts and log in securely.
*   **Product Catalog**: Browse and search for products across different categories.
*   **Shopping Cart**: Add products to the cart and manage items before checkout.
*   **Order Management**: View past orders and track the status of current orders.
*   **Admin Dashboard**: Admin users can manage products, categories, and view customer orders.
*   **Secure Payments**: Integrated payment processing (e.g., Stripe).

## 🛠️ Tech Stack

*   **Backend**: Laravel (PHP Framework)
*   **Frontend**: Blade Templating, Tailwind CSS, JavaScript
*   **Build Tool**: Vite
*   **Database**: MySQL
*   **Authentication**: Laravel Breeze/Jetstream
*   **Payment Gateway**: Stripe (requires configuration)

## 🚀 Installation & Setup

To run this project locally, follow these steps:

### Prerequisites

Make sure you have the following installed on your machine:
*   PHP (v8.0 or higher)
*   Composer (for PHP dependency management)
*   Node.js (v14 or higher) & npm
*   MySQL (or another compatible database)

### Steps to Run

1.  **Clone the repository**
    ```bash
    git clone https://github.com/anupghimire12/MeroShop-Ecommerce-Laravel-.git
    cd MeroShop-Ecommerce-Laravel-
    ```

2.  **Install PHP dependencies**
    ```bash
    composer install
    ```

3.  **Setup Environment File**
    ```bash
    cp .env.example .env
    ```
    Edit the `.env` file with your database credentials and other settings (like Stripe keys).
    ```ini
    DB_DATABASE=your_database_name
    DB_USERNAME=your_mysql_username
    DB_PASSWORD=your_mysql_password
    ```

4.  **Generate application key**
    ```bash
    php artisan key:generate
    ```

5.  **Run database migrations**
    ```bash
    php artisan migrate
    ```

6.  **Install frontend dependencies and build assets**
    ```bash
    npm install
    npm run dev
    ```

7.  **Start the development server**
    ```bash
    php artisan serve
    ```

8.  **Visit the application**
    Open your browser and go to `http://localhost:8000`.

## 📖 Usage

*   **Customer Mode**: Browse products, add them to your cart, and place orders.
*   **Admin Mode**: Login as an admin to manage products, view and update orders.

## 🤝 Contribution

Feel free to fork the repository and submit a pull request for any improvements or bug fixes.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 🔑 Important Configuration Notes

*   **Stripe Payments**: To enable payments, you must add your Stripe API keys (`STRIPE_KEY` and `STRIPE_SECRET`) to your `.env` file.
*   **Database**: Ensure your MySQL server is running and the database specified in your `.env` file exists.

## 🙏 Credits

This project was inspired by various online tutorials and resources.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

**About**: This project was developed for educational purposes as a 6th-semester course project.