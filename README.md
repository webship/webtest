# WebTest

### Website Testing tools.

* [Drupal Core DEV](https://github.com/drupal/core-dev): ~9.0
* [Drupal Extension](https://packagist.org/packages/drupal/drupal-extension): ~4.0
* [Behat UI](https://www.drupal.org/project/behat_ui): ~4.0


### Recommended to use with composer:

```
  "require-dev": {
    "drupal/webtest": "~9.0"
  },
  "config": {
    "bin-dir": "bin/",
    "secure-http": false,
    "preferred-install": {
      "drupal/core": "dist"
    }
  },
```