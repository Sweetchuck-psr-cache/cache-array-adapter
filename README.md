# Array PSR-6 Cache pool
[![Gitter](https://badges.gitter.im/php-cache/cache.svg)](https://gitter.im/php-cache/cache?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Latest Stable Version](https://poser.pugx.org/cache/array-adapter/v/stable)](https://packagist.org/packages/cache/array-adapter)
[![codecov.io](https://codecov.io/github/php-cache/array-adapter/coverage.svg?branch=master)](https://codecov.io/github/array-cache/apc-adapter?branch=master)
[![Total Downloads](https://poser.pugx.org/cache/array-adapter/downloads)](https://packagist.org/packages/cache/array-adapter)
[![Monthly Downloads](https://poser.pugx.org/cache/array-adapter/d/monthly.png)](https://packagist.org/packages/cache/array-adapter)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)

This is a PSR-6 cache implementation using PHP array. It is a part of the PHP Cache organisation. To read about
features like tagging and hierarchy support please read the shared documentation at [www.php-cache.com](https://www.php-cache.com).

### Install

```bash
composer require cache/array-adapter
```

### Use

You do not need to do any configuration to use the `ArrayCachePool`.

```php
$pool = new \Cache\Adapter\PHPArray\ArrayCachePool();
```

### Contribute

Contributions are very welcome! Send a pull request to the [main repository](https://github.com/php-cache/cache) or
report any issues you find on the [issue tracker](http://issues.php-cache.com).
