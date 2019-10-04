# Cache
A simple PHP class for caching

# Use

```php
<?php

require 'vendor/autoload.php';

$cache = new Cache([
  'path' => 'tmp/cache',    // path storage
  'ttl' => 3600,            // time of life default 1 hour
  'prefix' => 'cache_'      // prefix name not duplicate
]);

```
