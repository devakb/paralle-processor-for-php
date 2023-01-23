# ParalleProcessor for PHP
@Tested: v8


# ⭐ Usages 

> 👉 **Download** ⬇️ ParalleProcessor.php

```
$tasks = [
  "id" => "00001", "command" => "php artisan command_name",
  "id" => "00002", "command" => "php artisan command_name",
  "id" => "00003", "command" => "php artisan command_name",
];

$processor = new ParalleProcessor($tasks);
$processor->start();

```
