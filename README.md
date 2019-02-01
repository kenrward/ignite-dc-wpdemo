# ignite-dc-wpdemo

## 1. Create Azure Resources using Azure CLI

## 2. Deploy web code via GitHub

## 3. Deploy database via MySQL Client Tools

## 4. Update WordPress config via Azure SCM

Using the App Service Editor (Preview) copy wp-config-sample.php to wp-config.php.  Replace the following:

```php
// ** MySQL settings - You can get this info from your web host ** //
/** The name of the database for WordPress */
define( 'DB_NAME', getenv("WORDPRESS_DB_NAME") );

/** MySQL database username */
define( 'DB_USER', getenv("WORDPRESS_DB_USER") );

/** MySQL database password */
define( 'DB_PASSWORD', getenv("WORDPRESS_DB_PASSWORD") );

/** MySQL hostname */
define( 'DB_HOST', getenv("WORDPRESS_DB_HOST") );

````

## 5. Update URL with Search Replace DB script deployed via ZipDeploy

