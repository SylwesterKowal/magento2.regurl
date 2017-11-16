# magento2.regurl

#install
````
composer require sylwesterkowal/magento2.regurl
php bin/magento setup:upgrade
````

#use

Regenerate url for all products and the global store
````
php bin/magento wm21w:regenurl
````
Regenerate url for products with id (1, 2, 3, 4) for store 1
````
php bin/magento iazel:regenurl -s1 1 2 3 4
````