# README #

This is php trait for Singleton pattern;

## Usage:

```
<?php

use cri2net\php_singleton\Singleton;

class YourClass
{
    use Singleton;
    
    /*
    code of your class
    */
}

$obj = YourClass::getInstance();
```
