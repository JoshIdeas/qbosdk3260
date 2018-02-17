# QBO SDK for Drupal 7/8 JI QuickBooks Module 

This SDK was adapted from the original work from QuickBooks programmers.
I needed to rewrite parts of their work to disable some features,
enable others, fix bugs, and allow it to work with Drupal 7 and Drupal 8.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The JI QuickBooks module (https://www.drupal.org/project/ji_quickbooks).
A QuickBooks Online account (qbo.intuit.com). Drupal 7 or Drupal 8's
Ubercart or Commerce modules. Composer (https://getcomposer.org/) installed
on the web server.

Additional requirements:
PHP 5.3 or greater
PECL OAuth (http://pecl.php.net/package/oauth)

### Installing

Drupal 7

```
/sites/all/modules/libraries/qbosdk3260
```

Drupal 8

```
/libraries/qbosdk3260
```

or

```
composer require drupal/ji_quickbooks
```


## Authors

* **Intuit.com** - *Initial work* - [Intuit](https://intuit.com)
* **Joshideas.com** - *Minor modifications and improvements* - [JoshIdeas](https://joshideas.com)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
