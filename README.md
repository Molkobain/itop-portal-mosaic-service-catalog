👋 Available on [iTop Hub](https://store.itophub.io/en_US/products/molkobain-portal-mosaic-service-catalog) & [Molkobain I/O!](https://www.molkobain.com/product/service-catalog-as-mosaic-by-default/)

# iTop extension: molkobain-portal-mosaic-service-catalog
* [Description](#description)
* [Compatibility](#compatibility)
* [Installation](#installation)
* [Configuration](#configuration)

## Description
This extension changes the default view mode of the service catalog within the portal, to *mosaic* (similar to Windows 8).
* This mode is much more efficient and user friendly if you have a small number of services and service subcategories.
* In this case, you can display icons, which if well chosen, are understood more rapidly than a text.
* Navigation on small devices is also easier with this mode.

![Description decoration](https://raw.githubusercontent.com/Molkobain/itop-portal-mosaic-service-catalog/master/docs/service-catalog-mosaic.PNG)

## Compatibility
Compatible with iTop 2.4+

## Installation
* Unzip the extension
* Copy the ``dist/molkobain-portal-mosaic-service-catalog`` folder under ``<PATH_TO_ITOP>/extensions`` folder of your iTop
* Run iTop setup & select extension *Portal: Service catalog as mosaic by default*

*Your folders should look like this*

![Extensions folder](https://raw.githubusercontent.com/Molkobain/itop-portal-mosaic-service-catalog/master/docs/mpmsc-install.PNG)

## Configuration
### Standard portal
No configuration needed.

### Customized portal
If you customized the user portal, you will have to check/modify 2 things on the ``datamodel.molkobain-portal-mosaic-service-catalog.xml`` file of the extension, then run an iTop setup.
* Portal ID: If your portal ID is not ``itop-portal``, change it to your custom ID on line 4.
* Service catalog brick: If you are not targetting the standard service catalog, change the brick ID on line 6 (``services``) with yours.

## Licensing
This extension is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
