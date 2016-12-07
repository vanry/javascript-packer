### PHP Javascript Packer

```php

use JavascriptPacker\JavascriptPacker;

$source = "console.log('hello world');";

$packer = new JavascriptPacker;

echo $packer->pack($source);

```