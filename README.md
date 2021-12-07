# How To Run

- Install MAMP (https://www.mamp.info/en/downloads/)
- Change the settings for mysql DB. Allow network access to mySQL
- Go to (http://localhost:8890/phpMyAdmin5/)
- Create a tables called "my_blog"
- git clone the repo into the MAMP folder
- cd to the clone folder and run "npm install && npm run dev"
- Now run "php artisan serve"

# How to populate data
- run " php artisan tinker "
- run " \App\Models\BlogPost::factory()->times(10)->create(); "
