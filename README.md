# magento2.regurl

#instalacja
````
composer require wm21w/magento2.regurl
php bin/magento setup:upgrade
````

#sposób użycia

Wygeneruj adresy URL dla produktów w widoku sklepu ID = 1
````
php bin/magento wm21w:regenurl --store 1
````
Wygeneruj adresy URL dla wybranych produktów ID (1, 2, 3, 4) dla widoku sklepu ID 1
````
php bin/magento wm21w:regenurl --store 1 1 2 3 4
````