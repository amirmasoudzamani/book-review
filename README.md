# Book Review App

A simple book review application built with Laravel.

## Languages

- [English](#english)
- [فارسی](#فارسی)

---

# English

## About

Book Review App is a simple book review application built with Laravel.

This project was created to practice Laravel features such as Eloquent relationships, database queries, filtering, searching, Blade components, and handling user reviews.

Users can browse books, search through the available books, filter them based on popularity and ratings, and submit reviews with ratings.

## Features

- View book list
- Search books
- Filter books by popularity and rating
- View book details
- Add reviews for books
- Rate books
- Display average ratings
- View book reviews
- Reusable Blade components for star ratings
- Simple and clean interface
- No user authentication required

## Technologies

- Laravel
- PHP
- MySQL
- Blade
- Blade Components
- Tailwind CSS

## Installation

Follow these steps to run the project locally.

### Clone the repository

```bash
git clone https://github.com/username/book-review-app.git
```

### Install dependencies

```bash
composer install
```

### Create environment file

```bash
cp .env.example .env
```

### Generate application key

```bash
php artisan key:generate
```

### Configure database

Open the `.env` file and configure your database settings.

Then run migrations:

```bash
php artisan migrate
```

### Run the project

```bash
php artisan serve
```

The application will be available at:

```
http://127.0.0.1:8000
```

## License

This project is open-sourced under the MIT License.

---

# فارسی

## درباره پروژه

Book Review App یک برنامه ساده برای مشاهده و ثبت نقد و بررسی کتاب‌ها است که با استفاده از Laravel ساخته شده است.

هدف اصلی این پروژه تمرین قابلیت‌های Laravel مانند رابطه بین مدل‌ها، کار با دیتابیس، Query های مختلف، جستجو، فیلتر کردن، ساخت Blade Component ها و مدیریت Review ها بوده است.

در این پروژه کاربران می‌توانند لیست کتاب‌ها را مشاهده کنند، بین کتاب‌ها جستجو کنند، کتاب‌ها را بر اساس محبوبیت و امتیاز فیلتر کنند و برای کتاب‌ها نظر و امتیاز ثبت کنند.

## امکانات

- مشاهده لیست کتاب‌ها
- جستجو بین کتاب‌ها
- فیلتر کتاب‌ها بر اساس محبوبیت و امتیاز
- مشاهده جزئیات کتاب
- ثبت Review برای کتاب‌ها
- امتیازدهی به کتاب‌ها
- نمایش میانگین امتیاز کتاب‌ها
- مشاهده نظرات کاربران
- استفاده از Blade Component برای نمایش امتیازدهی ستاره‌ای
- رابط کاربری ساده و تمیز
- بدون نیاز به سیستم ثبت‌نام و ورود

## تکنولوژی‌ها

- Laravel
- PHP
- MySQL
- Blade
- Blade Components
- Tailwind CSS

## نصب و اجرا

برای اجرای پروژه به صورت محلی مراحل زیر را انجام دهید.

### کلون کردن پروژه

```bash
git clone https://github.com/username/book-review-app.git
```

### نصب وابستگی‌ها

```bash
composer install
```

### ساخت فایل تنظیمات محیط

```bash
cp .env.example .env
```

### ساخت کلید برنامه

```bash
php artisan key:generate
```

### تنظیم دیتابیس

فایل `.env` را باز کنید و اطلاعات دیتابیس را وارد کنید.

سپس migration ها را اجرا کنید:

```bash
php artisan migrate
```

### اجرای پروژه

```bash
php artisan serve
```

پروژه در آدرس زیر در دسترس خواهد بود:

```
http://127.0.0.1:8000
```

## لایسنس

این پروژه تحت لایسنس MIT منتشر شده است.