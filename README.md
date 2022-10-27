<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Installation

1. Clone Repository
```bash
git clone https://github.com/mrazinshaikh/lara_vue_inertia.git
```

2. Goto project directory

```bash
cd lara_vue_inertia
```

3. Install php dependencies

```bash
composer install
```

4. Set Up env

```bash
cp .env.example .env
```
- SET `DB_PASSWORD`  <small>(MySql login password.)</small>
- To set `APP_KEY` RUN `php artisan  key:generate`
- PS: Also set `DB_USERNAME` if other then `root`


5. Install Js dependencies

```bash
npm install
```

6. Create database with name `lara_vue_inertia`. <small>(`DB_DATABASE` in .env)</small> 

7. Run Migration
```bash
php artisan migrate
```

8. Start laravel server
```bash
php artisan serve
```

- Note: default port 8000. if need to run on deferent port use --port=<PORT> option
- Ex:  `php artisan serve --port=8005`

9. Start npm server
```bash
npm run dev
```

10. Visit laravel serve [127.0.0.1:8000](http://127.0.0.1:8000)


<h1 align="center" style="text-align:center;margin-top:3rem;border-top:1px solid rgba(202, 203, 204,0.3);padding:1rem 0;">:smiley: :smiley: Happy Coding :smiley: :smiley:</h1>
