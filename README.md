# Laravel + Nuxt Project

This is a Laravel + Nuxt project that is a sample blog creating project.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [PHP](https://www.php.net/) (version 8.1.20)
- [Composer](https://getcomposer.org/)
- [Node.js](https://nodejs.org/) (version 16.20.0)
- [npm](https://www.npmjs.com/)

### Installing

1. Clone the repository:

    ```bash
    git clone https://github.com/nandar-oo/Blog-Laravel-Nuxt.git
    ```

2. Navigate to the project directory for laravel api:

    ```bash
    cd Blog-Laravel-Nuxt/server
    ```

3. Install PHP dependencies:

    ```bash
    composer install
    ```

4. Install JavaScript dependencies:

    ```bash
    npm install
    ```

5. Copy `.env.example` to `.env` and configure your database settings.

6. Generate the application key:

    ```bash
    php artisan key:generate
    ```

7. Run migrations:

    ```bash
    php artisan migrate
    ```

8. Start the development server:

    ```bash
    php artisan serve
    ```
9. Navigate to the nuxt project directory:

    ```bash
    cd Blog-Laravel-Nuxt/client
    ```

10. Install dependencies:

    ```bash
    npm install
    ```

11. Start the development server:

    ```bash
    npm run dev
    ```

