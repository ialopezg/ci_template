# CI_Template

CodeIgniter Templating


OUTLINE
-------
- [Requirements](#requirements)
- [Installation](#installation)
---
REQUIREMENTS
------------

This library requires the following:

- PHP 5.4.0+
- CodeIgniter 3.0.0+
---
INSTALLATION
------------
Run Composer in your Codeigniter project under the folder `\application`:

    composer require ialopezg/ci_basemodel
    
Check Codeigniter `application/config/config.php`:

```php
$config['composer_autoload'] = TRUE;
```
    
> You could customize the vendor path into `$config['composer_autoload']`
---