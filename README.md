# laravel-ckeditor5-vue-debug
repo to help resolve https://github.com/ckeditor/ckeditor5-vue/issues/23

1. Clone/download
2. Run `composer install` & `npm install`
3. Copy `.env.example` -> `.env` and run `php artisan key:generate`
4. Run `php artisan serve` to startup a local webserver @ http://127.0.0.1:8000
5. Run `npm run dev` to run mix
6. Enjoy the errors


#### Relevant files

- `webpack.config.js`
- `webpack.mix.js`
- `resources/js/app.js`
- `resources/js/components/ckeditor-custom.vue`
- `resources/views/welcome.blade.php`