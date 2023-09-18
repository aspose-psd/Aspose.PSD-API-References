---
title: MaskingOptions
second_title: Aspose.PSD for Java API Reference
description: Represents the common image masking options.
type: docs
weight: 16
url: /java/com.aspose.psd.masking.options/maskingoptions/
---

**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Represents the common image masking options.
## Constructors

| Constructor | Description |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Fields

| Field | Description |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | The background object number |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Gets the arguments for segmentation algorithm. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Gets the background replacement color. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Gets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background. |
| [getExportOptions()](#getExportOptions--) | Gets the image export options. |
| [getMaskingArea()](#getMaskingArea--) | Gets the masking area. |
| [getMethod()](#getMethod--) | Gets the segmentation method. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Sets the arguments for segmentation algorithm. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Sets the background replacement color. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Sets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Sets the image export options. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Sets the masking area. |
| [setMethod(int value)](#setMethod-int-) | Sets the segmentation method. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


The background object number

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Gets the arguments for segmentation algorithm.

Value: The arguments for segmentation algorithm.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Gets the background replacement color.

Value: The background replacement color. This color will be used as background color in resulting images.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Gets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.

Value:  true  if decompose; otherwise,  false .

**Returns:**
boolean - a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Gets the image export options.

Value: The image export options that will be used to create the resulting images.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
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

