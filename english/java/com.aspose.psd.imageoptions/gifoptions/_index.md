---
title: GifOptions
second_title: Aspose.PSD for Java API Reference
description: The gif file format creation options.
type: docs
weight: 12
url: /java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

The gif file format creation options.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initializes a new instance of the  GifOptions  class. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | Initializes a new instance of the  GifOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Clones this instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Gets or sets the GIF background color index. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | Gets or sets the GIF color resolution. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Gets or sets a value indicating whether palette correction is applied. |
| [getFullFrame()](#getFullFrame--) | Gets a value indicating whether [full frame]. |
| [getInterlaced()](#getInterlaced--) | True if image should be interlaced. |
| [getMaxDiff()](#getMaxDiff--) | Gets or sets the maximum allowed pixel difference. |
| [getMultiPageOptions()](#getMultiPageOptions--) | The multipage options |
| [getPalette()](#getPalette--) | Gets or sets the color palette. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Gets or sets the GIF pixel aspect ratio. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets or sets the progress event handler. |
| [getResolutionSettings()](#getResolutionSettings--) | Gets or sets the resolution settings. |
| [getSource()](#getSource--) | Gets or sets the source to create image in. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Gets or sets the vector rasterization options. |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata container. |
| [hasTrailer()](#hasTrailer--) | Gets or sets a value indicating whether GIF has trailer. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | Gets or sets a value indicating whether palette entries are sorted. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Gets or sets the GIF background color index. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Gets or sets the GIF color resolution. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Gets or sets a value indicating whether palette correction is applied. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Sets a value indicating whether [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Gets or sets a value indicating whether ignore after create event. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True if image should be interlaced. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Gets or sets the maximum allowed pixel difference. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | The multipage options |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Gets or sets the color palette. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Gets or sets a value indicating whether palette entries are sorted. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Gets or sets the GIF pixel aspect ratio. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Gets or sets the progress event handler. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Gets or sets the resolution settings. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Gets or sets the source to create image in. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Gets or sets a value indicating whether GIF has trailer. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Gets or sets the vector rasterization options. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata container. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Initializes a new instance of the  GifOptions  class.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Initializes a new instance of the  GifOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | The GIF Options. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Gets or sets the GIF background color index.

**Returns:**
byte - The GIF background color index.
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Gets or sets the GIF color resolution.

**Returns:**
byte - The color resolution.

Color Resolution - Number of bits per primary color available to the original image, minus 1. This value represents the size of the entire palette from which the colors in the graphic were selected, not the number of colors actually used in the graphic. For example, if the value in this field is 3, then the palette of the original image had 4 bits per primary color available to create the image. This value should be set to indicate the richness of the original palette, even if not every color from the whole palette is available on the source machine.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Gets or sets a value indicating whether palette correction is applied.

**Returns:**
boolean -  true  if palette correction is applied; otherwise,  false .

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Gets a value indicating whether [full frame].

Value:  true  if [full frame]; otherwise,  false .

**Returns:**
boolean - a value indicating whether [full frame].
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True if image should be interlaced.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used. Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy. It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain. The range of allowed values is [0, 1000].

**Returns:**
int - The range of allowed values.
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Gets or sets the GIF pixel aspect ratio.

Pixel Aspect Ratio - Factor used to compute an approximation of the aspect ratio of the pixel in the original image. If the value of the field is not 0, this approximation of the aspect ratio is computed based on the formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 The Pixel Aspect Ratio is defined to be the quotient of the pixel's width over its height. The value range in this field allows specification of the widest pixel of 4:1 to the tallest pixel of 1:4 in increments of 1/64th. Values : 0 - No aspect ratio information is given. 1..255 - Value used in the computation.

**Returns:**
byte - The GIF pixel aspect ratio.
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Gets or sets a value indicating whether GIF has trailer.

**Returns:**
boolean -  true  if GIF has trailer; otherwise,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Gets or sets a value indicating whether palette entries are sorted.

**Returns:**
boolean -  true  if palette entries are sorted; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Gets or sets the GIF background color index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The GIF background color index. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Gets or sets the GIF color resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The color resolution.

Color Resolution - Number of bits per primary color available to the original image, minus 1. This value represents the size of the entire palette from which the colors in the graphic were selected, not the number of colors actually used in the graphic. For example, if the value in this field is 3, then the palette of the original image had 4 bits per primary color available to create the image. This value should be set to indicate the richness of the original palette, even if not every color from the whole palette is available on the source machine. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Gets or sets a value indicating whether palette correction is applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if palette correction is applied; otherwise,  false .

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True if image should be interlaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used. Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy. It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain. The range of allowed values is [0, 1000].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The range of allowed values. |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Gets or sets a value indicating whether palette entries are sorted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if palette entries are sorted; otherwise,  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Gets or sets the GIF pixel aspect ratio.

Pixel Aspect Ratio - Factor used to compute an approximation of the aspect ratio of the pixel in the original image. If the value of the field is not 0, this approximation of the aspect ratio is computed based on the formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 The Pixel Aspect Ratio is defined to be the quotient of the pixel's width over its height. The value range in this field allows specification of the widest pixel of 4:1 to the tallest pixel of 1:4 in increments of 1/64th. Values : 0 - No aspect ratio information is given. 1..255 - Value used in the computation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The GIF pixel aspect ratio. |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Gets or sets a value indicating whether GIF has trailer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if GIF has trailer; otherwise,  false . |

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | The XMP data container. |

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

