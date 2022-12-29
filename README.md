# Change Product

Add Descaut In Persantage on Product Deatail Page and Remove Qty and Price on the Product Cart Page 

`Custom Category attribute`

## Composer install

- `composer config repositories.Product vcs https://github.com/rajudiya/Product`

- `composer require change/product:dev-main`

## Composer uninstall

- `composer remove change/product`

## Known issues

- **Issues will be here**
  Compartible with magento 2.4.5

## Developer informations
- Developer Name - Rohan Ajudiya
- Inkdin url     - https://www.linkedin.com/in/ajudiya-rohan-9a9ab81b3/
- Contect us     - +91 6353856107

### Install module

1. Run `php bin/magento setup:upgrade`
2. Run `php bin/magento setup:di:compile`
3. Run `php rm -rf generated/`
3. Run `php bin/magento s:s:d`
4. Run `php bin/magento c:c`
6. Run `php bin/magento indexer:reindex`
7. run `php bin/magento setup:static-content:deploy -f`

### Uninstall module
1. Run `php bin/magento setup:di:compile`
2. Run `php bin/magento s:s:d`
3. Run `php bin/magento c:c`
4. Run `php bin/magento indexer:reindex`
5. run `php bin/magento setup:static-content:deploy -f`

### Additional developer notes
Reference URL `References will be added.`
