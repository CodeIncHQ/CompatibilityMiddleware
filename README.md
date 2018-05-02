# PSR-15 middlewares 



This library provides a collection of [PSR-15](https://www.php-fig.org/psr/psr-15/) middleware to provide compatibility with older PHP scripts. 



## The collection includes

* [`PhpGpcVarsMiddleware`](src/PhpGpcVarsMiddleware.php) Extract PSR-7 request data to PHP GPC variables `$_GET`, `$_POST`, `$_COOKIE` and `$_SERVER`
* [`PhpSessionMiddleware`](src/PhpSessionMiddleware.php) Read sesion cookie from PSR-7 requests and add session cookie to PSR-7 responses


## Installation

This library is available through [Packagist](https://packagist.org/packages/codeinc/compatibility-middleware) and can be installed using [Composer](https://getcomposer.org/): 

```bash
composer require codeinc/compatibility-middleware
```

## License

The library is published under the MIT license (see [`LICENSE`](LICENSE) file).