# Project Setup and Start Guide

This project uses **Laravel** as the framework and **SQLite** as the database.  
Follow the steps below to set up and run the project on your local machine.

---

## ✨

![Laravel](https://img.shields.io/badge/Laravel-11.x-red?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.3-777BB4?logo=php&logoColor=white)
![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey?logo=sqlite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🛠 Project Setup

### Step 1: Clone the Project

```bash
git clone https://github.com/your-username/project-name.git
cd project-name

```

### Step 2: Install Dependencies

```bash
composer install

composer update

composer dump-autoload

```

### Step 3: Set Up Environment Variables

```bash

cp .env.example .env

In .env file, set:

```

### Step 4: Generate Application Key

```bash

php artisan key:generate

```

### Step 5: Run Migrations

```bash

php artisan migrate

```

### Step 6: Start the Development Server

```bash
php artisan serve
```
Open your web browser and navigate to `http://localhost:8000` to access the project.

That's it! You should now have the project set up and running on your local machine.
