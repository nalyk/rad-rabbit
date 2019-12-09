<h1 align="center">
<pre>
  (\/)
 ( ..)
c(")(")
</pre>
</h1>

<h3 align="center">RAD RABBIT</h3>
<h6 align="center">Slim 4 Skeleton</h6>

<div align="center">

  [![Latest Version on Packagist](https://img.shields.io/github/release/nalyk/rad-rabbit.svg)](https://packagist.org/packages/nalyk/rad-rabbit)
  [![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE.md)
  [![Build Status](https://github.com/nalyk/rad-rabbit/workflows/PHP/badge.svg)](https://github.com/nalyk/rad-rabbit/actions)
  [![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/nalyk/rad-rabbit.svg)](https://scrutinizer-ci.com/g/nalyk/rad-rabbit/code-structure)
  [![Quality Score](https://img.shields.io/scrutinizer/quality/g/nalyk/rad-rabbit.svg)](https://scrutinizer-ci.com/g/nalyk/rad-rabbit/?branch=master)
  [![Total Downloads](https://img.shields.io/packagist/dt/nalyk/rad-rabbit.svg)](https://packagist.org/packages/nalyk/rad-rabbit/stats)

</div>

This is a skeleton to quickly set up a new [Slim 4](https://www.slimframework.com/) application.

## Requirements

* PHP 7.1+
* NGINX
* Composer (only for development)

#### Recommended

* MySQL 5.7+, 8.x
* [NPM](https://nodejs.org/en/download/) for webpack

## Features

This project comes configured with:

* Modern coding style (PSR-1, PSR-2, PSR-12)
* PHPDoc Standard (PSR-5, PSR-19)
* Class Autoloader (PSR-4)
* HTTP request and response (PSR-7)
* HTTP Server Request Handlers, Middleware (PSR-15)
* HTTP Factories (PSR-17)
* Dependency injection container (PSR-11)
* Routing
* Single action controllers ([ADR](https://github.com/pmjones/adr/blob/master/ADR.md))
* Logging (PSR-3)
* Translations
* Sessions middleware
* Database Query Builder
* Database Migrations (Phinx)
* Database Migrations Generator
* Date and time (Chronos)
* Console Commands (Symfony)
* Unit- and integrations tests (PHPUnit)
* Tested on Travis CI and Scrutinizer CI
* PHPStan, max level
* Build and deployment scripts

### Packages

This project also uses the following packages:

* [phpunit](https://github.com/sebastianbergmann/phpunit) as unit testing framework
* [slim/psr7](https://github.com/slimphp/Slim-Psr7) as PSR-7 implementation
* [monolog/monolog](https://github.com/monolog/monolog) as logger (PSR-3)
* [slim/twig-view](https://github.com/slimphp/Twig-View) as template engine
* [php-di/php-di](https://github.com/PHP-DI/PHP-DI) as container implementation (PSR-11)
* [symfony/translation](https://github.com/symfony/translation) as translator
* [odan/twig-translation](https://github.com/odan/twig-translation) as Twig translator extension
* [webpack](https://webpack.js.org/) as bundler 

## Documentation

Read the **[Documentation](https://odan.github.io/slim4-skeleton)**

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
