# Code-style configuration for Laravel Pint

[![packagist](https://img.shields.io/packagist/v/gomzyakov/pint-config.svg)](https://packagist.org/packages/gomzyakov/pint-config)
[![downloads_count](https://img.shields.io/packagist/dt/gomzyakov/pint-config.svg)](https://packagist.org/packages/gomzyakov/pint-config)
[![license](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/gomzyakov/pint-config/blob/development/LICENSE)
[![codecov](https://codecov.io/gh/gomzyakov/pint-config/branch/main/graph/badge.svg?token=4CYTVMVUYV)](https://codecov.io/gh/gomzyakov/pint-config)

This package allows sharing identical [php-cs-fixer](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer) formatting rules across all of your projects without copy-and-pasting configuration files.

## Quickstart

### Step 1 of 2

Install [Laravel Pint](https://github.com/laravel/pint) & this package via [Composer](https://getcomposer.org):

```sh
composer require --dev laravel/pint gomzyakov/pint-config
```

### Step 2 of 2

**And that's it!** You can now find code style violations with following command:

```sh
./vendor/bin/pint --config vendor/gomzyakov/pint-config/pint.json
```

## Support

If you find any package errors, please, [make an issue](https://github.com/gomzyakov/pint-config/issues) in current repository.

## License

This is open-sourced software licensed under the [MIT License](https://github.com/gomzyakov/pint-config/blob/main/LICENSE).
