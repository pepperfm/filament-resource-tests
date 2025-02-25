# Filament Resource Tests

[![Latest Version on Packagist](https://img.shields.io/packagist/v/codewithdennis/filament-resource-tests.svg?style=flat-square)](https://packagist.org/packages/codewithdennis/filament-resource-tests)
[![Total Downloads](https://img.shields.io/packagist/dt/codewithdennis/filament-resource-tests.svg?style=flat-square)](https://packagist.org/packages/codewithdennis/filament-resource-tests)

A package that creates PEST tests specifically tailored for your filament resources.

### This package is still in development and not ready for use.
Please do not use it in production.

## Installation
You can install the package via composer:

```bash
composer require codewithdennis/filament-resource-tests
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="filament-resource-tests-config"
```

This is the contents of the published config file:

```php
return [
    //
];
```

You can create a new test for a resource by running the following command:

```bash
php artisan filament:make-test BlogResource
```

## Credits

- [CodeWithDennis](https://github.com/CodeWithDennis)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
