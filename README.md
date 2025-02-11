# PHP binaries used by PHPacker

This is a fork of the general purpose [NativePHP binaries(https://github.com/NativePHP/php-bin) targeting the [micro SAPI](https://github.com/easysoft/phpmicro)

## Installation

You can install the package via Composer:

```shell
composer require phpacker/php-bin
```

## Building

NativePHP uses [`static-php-cli`](https://static-php.dev) to build minimal, statically-linked, self-contained PHP
executables for each platform. This fork specifically outputs binaries targeting the micro SAPI

They are automatically built weekly to get the latest versions of PHP near enough as soon as they become available.

[Check here](https://github.com/NativePHP/php-bin/blob/main/php-extensions.txt) for the definitive list of
extensions that are compiled in.

## Issues

Please raise any issues on the [NativePHP/laravel](https://github.com/nativephp/laravel/issues/new/choose) repo.

## Credits

- [Marcel Pociot](https://github.com/mpociot)
- [Simon Hamp](https://github.com/simonhamp)
- [Willem Leuverink](https://github.com/gwleuverink)
- [All Contributors](../../contributors)

## License

This repository is simply a redistribution of PHP. As such its use and further distribution is subject to the various
license agreements found in [the licenses](license-files/)
