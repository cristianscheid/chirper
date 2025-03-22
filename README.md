# Chirper

## Description

Chirper is a microblogging platform built with Laravel, React, and Tailwind CSS, leveraging Inertia.js to deliver a seamless single-page application experience. Users can create, view, edit, and delete posts securely, with full authentication. The platform also features notifications for new Chirps, enhancing user interactivity. Developed as part of the Laravel Bootcamp, this project showcases the effective integration of modern web technologies in a real-world application.

### Features

- Authentication with secure login and user management.
- CRUD operations for creating, viewing, editing, and deleting posts.
- Email notifications for new Chirps.
- Responsive design optimized for both desktop and mobile devices.

## Built With

![PHP][php-badge]
![Laravel][laravel-badge]
![MySQL][mysql-badge]

![JavaScript][javascript-badge]
![React][react-badge]
![Inertia][inertia-badge]
![Tailwind CSS][tailwindcss-badge]

## Visuals

![desktop 1](.github/desktop_1.png)
![desktop 2](.github/desktop_2.png)

## Installation

To get started with this project, follow the steps below:

1.  **Clone the repository**

    ```
    git clone https://github.com/cristianscheid/chirper.git
    cd chirper
    ```

2.  **Set up backend environment**

    - Install dependencies:

      ```
      composer install
      ```

    - Set up environment variables:

      ```
      cp .env.example .env
      ```

      > Open the `.env` file and configure your database and other settings (you can keep the default settings to use SQLite for simplicity).

    - Generate application key:

      ```
      php artisan key:generate --ansi
      ```

    - Run database migrations:

      ```
      php artisan migrate
      ```

3.  **Set up frontend environment**

    - Install dependencies:

      ```
      npm install
      ```

4.  **Start the servers**

    - Backend:

      ```
      php artisan serve
      ```

    - Frontend:
      ```
      npm run dev
      ```

## Usage

Once the application is running, you can access it at `http://localhost:8000`.

<!-- Badges for 'Built With' section -->

[php-badge]: https://img.shields.io/badge/PHP-8.3-gray?style=for-the-badge&logo=php&logoColor=white
[laravel-badge]: https://img.shields.io/badge/Laravel-11.18-gray?style=for-the-badge&logo=laravel&logoColor=white
[mysql-badge]: https://img.shields.io/badge/MySQL-8.0-gray?style=for-the-badge&logo=mysql&logoColor=white
[javascript-badge]: https://img.shields.io/badge/JavaScript-ES6-gray?style=for-the-badge&logo=javascript&logoColor=white
[react-badge]: https://img.shields.io/badge/React-18.2-gray?style=for-the-badge&logo=react&logoColor=white
[inertia-badge]: https://img.shields.io/badge/Inertia.js-1.0-gray?style=for-the-badge&logo=inertia&logoColor=white
[tailwindcss-badge]: https://img.shields.io/badge/TailwindCSS-3.2-gray?style=for-the-badge&logo=tailwindcss&logoColor=white
