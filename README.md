# google-calendar
A PHP library to easily connect to Google Calendar
## requirements
Set up a project on Google, create a service account in the IAM & Admin Google Cloud Console, and create a key. Download the json config file and place it in 
your project.
## installation
```
composer require delboy1978uk/google-calendar
```
## setup
Somewhere in your project, define an environment variable
```php
putenv('GOOGLE_APPLICATION_CREDENTIALS=/path/to/service_account.json');
```
