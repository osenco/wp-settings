# WordPress Settings
## The Settings Page
### Installation
#### Via Composer
Navigate to the base of your plugin/theme direcory and run the following command
```cmd
composer require osenco/wp-settings
```

Remember to include the autoloder in your plugin main file, or your theme's `functions.php`
```php
require_once __DIR__.'/vendor/autoload.php';
```

### Usage
See [Example.php](this sample class) for example usage.

## The OOP PLugin Base
You can use this package as a base to create your plugin or theme in a purely OOP PHP implementation. Just install it as above, then edit the composer.json file to include an autoloader for your custom code.
