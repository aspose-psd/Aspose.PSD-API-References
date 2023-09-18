---
title: BmpOptions
second_title: Aspose.PSD for Java API Reference
description: The bmp file format creation options.
type: docs
weight: 10
url: /java/com.aspose.psd.imageoptions/bmpoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

The bmp file format creation options.
## Constructors

| Constructor | Description |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Initializes a new instance of the  BmpOptions  class. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.psd.imageoptions.BmpOptions-) | Initializes a new instance of the  BmpOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Clones this instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets or sets the image bits per pixel count. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getClass()](#getClass--) |  |
| [getCompression()](#getCompression--) | Gets or sets the compression. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getFullFrame()](#getFullFrame--) | Gets a value indicating whether [full frame]. |
| [getMultiPageOptions()](#getMultiPageOptions--) | The multipage options |
| [getPalette()](#getPalette--) | Gets or sets the color palette. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets or sets the progress event handler. |
| [getResolutionSettings()](#getResolutionSettings--) | Gets or sets the resolution settings. |
| [getSource()](#getSource--) | Gets or sets the source to create image in. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Gets or sets the vector rasterization options. |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata container. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Gets or sets the image bits per pixel count. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setCompression(long value)](#setCompression-long-) | Gets or sets the compression. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Sets a value indicating whether [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Gets or sets a value indicating whether ignore after create event. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | The multipage options |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Gets or sets the color palette. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Gets or sets the progress event handler. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Gets or sets the resolution settings. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Gets or sets the source to create image in. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Gets or sets the vector rasterization options. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata container. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


Initializes a new instance of the  BmpOptions  class.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.psd.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Initializes a new instance of the  BmpOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.psd.imageoptions/bmpoptions) | The BMP options. |

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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets or sets the image bits per pixel count.

**Returns:**
int - The image bits per pixel count.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompression() {#getCompression--}
```
public long getCompression()
```


Gets or sets the compression.

**Returns:**
long - The compression.
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
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Gets or sets the color palette.

Value: The color palette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
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
### getSource() {#getSource--}
```
public final Source getSource()
```


Gets or sets the source to create image in.

Value: The source to create image in.

**Returns:**
[Source](../../com.aspose.psd/source)
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




### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Gets or sets the image bits per pixel count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The image bits per pixel count. |

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

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Gets or sets the compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The compression. |

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

