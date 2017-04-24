---
title: What is the difference between include and require in PHP
description: What is the difference between include and require in PHP.
header: What is the difference between include and require in PHP
---
Both are PHP statements to include and evaluate files but they handles errors differently.

include

    If an error occurs a warning will be generated and script will continue execution.

require

    If an error occurs a fatal error will be generated and script will stop execution.

Useful links: [include](http://php.net/manual/en/function.include.php), [require](http://php.net/manual/en/function.require.php)


