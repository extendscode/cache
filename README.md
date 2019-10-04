# Cache
A simple PHP class for caching

# Use

```php
<?php

require 'vendor/autoload.php';

$cache = new Cache([
  'path' => 'tmp/cache',    // path storage
  'ttl' => 3600,            // cache lifetime (default:1 hour)
  'prefix' => 'cache_'      // prefix name not duplicate
]);

// Fetches an entry from the cache or store value into cache if no exists.
$key = $cache->get('key', 'default');

or

$key = $cache->get('key', function() {
  return ...
});

```
