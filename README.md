php-image-Helper
================

PHP library to resize, scale and crop images.

Setup
-----
If using [Composer](https://getcomposer.org/), in your `composer.json` file add:

```json
{
    "require": {
        "vad-naitik/PHP-Image-Helper": "1.0.*"
    }
}
```
Otherwise:

```php
include '/path/to/ImageHelper.php';
```

Because this class uses namespacing, when instantiating the object, you need to either use the fully qualified namespace:

```php
$image = new \VadNaitik\ImageHelper();
```

Or alias it:

```php

use \VadNaitik\ImageHelper;

$image = new ImageHelper();
```

> Note: This library uses GD class which do not support resizing animated gif files

------------------
