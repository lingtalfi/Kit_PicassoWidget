Example #1: simple example
-----------


I'm using this example to generate widget doc for the [Light_Kit_BootstrapWidgetLibrary](https://github.com/lingtalfi/Light_Kit_BootstrapWidgetLibrary).


```php

$out = "/tmp/widgets.md";
$descrDir = "/komin/jin_site_demo/universe/Ling/Light_Kit_BootstrapWidgetLibrary/assets";
$imgDir = "/komin/lingtalfi.com/app/www/img/universe/Light_Kit_BootstrapWidgetLibrary/screenshots";
$o = new VariableDescriptionDocWriterUtil();
$o->setVariablesDescriptionDir($descrDir);
$o->setImgBaseDir($imgDir);
$o->setImgBaseUrl("http://lingtalfi.com/img/universe/Light_Kit_BootstrapWidgetLibrary/screenshots");
$o->setDocumentDate("2019-05-01");
$o->setDocumentTitle("Bootstrap Widget Library");
a($o->writeDoc($out));
az();
```