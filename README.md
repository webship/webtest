# WebTest

### Website Testing tools.

* [Drupal Core DEV](https://github.com/drupal/core-dev): ^8 or ^9
* [Drupal Extension](https://packagist.org/packages/drupal/drupal-extension): ^3
* [Behat](https://packagist.org/packages/behat/behat): ^3
* [Behat UI](https://www.drupal.org/project/behat_ui): ^3
* [Phing](https://packagist.org/packages/phing/phing): ^2


### Recommended to use with composer:

```
  "require-dev": {
    "drupal/webtest": "2.*@stable"
  },
  "config": {
    "bin-dir": "bin/",
    "secure-http": false,
    "preferred-install": {
      "drupal/core": "dist"
    }
  },
```