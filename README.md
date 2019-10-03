# Amazon_Alexa Module

The Amazon_Alexa module provides Alexa Delivery Notifications for tracking numbers added to orders.

## Installation
### Install via composer (recommended):
```
$ composer require beargroup/amazon-alexa-magento-2-module
$ php bin/magento module:enable Amazon_Alexa
$ php bin/magento setup:upgrade
$ php bin/magento setup:di:compile
$ php bin/magento cache:clean
```
### Manual install:
```
$ mkdir -p app/code/Amazon/
$ git clone https://github.com/BearGroup/amazon-alexa-magento-2-module.git app/code/Amazon/Alexa
$ php bin/magento module:enable Amazon_Alexa
$ php bin/magento setup:upgrade
$ php bin/magento setup:di:compile
$ php bin/magento cache:clean
```


## Dependencies

You can find a list of modules in the require section of the `composer.json` file located in the
same directory as this `README.md` file.

## Extension Points

Amazon Pay does not provide any specific extension points.

## Additional Information

[View the Complete User Guide](https://amzn.github.io/amazon-payments-magento-2-plugin/)
