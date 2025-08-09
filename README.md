# Vue Todo List API

This repository contains a minimal Laravel 9 application paired with a Vue frontend scaffold. It exposes a small REST API for managing todo items.

## Features

- List all items via `GET /api/items`
- Show a single item via `GET /api/item/{id}`
- Create items with `POST /api/item/store`
- Update items with `PUT /api/item/{id}`
- Delete items with `DELETE /api/item/{id}`

Each item has a `title` and a `done` flag stored in the `items` database table.

## Getting Started

1. Install PHP dependencies:
   ```bash
   composer install
   ```
2. Copy the example environment file and configure your database connection:
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```
3. Run database migrations:
   ```bash
   php artisan migrate
   ```
4. Install and build frontend assets:
   ```bash
   npm install
   npm run dev
   ```
5. Start the development server:
   ```bash
   php artisan serve
   ```

## Testing

Run the application test suite with:

```bash
php artisan test
```

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

