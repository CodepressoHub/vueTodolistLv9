# Codebase Overview

## Backend

- `app/Models/Item.php` – Eloquent model representing a todo item.
- `app/Http/Controllers/ItemController.php` – REST controller that lists, creates and updates items.
- `database/migrations/2022_08_01_025754_create_items_table.php` – migration defining the `items` table with `title` and `done` columns.
- `routes/api.php` – registers API routes under `/api` for CRUD operations on items.

## Frontend

- `resources/js/app.js` – entry point for the Vue/Vite frontend scaffold.

## Tests

- `tests/Feature/ExampleTest.php` – sample feature test ensuring the welcome page is accessible.
