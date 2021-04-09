[Back to the Ling/Kit_PicassoWidget api](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget.md)<br>
[Back to the Ling\Kit_PicassoWidget\WidgetHandler\PicassoWidgetHandler class](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/WidgetHandler/PicassoWidgetHandler.md)


PicassoWidgetHandler::processBrainFile
================



PicassoWidgetHandler::processBrainFile — Process the brain file.




Description
================


private [PicassoWidgetHandler::processBrainFile](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/WidgetHandler/PicassoWidgetHandler/processBrainFile.md)(string $file) : void




Process the brain file.
Note: we isolate it in its own function, because we don't want the file to access widgetConf directly (from the process method).

Instead, the brain file should register variables via our registerWidgetVar method.




Parameters
================


- file

    


Return values
================

Returns void.








Source Code
===========
See the source code for method [PicassoWidgetHandler::processBrainFile](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/WidgetHandler/PicassoWidgetHandler.php#L425-L428)


See Also
================

The [PicassoWidgetHandler](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/WidgetHandler/PicassoWidgetHandler.md) class.

Previous method: [getWidgetDir](https://github.com/lingtalfi/Kit_PicassoWidget/blob/master/doc/api/Ling/Kit_PicassoWidget/WidgetHandler/PicassoWidgetHandler/getWidgetDir.md)<br>

