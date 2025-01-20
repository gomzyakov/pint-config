# Code-style configuration for Laravel Pint

[![packagist](https://img.shields.io/packagist/v/gomzyakov/pint-config.svg)](https://packagist.org/packages/gomzyakov/pint-config)
[![downloads_count](https://img.shields.io/packagist/dt/gomzyakov/pint-config.svg)](https://packagist.org/packages/gomzyakov/pint-config)
[![license](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/gomzyakov/pint-config/blob/development/LICENSE)

This package provides a [Laravel Pint](https://laravel.com/docs/pint) configuration for PHP projects which follow the [PSR-12 coding style](https://www.php-fig.org/psr/psr-12/) and coding style commonly seen in the official PHP documentation.

## Installation

Install the package using Composer:

```sh
composer require --dev laravel/pint gomzyakov/pint-config
```

## Usage

Either run Pint directly with the configuration file:

```sh
./vendor/bin/pint --config vendor/gomzyakov/pint-config/pint.json
```

Or add a `format` script to your `composer.json` file to run Pint with the configuration file:

```sh
composer config scripts.format 'pint --config vendor/gomzyakov/pint-config/pint.json' --file composer.json
```

And run the script:

```sh
composer format
```

## Support

If you find any package errors, please, [make an issue](https://github.com/gomzyakov/pint-config/issues) in current repository.

## License

This is open-sourced software licensed under the [MIT License](https://github.com/gomzyakov/pint-config/blob/main/LICENSE).
