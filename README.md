# WebTest

### Website Testing tools.

* Drupal Core DEV: ^8.8.0
* Drupal Console": ^1.0
* Drush": ^9.0
* Behat": ~3.0
* Behat UI: ^3.0
* Phing": ~2.0
* Drupal Extension: ^3.2

### Recommended to use with composer:

```
  "require-dev": {
    "drupal/webtest": "8.1.x-dev"
  },
  "config": {
    "bin-dir": "bin/",
    "secure-http": false,
    "preferred-install": {
      "drupal/core": "dist"
    }
  },
```