<h1 align="center">LaravelTemplate</h1>

<p align="center">A Laravel project scaffolded with Jetstream, providing user authentication and team management features.</p>

<p align="center">
  <a href="#technologies-used">Technologies Used</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#license">License</a> •
  <a href="#contributing">Contributing</a>
</p>

## Technologies Used

-   Laravel
-   Jetstream
-   PHP
-   HTML
-   CSS
-   JavaScript

## Getting Started

To run this project on your local machine, follow these steps:

### Prerequisites

-   PHP (7.4 or higher)
-   Composer
-   Node.js (12 or higher)
-   npm

### Installation

1. Clone the repository:

git clone <repository-url>

Replace `<repository-url>` with the URL of your GitHub repository.

2. Navigate into the project directory:

cd LaravelTemplate

3. Install PHP dependencies:

composer install

4. Install JavaScript dependencies:

npm install

5. Build frontend assets:

npm run dev

6. Set up the environment variables:

-   Copy the `.env.example` file and rename it to `.env`.
-   Generate an application key:

    ```
    php artisan key:generate
    ```

-   Configure your database connection in the `.env` file.

7. Run database migrations:

php artisan migrate

8. Start the development server:

php artisan serve

The application should now be accessible at `http://localhost:8000`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request.
