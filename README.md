# zipline-portfolio

1. Create a file named "helpers.php" in "app" folder. (beside filters.php and routes.php)
2. Create a folder named "helpers" in app folder. (beside your helpers.php file)
3. Put "pagination_sort_helper.php" file in "helpers" folder.
4. Include (require) "pagination_sort_helper.php" file in helpers.php.
in helpers.php write: `php require_once __DIR__ . '/helpers/pagination_sort_helper.php';`

5. Load helpers.php file in "app/start/global.php". At the end of the file:
6. vvv
```php
require app_path() . '/filters.php';
require app_path() . '/helpers.php';
```
