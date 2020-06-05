# WebTest

### Website Testing tools.

* Drupal Core DEV: ^8 or ^9
* Drupal Console": ^1
* Drush": ^9 or ^10
* Behat": ^3
* Behat UI: ^3
* Phing": ^2
* Drupal Extension: ^3

### Recommended to use with composer:

```
  "require-dev": {
    "drupal/webtest": "@stable"
  },
  "config": {
    "bin-dir": "bin/",
    "secure-http": false,
    "preferred-install": {
      "drupal/core": "dist"
    }
  },
```