[Back to the Ling/Kit_PicassoWidget api](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget.md)



The WidgetConfAwarePicassoWidget class
================
2019-04-24 --> 2021-05-31






Introduction
============

The WidgetConfAwarePicassoWidget class.

In a nutshell
------------
If your widget ever needs to access [the widget configuration array](https://github.com/lingtalfi/Kit_PicassoWidget#the-picasso-widget-array),
then extend this class instead of the PicassoWidget class.

Otherwise, just extend the PicassoWidget class.



Class synopsis
==============


class <span class="pl-k">WidgetConfAwarePicassoWidget</span> extends [PicassoWidget](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget.md) implements [UniversalTemplateEngineInterface](https://github.com/lingtalfi/UniversalTemplateEngine/blob/master/UniversalTemplateEngineInterface.php), [WidgetConfAwarePicassoWidgetInterface](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/WidgetConfAwarePicassoWidgetInterface.md) {

- Properties
    - protected array [$widgetConf](#property-widgetConf) ;

- Inherited properties
    - protected array [PicassoWidget::$libraries](#property-libraries) ;
    - protected array [PicassoWidget::$attr](#property-attr) ;
    - protected [Ling\HtmlPageTools\Copilot\HtmlPageCopilot](https://github.com/lingtalfi/HtmlPageTools/blob/master/doc/api/Ling/HtmlPageTools/Copilot/HtmlPageCopilot.md) [PicassoWidget::$copilot](#property-copilot) ;

- Methods
    - public [__construct](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/WidgetConfAwarePicassoWidget/__construct.md)() : void
    - public [setWidgetConf](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/WidgetConfAwarePicassoWidget/setWidgetConf.md)(array $widgetConf) : void
    - public [getWidgetConf](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/WidgetConfAwarePicassoWidget/getWidgetConf.md)() : array

- Inherited methods
    - public [PicassoWidget::getLibraries](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/getLibraries.md)() : array
    - public [PicassoWidget::setCopilot](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/setCopilot.md)([Ling\HtmlPageTools\Copilot\HtmlPageCopilot](https://github.com/lingtalfi/HtmlPageTools/blob/master/doc/api/Ling/HtmlPageTools/Copilot/HtmlPageCopilot.md) $copilot) : void
    - public [PicassoWidget::renderFile](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/renderFile.md)(string $filePath, ?array $variables = []) : false | string
    - public [PicassoWidget::prepare](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/prepare.md)(array &$widgetConf, [Ling\HtmlPageTools\Copilot\HtmlPageCopilot](https://github.com/lingtalfi/HtmlPageTools/blob/master/doc/api/Ling/HtmlPageTools/Copilot/HtmlPageCopilot.md) $copilot) : void
    - protected [PicassoWidget::getAttributesHtml](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/getAttributesHtml.md)(?bool $excludeClass = true) : string
    - protected [PicassoWidget::getCssClass](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/getCssClass.md)() : string
    - protected [PicassoWidget::registerLibrary](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/registerLibrary.md)(string $libraryName, array $css, array $js) : void
    - public ZephyrTemplateEngine::render(string $resourceId, ?array $variables = []) : false | string
    - public ZephyrTemplateEngine::getErrors() : array
    - public ZephyrTemplateEngine::setDirectory(string $directory) : void
    - protected ZephyrTemplateEngine::interpret(string $___path, array $z) : false | string

}




Properties
=============

- <span id="property-widgetConf"><b>widgetConf</b></span>

    This property holds the widgetConf for this instance.
    
    

- <span id="property-libraries"><b>libraries</b></span>

    This property holds the libraries for this instance.
    
    It's an array of library name => assets.
    
    Assets is the following array:
    
    - css: array of css urls
    - js: array of js urls
    
    

- <span id="property-attr"><b>attr</b></span>

    This property holds the attr for this instance.
    This is an array of html attributes to add to the widget's outer tag.
    
    For instance:
    - id: my_id
    - class: my_class1 my_class2
    - data-example-value: 668
    
    

- <span id="property-copilot"><b>copilot</b></span>

    This property holds the copilot for this instance.
    Sometimes, templates might need to access the copilot directly,
    hence the existence of this property.
    
    



Methods
==============

- [WidgetConfAwarePicassoWidget::__construct](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/WidgetConfAwarePicassoWidget/__construct.md) &ndash; Builds the WidgetConfAwarePicassoWidget instance.
- [WidgetConfAwarePicassoWidget::setWidgetConf](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/WidgetConfAwarePicassoWidget/setWidgetConf.md) &ndash; Sets the widget configuration.
- [WidgetConfAwarePicassoWidget::getWidgetConf](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/WidgetConfAwarePicassoWidget/getWidgetConf.md) &ndash; Returns the widget configuration.
- [PicassoWidget::getLibraries](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/getLibraries.md) &ndash; Returns the libraries of this instance.
- [PicassoWidget::setCopilot](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/setCopilot.md) &ndash; Sets the copilot.
- [PicassoWidget::renderFile](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/renderFile.md) &ndash; Parses the file identified and returns its interpreted content (by injecting the variables in it).
- [PicassoWidget::prepare](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/prepare.md) &ndash; Prepares the widget according to the given widget configuration.
- [PicassoWidget::getAttributesHtml](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/getAttributesHtml.md) &ndash; Returns the string of html attributes defined in the widget attributes (attr property in the [widget configuration array](https://github.com/lingtalfi/Kit_PicassoWidget#the-picasso-widget-array)).
- [PicassoWidget::getCssClass](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/getCssClass.md) &ndash; 
- [PicassoWidget::registerLibrary](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget/registerLibrary.md) &ndash; Registers an (external) library that this widget uses.
- ZephyrTemplateEngine::render &ndash; Parses the template identified by $resourceId and returns the interpreted template (the template with the variables injected in it).
- ZephyrTemplateEngine::getErrors &ndash; Returns the errors of this instance.
- ZephyrTemplateEngine::setDirectory &ndash; Sets the directory.
- ZephyrTemplateEngine::interpret &ndash; and returns the resulting html code.





Location
=============
Ling\Kit_PicassoWidget\Widget\WidgetConfAwarePicassoWidget<br>
See the source code of [Ling\Kit_PicassoWidget\Widget\WidgetConfAwarePicassoWidget](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/Widget/WidgetConfAwarePicassoWidget.php)



SeeAlso
==============
Previous class: [PicassoWidget](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/PicassoWidget.md)<br>Next class: [WidgetConfAwarePicassoWidgetInterface](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/Widget/WidgetConfAwarePicassoWidgetInterface.md)<br>
