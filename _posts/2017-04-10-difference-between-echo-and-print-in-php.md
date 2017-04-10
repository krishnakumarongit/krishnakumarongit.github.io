---
title: What is the difference between echo and print in PHP
description: What is the difference between echo and print in PHP.
header: What is the difference between echo and print in PHP
---
Both are PHP statements to display output. Following are the main
differnece between echo and print.

1. Speed

...echo is faster than print since it dosen't have a return value. In PHP
...print statement always retun 1.

2. Parameters

...echo can take multiple parameters.


```php
<?php 
   echo "first param", "second param", "third param";
?>
```

...print can only take one parameter


```php
<?php 
   print "first param";
?>
```

3. Expression

...print can be used as a part of an expression since it behaves like a function where echo cannot.
