# TemplateEngine
Simple PHP template handler

## How to use

```php
include_once 'Template.php';

$template = new Template("layout/");

echo $template->loadTemplate("index", ["username" => "admin"]);
```
