# Mediebruket WordPress Coding Standards

## Installation

In project
```bash
composer require mediebruket/wp-coding-standards --dev
```

Or install globally
```bash
composer global require mediebruket/wp-coding-standards
```

## Usage

Check manually by running PHPCS from command line and specify the coding standard:

```bash
vendor/bin/phpcs --standard="Mediebruket" <path>
```

You can omit `vendor/bin` if PHP_CodeSniffer is installed globally.

### PHPStorm Setup

Alternatively, the coding standard can be enabled in Phpstorm.

Phpstorm needs to know where PHP_CodeSniffer is located. Navigate to **Languages & Frameworks > PHP > Quality tools > PHP_CodeSniffer** and
specify the path your installation by clicking **…** .

Then you'll have to specify the coding standard. Navigate to **Editor > Inspections > PHP > Quality tools > PHP_CodeSniffer validation > Options > Coding standard**.
Chose the preferred coding standard from the options section.
