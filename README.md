<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About
A starter kit of Laravel 8 with the Vuejs Authentication that was available in previous versions.
I created this to help users to follow some technical articles I've written on:
1. [Dev.to](https://dev.to/mupati)
2. [Medium](https://mupati.medium.com)

## Setup
1. Clone or  download the repository<br/>
   ```
   git clone git@github.com:Mupati/laravel-8-vue-auth-starter.git
   ```

2. Create your `.env` file.
   ```
   cd laravel-8-vue-auth-starter
   cp .env.example .env
   ```
3. Update the `.env` file with your database various credentials
4. Install the necessary packages.
   ```
   composer install && npm install
   ```
5. Generate the app key
   ```
   php artisan key:generate
   ```
6. Run the migrations
   ```
   php artisan migrate
   ```

7. Start frontend server
   ```
   npm run watch
   ```
8. Start the backend development server
   ```
   php artisan serve
   ```
9.  Visit the url printed out on the terminal in your browser. Most likely it will be http://127.0.0.1:8000.


Continue your journey of building the NEXT BIG THING.