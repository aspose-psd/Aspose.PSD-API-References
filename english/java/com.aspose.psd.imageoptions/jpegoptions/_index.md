---
title: JpegOptions
second_title: Aspose.PSD for Java API Reference
description: The jpeg file format create options.
type: docs
weight: 15
url: /java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

The jpeg file format create options.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initializes a new instance of the  JpegOptions  class. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Initializes a new instance of the  JpegOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Clones this instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Gets bits per channel for lossless jpeg image. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | The destination CMYK color profile for CMYK jpeg images. |
| [getColorType()](#getColorType--) | Gets the color type for jpeg image. |
| [getComment()](#getComment--) | Gets the jpeg file comment. |
| [getCompressionType()](#getCompressionType--) | Gets the compression type. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Gets the default memory allocation limit. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getExifData()](#getExifData--) | Get or set exif data container |
| [getFullFrame()](#getFullFrame--) | Gets a value indicating whether [full frame]. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Gets the horizontal subsamplings for each component. |
| [getJfif()](#getJfif--) | Gets the jfif. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Gets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Gets the JPEG-LS interleave mode. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Gets the JPEG-LS preset parameters. |
| [getMultiPageOptions()](#getMultiPageOptions--) | The multipage options |
| [getPalette()](#getPalette--) | Gets or sets the color palette. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Gets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets or sets the progress event handler. |
| [getQuality()](#getQuality--) | Gets image quality. |
| [getRdOptSettings()](#getRdOptSettings--) | Gets the RD optimizer settings. |
| [getResolutionSettings()](#getResolutionSettings--) | Gets or sets the resolution settings. |
| [getResolutionUnit()](#getResolutionUnit--) | Gets the resolution unit. |
| [getRgbColorProfile()](#getRgbColorProfile--) | The destination RGB color profile for CMYK jpeg images. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Gets the sample rounding mode to fit an 8-bit value to an n-bit value. |
| [getScaledQuality()](#getScaledQuality--) | The scaled quality. |
| [getSource()](#getSource--) | Gets or sets the source to create image in. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Gets or sets the vector rasterization options. |
| [getVerticalSampling()](#getVerticalSampling--) | Gets the vertical subsamplings for each component. |
| [getXmpData()](#getXmpData--) | Gets the XMP metadata container. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Sets bits per channel for lossless jpeg image. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | The destination CMYK color profile for CMYK jpeg images. |
| [setColorType(int value)](#setColorType-int-) | Sets the color type for jpeg image. |
| [setComment(String value)](#setComment-java.lang.String-) | Sets the jpeg file comment. |
| [setCompressionType(int value)](#setCompressionType-int-) | Sets the compression type. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Sets the default memory allocation limit. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | Get or set exif data container |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Sets a value indicating whether [full frame]. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Sets the horizontal subsamplings for each component. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Gets or sets a value indicating whether ignore after create event. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | Sets the jfif. |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Sets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification). |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Sets the JPEG-LS interleave mode. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | Sets the JPEG-LS preset parameters. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | The multipage options |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Gets or sets the color palette. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Sets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Gets or sets the progress event handler. |
| [setQuality(int value)](#setQuality-int-) | Sets image quality. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | Sets the RD optimizer settings. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Gets or sets the resolution settings. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Sets the resolution unit. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | The destination RGB color profile for CMYK jpeg images. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Sets the sample rounding mode to fit an 8-bit value to an n-bit value. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Gets or sets the source to create image in. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Gets or sets the vector rasterization options. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Sets the vertical subsamplings for each component. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Sets the XMP metadata container. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initializes a new instance of the  JpegOptions  class.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Initializes a new instance of the  JpegOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | The JPEG options. |

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Gets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel.

**Returns:**
byte
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
### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


The destination CMYK color profile for CMYK jpeg images. Use for saving images. Must be in pair with RGBColorProfile for correct color conversion.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


Gets the color type for jpeg image.

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


Gets the jpeg file comment.

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Gets the compression type.

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Gets the default memory allocation limit.

**Returns:**
int - The default memory allocation limit.
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
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Get or set exif data container

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Gets a value indicating whether [full frame].

Value:  true  if [full frame]; otherwise,  false .

**Returns:**
boolean - a value indicating whether [full frame].
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Gets the horizontal subsamplings for each component.

**Returns:**
byte[]
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Gets the jfif.

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Gets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification).

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Gets the JPEG-LS interleave mode.

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Gets the JPEG-LS preset parameters.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
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
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Gets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Gets or sets the progress event handler.

Value: The progress event handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Gets image quality.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Gets the RD optimizer settings.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Gets or sets the resolution settings.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Gets the resolution unit.

**Returns:**
byte - the resolution unit.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Gets the sample rounding mode to fit an 8-bit value to an n-bit value.  P:JpegOptions.BitsPerChannel 

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


The scaled quality.

**Returns:**
int
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
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Gets the vertical subsamplings for each component.

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets the XMP metadata container.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
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




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Sets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


The destination CMYK color profile for CMYK jpeg images. Use for saving images. Must be in pair with RGBColorProfile for correct color conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Sets the color type for jpeg image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Sets the jpeg file comment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Sets the compression type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Sets the default memory allocation limit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The default memory allocation limit. |

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Get or set exif data container

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

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

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Sets the horizontal subsamplings for each component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

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

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Sets the jfif.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Sets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Sets the JPEG-LS interleave mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Sets the JPEG-LS preset parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

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

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Sets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Sets image quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Sets the RD optimizer settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | The RD optimizer settings. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Gets or sets the resolution settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Sets the resolution unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | the resolution unit. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Sets the sample rounding mode to fit an 8-bit value to an n-bit value.  P:JpegOptions.BitsPerChannel 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Sets the vertical subsamplings for each component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Sets the XMP metadata container.

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

