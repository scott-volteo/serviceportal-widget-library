# Multi-Screen Catalog Item

## Description

The Multi-Screen Catalog Item Widget allows catalog items to be broken up into smaller sections enabling a better user experience for your requestors. Walk your users slowly and painlessly through a larger catalog items instead of bombarding them with tens of variables at once! The widget applies a clean, modern look and retains all of the core functionality of the out-of-box widget.

The widget works with standard catalog items as well as record producers. Upon opening any catalog item, the user will be presented with a display screen (picture, short description, and description) for the item before being prompted to fill in the item variables.

The widget is easily configurable with instance options and the colors can easily be change to meet any company palette with the use of SASS variables.

## Screenshot

![Multi Screen Catalog Item](https://raw.githubusercontent.com/platform-experience/serviceportal-widget-library/master/src/pe-multi-screen-catalog-item/images/pe-multi-screen-catalog-item.png)

## Additional Information/Notes

> None

## Installation

Download and install update set **[pe-multi-screen-catalog-item.u-update-set.xml](https://github.com/platform-experience/serviceportal-widget-library/blob/master/src/pe-multi-screen-catalog-item/pe-multi-screen-catalog-item.u-update-set.xml)**

After installation, the widget can be accessed via the `Service Portal > Widgets` section for use and customization.

- SN Product Documentation - ['Load a customization from a single XML file'](https://docs.servicenow.com/bundle/kingston-application-development/page/build/system-update-sets/task/t_SaveAnUpdateSetAsAnXMLFile.html)

## Configuration

> None

## Platform Dependencies

### SN System Tables

> None

### UI Dependencies

> None

## CSS/SASS Variables

_CSS/SASS variables are given default values that can be overridden with theming or portal-level CSS._

```scss
$si-mc-dark-color: #2d2b5d;
$si-mc-light-text-color: #ffffff;
$si-mc-action-background-color: #dddddd;
$si-mc-max-height: 700px;
$si-mc-background-color: #ffffff;
$si-mc-indicator-background-color: #eeeeee;
$si-mc-indicator-background-color-active: $si-mc-dark-color !default;
$si-mc-field-label-color: $si-mc-dark-color !default;
$si-mc-title-color: $si-mc-dark-color !default;
$si-mc-indicator-color: $si-mc-dark-color !default;
$si-mc-indicator-color-active: $si-mc-light-text-color !default;
$si-mc-attachment-color: $si-mc-dark-color !default;
$si-mc-attachment-btn-background-color: $si-mc-dark-color !default;
$si-mc-attachment-pill-background-color: #eeeeee;
$si-mc-attachment-btn-color: $si-mc-light-text-color !default;
$si-mc-border-radius: 3px !default;
$si-mc-action-bar-background-color: $si-mc-action-background-color;
$si-mc-image-height: auto;
$si-mc-image-width: auto;
```