<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://i.pinimg.com/originals/e7/c2/48/e7c24837bbe110000aec290a0b7f76eb.gif" width="400" alt="Laravel Logo"></a></p>

## Laravel Starter Project

A clean, minimal Laravel application ready for development. This project includes the essential setup to begin building your next web application with Laravel.

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## 🚀 Getting Started
Follow these steps to set up the project locally.

**Prerequisites**
- PHP 8.2 or higher
- Composer
- A database (MySQL, PostgreSQL, SQLite, etc.)

**Installation**
1. Clone the repository:
   
    ```
    git clone https://github.com/melissapixel/FusionPoint.git
    cd your-repo-name
    ```
2. Install PHP dependencies:
    
    ```
    composer install
    ```

3. Copy the example environment file and configure it:

    ```
    cp .env.example .env
    ```

    Then edit .env to set your database credentials and other settings.

4. Generate the application key:
    ```
    php artisan key:generate
    ```

5. Run migrations (if any):
    ```
    php artisan migrate
    ```

6. Start the local development server:
    ```
    php artisan serve
    ```

7. Visit `http://127.0.0.1:8000` in your browser.

## 📁 Project Structure
This project follows the standard Laravel directory structure. Key directories include:

- `app/` – Application logic (models, controllers, etc.)
- `routes/` – Web and API routes
- `resources/views/` – Blade templates
- `database/migrations/` – Database schema definitions
- `public/` – Publicly accessible assets and entry point

## 🛠️ Development Tools
- **Laravel Mix / Vite** – For asset compilation (CSS/JS)
- **Artisan CLI** – For generating code, running migrations, and more
- **Blade** – Laravel’s templating engine

## 🧪 Testing
To run tests (if configured):
```
php artisan test
```
