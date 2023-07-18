# Chirper

 Laravel10 blogging app


# Using this app

- download this app and make sure your developing environment is set with the following: Nodejs, composer
-  run your local server using the 'php artisan serv' command
- run the 'npm run dev command in your app directory to compile Tailwind CSS classes
-  navigate to 'http://127.0.0.1:8000/' on your browser and create an account to start using the app and make your first Chirp

## Important
- this app uses SQLite as a Database instead of MySQL because it is a small app
- you can check your data entries using Tinker in terminal
- Run 'php artisan tinker' in your app directory terminal to interact with the app directly with PHP
- Run the 'User::all();' command to get all users you've registered 

## Notifications and Mails
this app uses a Laravel log file to display notifications for the user if the new Chirp is created
     You can replace it by editing the 'env' file and setting the 'MAIL_MAILER' variable value to Mailpit but make sure you've configured your Mailpit
     to receive emails on it. Visit this link for more information 'https://github.com/axllent/mailpit'

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Any errors?
If you are facing any problem with the code or the database migrations, visit the Laravel 10 Bootcamp for this app documentation 
 and make sure you are reading under the 'Build Chirper with Blade' section
