# PHP Image Converter

*Version 1.1 beta*

PHP library to convert between **gif**, **jpeg**, **png** and **webp** image files.

## Usage

### Syntax

```php
echo \ImageConverter\convert(string $from , string $to , int $quality);
```

### Example

```php
<?php
include __DIR__ . '/src/php-image-converter.php';

$from = __DIR__ . '/my-image.png';
$to = __DIR__ . '/my-image.webp';

echo \ImageConverter\convert($from, $to);
```

## Notes

If you try to convert to a path that has not been created, it will try to create it automatically.

## Requirements

- PHP 7+
- GD (active on almost every server by default)

## Contributors

- [@peter279k](https://github.com/peter279k)
- [@jenstornell](https://github.com/jenstornell)

## Inspiration

- https://github.com/rakibtg/PHP-ImageToWebp

## Donate

Donate to [DevoneraAB](https://www.paypal.me/DevoneraAB) if you want.

## License

MIT
