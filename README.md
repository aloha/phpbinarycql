Php Binary CQL
============

Php implementation of the CQL binary protocol.  This project is a client that will allow queries to be sent using the binary protocol.  This fork is composer compatible.

Required PHP Modules (not installed by default)
--------------------
iconv
mbstring
bcmath

Installing Via Composer
--------------------------------------
This package is not submitted to packagist but you can add it to your composer.json file using the following require and repository entries.

Add custom package to repositories section in composer.json
```javascript
"repositories": [
        {
            "type": "package",
            "package": {
                "name": "aloha/phpbinarycql",
                "version": "0.0.3",
                "source": {
                    "url": "https://github.com/aloha/phpbinarycql",
                    "type": "git",
                    "reference": "0.0.3"
                }
            }
        }
    ],
```
Add desired release to require block in composer.json
```javascript
"require": {
        "aloha/phpbinarycql" : "0.0.3"
	},
```

Add PSR-0 line since you are loading a custom package
```javascript
"autoload": {
	"psr-0": {
	    "McFrazier\\PhpBinaryCql": "src/"
	}
},

Update Composer or composer install if running for first time
```bash
composer update
```


Forked From
--------------------------------------
https://github.com/rmcfrazier/phpbinarycql


Additional Information
----------------------
- Walk through of simple_query.php - http://blog.robert.mcfrazier.com/getting-started-php-binary-cql-client/
