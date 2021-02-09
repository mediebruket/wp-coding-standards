# Mediebruket WordPress Coding Standards

We've transitioned to use [PSR-12 coding style](https://www.php-fig.org/psr/psr-12/) for our own Wordpress projects.

## Installation

```bash
composer require mediebruket/wp-coding-standards --dev
```

Copy and modify the sample configuration file.

```bash
cp vendor/mediebruket/wp-coding-standards/phpcs.xml.dist.sample phpcs.xml.dist
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

