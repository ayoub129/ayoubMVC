# AyoubMvc Framwork

AyoubMvc Framwork created by [Ayoub Berouijil](https://github.com/ayoub129). Customized by me and used as base for integrating and testing new technologies.

## Getting Started

Copy the project in your folder and install the database dump in your PhpMyAdmin.
Follow the instructions to complete the installation.

### Prerequisites

* Apache Server
* PHP 5.6+
* Mysql Database


Install [XAMPP](https://www.apachefriends.org/it/index.html) for an easy quickstart


### Config File

Modify the app/config/config.php file according to your needs. You need to updated based on your local settings.

```
//Database Configuration
define('DB_HOST', '<databaseHost>');
define('DB_USER', '<databaseUser>');
define('DB_PASS', '<databasePassword>');
define('DB_NAME', '<databaseName>');
```

Modify it like this

```
//Database Configuration
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'postly');
```

### htaccess file

Modify the RewriteBase in the .htaccess file inside the public folder to match the name of your installation folder

### Install the Database

Create a database of your choice in PhpMyAdmin .

## Built With

* PHP
* Bootstrap CSS 4.0


## Authors

* **Ayoub Berouijil** - *Initial work* - [Ayoub Berouijil](https://github.com/ayoub129)

## License

This project is licensed under the MIT License
