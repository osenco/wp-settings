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
See [this sample class](src/Example.php) for example usage.

## The OOP Plugin Base
You can use this package as a base to create your plugin or theme in a purely OOP PHP implementation. Just install it as above and create an `src` directory in your theme/plugin directory that will house all your namespaced code.

### Autoloading Classes
Remember to edit the composer.json file to include an autoloader for your custom code.
`composer.json`

```json
...
 "autoload": {
      "psr-4": {
          "Your\\Namespace\\": "src/"
      }
  }
...
```

