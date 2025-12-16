

## 🔹 2. ENV Setup (Local First)

### Task 2: Understand `.env`

Open `.env` and update:

```env
APP_NAME="Laravel Arch"
APP_ENV=local
APP_DEBUG=true
APP_URL=http://localhost

DB_DATABASE=laravel_arch
DB_USERNAME=root
DB_PASSWORD=
```

Create DB:

```sql
CREATE DATABASE laravel_arch;
```

Run:

```bash
php artisan migrate
```

### 🔑 Concept: ENV vs CONFIG

* `.env` → environment-specific (never commit)
* `config/*.php` → application behavior



Run app:

```bash
php artisan serve
```
