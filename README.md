# Mediebruket WordPress Coding Standards

## Installation

In project
```bash
composer require mediebruket/wp-coding-standards --dev
```

## Usage

Check manually by running PHPCS from command line and specify the coding standard:

```bash
vendor/bin/phpcs --standard="Mediebruket" <path>
```

### PHPStorm Setup

Alternatively, the coding standard can be enabled in Phpstorm.

Phpstorm needs to know where PHP_CodeSniffer is located. Navigate to **Languages & Frameworks > PHP > Quality tools > PHP_CodeSniffer** and
specify the path the `phpcs` executable in your `vendor` directory by clicking **…** . Additionally, you can add the
path to `phpcbf` as well.

Then you'll have to specify the coding standard. Navigate to **Editor > Inspections > PHP > Quality tools > PHP_CodeSniffer validation > Options > Coding standard**.
Chose the preferred coding standard from the options section.

## Credits

This package is heavily inspired by

* [dekode/coding-standards](https://packagist.org/packages/dekode/coding-standards)
* [infinum/eightshift-coding-standards](https://packagist.org/packages/infinum/eightshift-coding-standards)
