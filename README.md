<h2>This project is using Laravel v9.52.20 with Laravel Breeze as athentication package.</h2>

<h3>A. How to install Laravel Breeze:</h3>
1. composer require laravel/breeze --dev  <br/>
2. php artisan breeze:install <br/>
   Then choose blade.<br/>
3. php artisan migrate<br/>
4. npm install<br/>
5. npm run dev<br/>
<br/>

<h3>B. Dont forget to add this in your package.json:</h3>
   
"scripts": {<br/>
    "dev": "vite",<br/>
    "build": "vite build"<br/>
}<br/>
<br/>
"devDependencies": {<br/>
  "laravel-vite-plugin": "^1.0.0",<br/>
  "vite": "^5.0.0"<br/>
}<br/>

<h3>C. If you face problem like "vite manifest not found at:", you can try to reinstall the node_modules:</h3>
1. rm -rf node_modules<br/>
2. npm install<br/>
3. npm run build<br/>
<br/>



  Reference: <br/>
  https://laravel.com/docs/9.x/starter-kits <br/>
  https://sentry.io/answers/how-do-i-fix-the-laravel-error-vite-manifest-not-found/ <br/>
  https://laraveldaily.com/post/laravel-vite-manifest-not-found-at-manifest-json <br/>
