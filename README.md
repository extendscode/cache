# Cache
A simple PHP class for caching

# Use

```php
<?php

require 'vendor/autoload.php';

$cache = new Cache([
  'path' => 'your-path',    // path store
  'ttl' => 3600,            // time of life default 1 hour
  'prefix' => 'my_cache_'   // prefix name not duplicate
]);

```
