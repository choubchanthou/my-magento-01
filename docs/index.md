# Installation
```php
<?php
echo "Hello world";
```

[Click here](https://google.com.kh) to download the library.

### A typical top-level directory layout
```
   app/
   code/local/srb/shipback/
   Helper/: Store DAO classes for accessing the CMS database and stores API class for requesting to SRB database
   Model/: Keeps model classes for mapping to CMS database
   controllers/: Keeps controller classes (backend, frontend and webhook)
   etc: Store most of the configuration for the plugin including permissions, version info, paths and configuration values
   sql/srb_shipback_setup/: Stored SQL script that will be executed when user install or upgrade the plugin
   design/
   adminhtml/default/default/layout/shoprunback/: Stores mapping that bind controllers and template for admin side
   adminhtml/default/default/template/shoprunback/: Stores template designs for admin side
   frontend/rwd/default/layout/: Stores layout for client side (return page)
   frontend/rwd/default/template/shoprunback/: Stores template for return page (client side)

   etc/modules/: Is where we register our plugin to the CMS by placing our module configuration file in here (SRB_Shipback.xml)
   locale/: Keeps translated files
   Fr_FR/SRB_Shipback.csv: French Translation of SRB modules for France
   Fr_CA/SRB_Shipback.csv: French Translation of SRB modules for Canada

```    

Choose Option:
-[x] Option 1
-[] Option 2
-[] Option 3

