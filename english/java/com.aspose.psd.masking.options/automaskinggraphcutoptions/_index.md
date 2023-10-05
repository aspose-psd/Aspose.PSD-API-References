---
title: AutoMaskingGraphCutOptions
second_title: Aspose.PSD for Java API Reference
description: The GraphCut auto masking options.
type: docs
weight: 12
url: /java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

The GraphCut auto masking options.
## Constructors

| Constructor | Description |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Initializes a new instance of the [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) class. |
## Fields

| Field | Description |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | The background object number |
## Methods

| Method | Description |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Append auto masking args. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Fill inn default strokes. |
| [getArgs()](#getArgs--) | Gets the arguments for segmentation algorithm. |
| [getAssumedObjects()](#getAssumedObjects--) | Gets the assumed objects. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Gets the background replacement color. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Gets a value indicating whether default strokes should be calculated. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Gets the combined objects rectangle. |
| [getDecompose()](#getDecompose--) | Gets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Gets the default background strokes. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Gets the pre-calculated default foreground strokes. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Gets the default objects rectangles. |
| [getExportOptions()](#getExportOptions--) | Gets the image export options. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Gets the feathering radius. |
| [getMaskingArea()](#getMaskingArea--) | Gets the masking area. |
| [getMethod()](#getMethod--) | Gets the segmentation method. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Gets the default points pre-calculation process progress event handler. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Gets a value indicating whether assumed objects collection has human objects in it. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Sets the arguments for segmentation algorithm. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Sets the assumed objects. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Sets the background replacement color. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Sets a value indicating whether default strokes should be calculated. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | The combined objects rectangle. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Sets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | The default background strokes. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | The pre-calculated default foreground strokes. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | The default objects rectangles. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Sets the image export options. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Sets the feathering radius. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | A value indicating whether assumed objects collection has human objects in it. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Sets the masking area. |
| [setMethod(int value)](#setMethod-int-) | Sets the segmentation method. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Sets the default points pre-calculation process progress event handler. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Initializes a new instance of the [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) class.

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


The background object number

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Append auto masking args.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | The image. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Fill inn default strokes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | The image. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Gets the arguments for segmentation algorithm.

Value: The arguments for segmentation algorithm.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Gets the assumed objects.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - the assumed objects.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Gets the background replacement color.

Value: The background replacement color. This color will be used as background color in resulting images.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Gets a value indicating whether default strokes should be calculated.

**Returns:**
boolean - a value indicating whether default strokes should be calculated.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Gets the combined objects rectangle.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Gets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.

Value:  true  if decompose; otherwise,  false .

**Returns:**
boolean - a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Gets the default background strokes.

**Returns:**
com.aspose.psd.Point[] - the default background strokes.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Gets the pre-calculated default foreground strokes.

**Returns:**
com.aspose.psd.Point[] - the pre-calculated default foreground strokes.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Gets the default objects rectangles.

**Returns:**
com.aspose.psd.Rectangle[] - the default objects rectangles.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Gets the image export options.

Value: The image export options that will be used to create the resulting images.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Gets the feathering radius.

**Returns:**
int - the feathering radius.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Gets the masking area.

Value: The masking area which is a partial area of the source image. Rectangle.Empty value means full source image area.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Gets the segmentation method.

Value: The segmentation method.

**Returns:**
int - the segmentation method.
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Gets the default points pre-calculation process progress event handler.

Value: The progress event handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Gets a value indicating whether assumed objects collection has human objects in it.

**Returns:**
boolean - a value indicating whether assumed objects collection has human objects in it.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Sets the arguments for segmentation algorithm.

Value: The arguments for segmentation algorithm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | the arguments for segmentation algorithm. |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Sets the assumed objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | the assumed objects. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Sets the background replacement color.

Value: The background replacement color. This color will be used as background color in resulting images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | the background replacement color. |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Sets a value indicating whether default strokes should be calculated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether default strokes should be calculated. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


The combined objects rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | the combined objects rectangle. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Sets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.

Value:  true  if decompose; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background. |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


The default background strokes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | the default background strokes. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


The pre-calculated default foreground strokes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | the pre-calculated default foreground strokes. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


The default objects rectangles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | the default objects rectangles. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Sets the image export options.

Value: The image export options that will be used to create the resulting images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | the image export options. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Sets the feathering radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the feathering radius. |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


A value indicating whether assumed objects collection has human objects in it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether assumed objects collection has human objects in it. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Sets the masking area.

Value: The masking area which is a partial area of the source image. Rectangle.Empty value means full source image area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | the masking area. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Sets the segmentation method.

Value: The segmentation method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the segmentation method. |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Sets the default points pre-calculation process progress event handler.

Value: The progress event handler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | the default points pre-calculation process progress event handler. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

