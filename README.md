<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## Laravel 11 CURD with Image

## Install Laravel
- Install laravel project

## Database Configuration
- set DB config

## Database Configuration
- php artisan make:migration create_products_table --create=products
we are going to create crud application for product. so we have to create migration for "products" table using Laravel 11 php artisan command

- run migration command : php artisan migrate

## Add Controller and Model
we should create a new controller named ProductController. In this controller, we write logic to store images. We store images in the "images" folder of the public folder.
- php artisan make:controller ProductController --resource --model=Product

## Add Resource Route
- we need to add a resource route for the product CRUD application. So, open your "routes/web.php" file

## Add Blade Files
- layout, index, show, create, edit

# laravel_curd_image
