This project is using Laravel v9.52.20 with Laravel Breeze as athentication package.

How to install Laravel Breeze:
1. php artisan breeze:install
   Then choose blade.
2. php artisan migrate
3. npm install
4. npm run dev

   If you face problem like "vite manifest not found at:", you can try to reinstall the node_modules:
1. rm -rf node_modules
2. npm install
3. npm run build

    Dont forget to add this in your package.json:
   
"scripts": {
    "dev": "vite",
    "build": "vite build"
}

"devDependencies": {
  "laravel-vite-plugin": "^1.0.0",
  "vite": "^5.0.0"



  Reference:
  https://laravel.com/docs/9.x/starter-kits
  https://sentry.io/answers/how-do-i-fix-the-laravel-error-vite-manifest-not-found/
  https://laraveldaily.com/post/laravel-vite-manifest-not-found-at-manifest-json
