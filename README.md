RUN 
composer install

fill in your Pusher app credentials in your `.env` file:

PUSHER_APP_ID=xxxxxx
PUSHER_APP_KEY=xxxxxxxxxxxxxxxxxxxx
PUSHER_APP_SECRET=xxxxxxxxxxxxxxxxxxxx
PUSHER_APP_CLUSTER=

Change the DB in .env file

Create migrations:
php artisan migrate

run the server
php artisan serve


//Manually import the sql file attached.
Username: admin@admin.com
password: 1234567890