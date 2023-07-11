# Chirper
 Laravel10 bloging app

#Using this app
 1- dwnload this app and make sure your developing enviroment are set with the following:
    * Nodejs
    * composer
 2- run ypur local server using ' php artisan serv' command
 3- run 'npm run dev' command in your app directory to compile Tailwind css classes
 4- navigate to 'http://127.0.0.1:8000/' on your browser and create an account to start using the app and make your first Chirp

 #Important 
  1- this app using SQLite as a Database instead of MySQL because its a small app
  2- you can check your databse entries using Tinker in terminal
      * Run 'php artisan tinker' in your app directory terminal to interact with the app directly with PHP
      * Run 'User::all();' command to get all useres you've registered 
  3- this app is using laravel log file to display notification for the user if the new Chirp is created
     You can replace it by editing the 'env' file and set 'MAIL_MAILER' variable value to Mailpit but make sure you've configured your Mailpit
     to recieve emails on it. visit this link for more information 'https://github.com/axllent/mailpit'

#If you are facing any problem with the code or the database migrations visit the Laravel 10 bootcamp for this app documentation 
 and make sure you are reading under 'Build Chirper with Blade' section
