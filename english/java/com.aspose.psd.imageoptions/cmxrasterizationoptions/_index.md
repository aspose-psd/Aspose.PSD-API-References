---
title: CmxRasterizationOptions
second_title: Aspose.PSD for Java API Reference
description: the CMX exporter options.
type: docs
weight: 11
url: /java/com.aspose.psd.imageoptions/cmxrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase), [com.aspose.psd.imageoptions.VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
```
public class CmxRasterizationOptions extends VectorRasterizationOptions
```

the CMX exporter options.
## Constructors

| Constructor | Description |
| --- | --- |
| [CmxRasterizationOptions()](#CmxRasterizationOptions--) | Initializes a new instance of the [CmxRasterizationOptions](../../com.aspose.psd.imageoptions/cmxrasterizationoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Copies to. |
| [deepClone()](#deepClone--) | Clones this instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Gets a background color. |
| [getBorderX()](#getBorderX--) | Gets or sets the border X. |
| [getBorderY()](#getBorderY--) | Gets or sets the border Y. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getCenterDrawing()](#getCenterDrawing--) | Gets a value indicating whether center drawing. |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getDrawColor()](#getDrawColor--) | Gets a foreground color. |
| [getFullFrame()](#getFullFrame--) | Gets a value indicating whether [full frame]. |
| [getMultiPageOptions()](#getMultiPageOptions--) | The multipage options |
| [getPageHeight()](#getPageHeight--) | Gets the page height. |
| [getPageSize()](#getPageSize--) | Gets the page size. |
| [getPageWidth()](#getPageWidth--) | Gets the page width. |
| [getPalette()](#getPalette--) | Gets or sets the color palette. |
| [getPositioning()](#getPositioning--) | Gets the positioning. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets or sets the progress event handler. |
| [getResolutionSettings()](#getResolutionSettings--) | Gets or sets the resolution settings. |
| [getSmoothingMode()](#getSmoothingMode--) | Gets the smoothing mode. |
| [getSource()](#getSource--) | Gets or sets the source to create image in. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Gets the text rendering hint. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Gets or sets the vector rasterization options. |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata container. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Sets a background color. |
| [setBorderX(float value)](#setBorderX-float-) | Gets or sets the border X. |
| [setBorderY(float value)](#setBorderY-float-) | Gets or sets the border Y. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Sets a value indicating whether center drawing. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | Sets a foreground color. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Sets a value indicating whether [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Gets or sets a value indicating whether ignore after create event. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | The multipage options |
| [setPageHeight(float value)](#setPageHeight-float-) | Sets the page height. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | Sets the page size. |
| [setPageWidth(float value)](#setPageWidth-float-) | Sets the page width. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Gets or sets the color palette. |
| [setPositioning(int value)](#setPositioning-int-) | Sets the positioning. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Gets or sets the progress event handler. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Gets or sets the resolution settings. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Sets the smoothing mode. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Gets or sets the source to create image in. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Sets the text rendering hint. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Gets or sets the vector rasterization options. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata container. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmxRasterizationOptions() {#CmxRasterizationOptions--}
```
public CmxRasterizationOptions()
```


Initializes a new instance of the [CmxRasterizationOptions](../../com.aspose.psd.imageoptions/cmxrasterizationoptions) class.

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. This method simply call dispose method.

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copies to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | The vector rasterization options. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clones this instance.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Clones this instance.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes the current instance.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets a background color.

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Gets or sets the border X.

**Returns:**
float - The border X.
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Gets or sets the border Y.

**Returns:**
float - The border Y.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Gets a value indicating whether center drawing.

**Returns:**
boolean - a value indicating whether center drawing.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). To take proper name of default font can be used next code snippet: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Value: The default replacement font.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Gets a foreground color.

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Gets a value indicating whether [full frame].

Value:  true  if [full frame]; otherwise,  false .

**Returns:**
boolean - a value indicating whether [full frame].
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


The multipage options

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Gets the page height.

**Returns:**
float - the page height.
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Gets the page size.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Gets the page width.

**Returns:**
float - the page width.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Gets or sets the color palette.

Value: The color palette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Gets the positioning.

Value: The positioning.

**Returns:**
int - the positioning.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Gets or sets the progress event handler.

Value: The progress event handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Gets or sets the resolution settings.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Gets the smoothing mode.

**Returns:**
int - the smoothing mode.
### getSource() {#getSource--}
```
public final Source getSource()
```


Gets or sets the source to create image in.

Value: The source to create image in.

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Gets the text rendering hint.

Value: The text rendering hint.

**Returns:**
int - the text rendering hint.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Gets or sets the vector rasterization options.

Value: The vector rasterization options.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets or sets the XMP metadata container.

Value: The XMP data container.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Sets a background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | a background color. |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Gets or sets the border X.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The border X. |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Gets or sets the border Y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The border Y. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Sets a value indicating whether center drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether center drawing. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). To take proper name of default font can be used next code snippet: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Value: The default replacement font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


Sets a foreground color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | a foreground color. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Sets a value indicating whether [full frame].

Value:  true  if [full frame]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Gets or sets a value indicating whether ignore after create event.

Value:  true  if ignore after create event; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


The multipage options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Sets the page height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the page height. |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


Sets the page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | the page size. |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Sets the page width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the page width. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Gets or sets the color palette.

Value: The color palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Sets the positioning.

Value: The positioning.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the positioning. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Gets or sets the progress event handler.

Value: The progress event handler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Gets or sets the resolution settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Sets the smoothing mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the smoothing mode. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Gets or sets the source to create image in.

Value: The source to create image in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Sets the text rendering hint.

Value: The text rendering hint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the text rendering hint. |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Gets or sets the vector rasterization options.

Value: The vector rasterization options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Gets or sets the XMP metadata container.

Value: The XMP data container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

