---
title: TiffOptions
second_title: Aspose.PSD for Java API Reference
description: The tiff file format options.
type: docs
weight: 25
url: /java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

The tiff file format options. Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly. Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

  WARNING! never modify tiff options during save since this may cause side effects and hard to find bugs. The following line was specially left commented since it caused incorrect determination of data beginning. The passed options did not contain spp (although the options are not correct in such case but still this scenario causes errors) and the next line caused +spp tag +bpp tag added and when options were written after data completely written they have overwritten the data beginning for uncompressed codec!!! See TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;  
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Initializes a new instance of the  TiffOptions  class. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Initializes a new instance of the  TiffOptions  class. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Initializes a new instance of the  TiffOptions  class. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Initializes a new instance of the  TiffOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Adds a new tag. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Adds the tags. |
| [clone()](#clone--) |  |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Clones this instance. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Gets or sets the alpha storage option. |
| [getArtist()](#getArtist--) | Gets or sets the artist. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Gets or sets the color of the background. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the bits per pixel. |
| [getBitsPerSample()](#getBitsPerSample--) | Gets the bits per sample. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [getByteOrder()](#getByteOrder--) | Gets or sets a value indicating the tiff byte order. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Gets the cache. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Gets or sets the color map. |
| [getCompressedQuality()](#getCompressedQuality--) | Gets compressed image quality. |
| [getCompression()](#getCompression--) | Gets the compression. |
| [getCopyright()](#getCopyright--) | Gets the copyright. |
| [getDateTime()](#getDateTime--) | Gets or sets the date and time. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Gets or sets the default memory allocation limit. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getDocumentName()](#getDocumentName--) | Gets or sets the name of the document. |
| [getExifIfd()](#getExifIfd--) | Gets or sets the pointer to EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Gets the extra sample count. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Gets the extra samples values. |
| [getFaxT4Options()](#getFaxT4Options--) | Gets or sets the fax t4 options. |
| [getFileStandard()](#getFileStandard--) | Gets or sets the TIFF file standard. |
| [getFillOrder()](#getFillOrder--) | Gets or sets the byte bits fill order. |
| [getFullFrame()](#getFullFrame--) | Gets a value indicating whether [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | Gets or sets the halftone hints. |
| [getIccProfile()](#getIccProfile--) | Gets the icc profile stream. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getImageDescription()](#getImageDescription--) | Gets or sets the image description. |
| [getImageLength()](#getImageLength--) | Gets or sets the image length. |
| [getImageWidth()](#getImageWidth--) | Gets or sets the image width. |
| [getInkNames()](#getInkNames--) | Gets or sets the ink names. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Gets or sets the max sample value. |
| [getMinSampleValue()](#getMinSampleValue--) | Gets or sets the min sample value. |
| [getMultiPageOptions()](#getMultiPageOptions--) | The multipage options |
| [getOrientation()](#getOrientation--) | Gets or sets the orientation. |
| [getPageName()](#getPageName--) | Gets or sets the page name. |
| [getPageNumber()](#getPageNumber--) | Gets or sets the page number tag. |
| [getPalette()](#getPalette--) | Gets or sets the color palette. |
| [getPhotometric()](#getPhotometric--) | Gets or sets the photometric. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Gets or sets the planar configuration. |
| [getPredictor()](#getPredictor--) | Gets or sets the predictor for LZW compression. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Gets or sets a value indicating whether components must be premultiplied. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Gets or sets the progress event handler. |
| [getResolutionSettings()](#getResolutionSettings--) | Gets or sets the resolution settings. |
| [getResolutionUnit()](#getResolutionUnit--) | Gets or sets the resolution unit. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Gets or sets the rows per strip. |
| [getSampleFormat()](#getSampleFormat--) | Gets or sets the sample format. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Gets the samples per pixel. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Gets or sets the scanner manufacturer. |
| [getScannerModel()](#getScannerModel--) | Gets or sets the scanner model. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Gets or sets the max sample value. |
| [getSminSampleValue()](#getSminSampleValue--) | Gets or sets the min sample value. |
| [getSoftwareType()](#getSoftwareType--) | Gets or sets the software type. |
| [getSource()](#getSource--) | Gets or sets the source to create image in. |
| [getStripByteCounts()](#getStripByteCounts--) | Gets or sets the strip byte counts. |
| [getStripOffsets()](#getStripOffsets--) | Gets or sets the strip offsets. |
| [getSubFileType()](#getSubFileType--) | Gets or sets a general indication of the kind of data contained in this subfile. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Gets the instance of the tag by type. |
| [getTags()](#getTags--) | Gets or sets the tags. |
| [getTargetPrinter()](#getTargetPrinter--) | Gets or sets the target printer. |
| [getThreshholding()](#getThreshholding--) | Gets or sets the threshholding. |
| [getTileByteCounts()](#getTileByteCounts--) | Gets or sets the tile byte counts. |
| [getTileLength()](#getTileLength--) | Gets ot sets tile length. |
| [getTileOffsets()](#getTileOffsets--) | Gets or sets the tile offsets. |
| [getTileWidth()](#getTileWidth--) | Gets ot sets tile width. |
| [getTotalPages()](#getTotalPages--) | Gets the total pages. |
| [getValidTagCount()](#getValidTagCount--) | Gets the valid tag count. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Gets the valid tags count. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Gets or sets the vector rasterization options. |
| [getXPAuthor()](#getXPAuthor--) | Gets image author, which used by Windows Explorer. |
| [getXPComment()](#getXPComment--) | Gets comment on image, which used by Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Gets subject image, which used by Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Gets information about image, which used by Windows Explorer. |
| [getXPTitle()](#getXPTitle--) | Gets information about image, which used by Windows Explorer. |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata container. |
| [getXposition()](#getXposition--) | Gets or sets the x position. |
| [getXresolution()](#getXresolution--) | Gets or sets the x resolution. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Gets or sets the YCbCrCoefficients. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Gets or sets the subsampling factors for YCbCr photometric. |
| [getYposition()](#getYposition--) | Gets or sets the y position. |
| [getYresolution()](#getYresolution--) | Gets or sets the y resolution. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Gets a value indicating whether the extra samples is present. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Determines whether tag is present in the options or not. |
| [isTiled()](#isTiled--) | Gets a value indicating whether image is tiled. |
| [isValid()](#isValid--) | Gets a value indicating whether the  TiffOptions  have been properly configured. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Removes the tag. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Gets or sets the alpha storage option. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Gets or sets the artist. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Gets or sets the color of the background. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Sets the bits per sample. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [setByteOrder(int value)](#setByteOrder-int-) | Gets or sets a value indicating the tiff byte order. |
| [setColorMap(int[] value)](#setColorMap-int---) | Gets or sets the color map. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Sets compressed image quality. |
| [setCompression(int value)](#setCompression-int-) | Sets the compression. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Sets the copyright. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Gets or sets the date and time. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Gets or sets the default memory allocation limit. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Gets or sets the name of the document. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Sets the extra samples values. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Gets or sets the fax t4 options. |
| [setFileStandard(int value)](#setFileStandard-int-) | Gets or sets the TIFF file standard. |
| [setFillOrder(int value)](#setFillOrder-int-) | Gets or sets the byte bits fill order. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Sets a value indicating whether [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Gets or sets the halftone hints. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Sets the icc profile stream. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Gets or sets a value indicating whether ignore after create event. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Gets or sets the image description. |
| [setImageLength(long value)](#setImageLength-long-) | Gets or sets the image length. |
| [setImageWidth(long value)](#setImageWidth-long-) | Gets or sets the image width. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Gets or sets the ink names. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Gets or sets the max sample value. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Gets or sets the min sample value. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | The multipage options |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the orientation. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Gets or sets the page name. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Gets or sets the page number tag. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Gets or sets the color palette. |
| [setPhotometric(int value)](#setPhotometric-int-) | Gets or sets the photometric. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Gets or sets the planar configuration. |
| [setPredictor(int value)](#setPredictor-int-) | Gets or sets the predictor for LZW compression. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Gets or sets a value indicating whether components must be premultiplied. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Gets or sets the progress event handler. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Gets or sets the resolution settings. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Gets or sets the resolution unit. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Gets or sets the rows per strip. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Gets or sets the sample format. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Gets or sets the scanner manufacturer. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Gets or sets the scanner model. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Gets or sets the max sample value. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Gets or sets the min sample value. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Gets or sets the software type. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Gets or sets the source to create image in. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Gets or sets the strip byte counts. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Gets or sets the strip offsets. |
| [setSubFileType(long value)](#setSubFileType-long-) | Gets or sets a general indication of the kind of data contained in this subfile. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Gets or sets the tags. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Gets or sets the target printer. |
| [setThreshholding(int value)](#setThreshholding-int-) | Gets or sets the threshholding. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Gets or sets the tile byte counts. |
| [setTileLength(long value)](#setTileLength-long-) | Gets ot sets tile length. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Gets or sets the tile offsets. |
| [setTileWidth(long value)](#setTileWidth-long-) | Gets ot sets tile width. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Gets or sets the vector rasterization options. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Sets image author, which used by Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Sets comment on image, which used by Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Sets subject image, which used by Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Sets information about image, which used by Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Sets information about image, which used by Windows Explorer. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata container. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the x position. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the x resolution. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Gets or sets the YCbCrCoefficients. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Gets or sets the subsampling factors for YCbCr photometric. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the y position. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Gets or sets the y resolution. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Validates if options have valid combination of tags |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Initializes a new instance of the  TiffOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| expectedFormat | int | The expected tiff file format. |
| byteOrder | int | The tiff file format byte order to use. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Initializes a new instance of the  TiffOptions  class. By default little endian convention is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| expectedFormat | int | The expected tiff file format. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Initializes a new instance of the  TiffOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | The options to copy from. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Initializes a new instance of the  TiffOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | The tags to initialize options with. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Adds a new tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | The tag to add. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Adds the tags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | The tags to add. |

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Gets or sets the alpha storage option. Options other than  TiffAlphaStorage.Unspecified  are used when there are more than 3  SamplesPerPixel  defined.

**Returns:**
int - The alpha storage option.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Gets or sets the artist.

**Returns:**
java.lang.String - The artist.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Gets or sets the color of the background. Used for internal purposes to store image's backround color.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the bits per pixel.

**Returns:**
int - The bits per pixel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Gets the bits per sample.

**Returns:**
int[] - The bits per sample value.

When setting this value keep in mind that it will also set SamplesPerPixel value to array length. These 2 properties are very tightly coupled so may be set alltogether only.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.

Value: The buffer size hint, in megabytes. Non-positive value means no memory limitation for internal buffers

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Gets or sets a value indicating the tiff byte order.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Gets the cache.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | int | The tag (which is an array type). |

**Returns:**
long[] - The tag value.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Gets or sets the color map.

**Returns:**
int[] - The color map.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Gets compressed image quality. Used with the Jpeg compression.

**Returns:**
int - compressed image quality.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Gets the compression.

**Returns:**
int - The compression.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Gets the copyright.

**Returns:**
java.lang.String - The copyright.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Gets or sets the date and time.

**Returns:**
java.lang.String - The date and time.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Gets or sets the default memory allocation limit.

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
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Gets or sets the name of the document.

**Returns:**
java.lang.String - The name of the document.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Gets or sets the pointer to EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Gets the extra sample count.

Value: The extra sample count.

**Returns:**
long - the extra sample count.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Gets the extra samples values.

Value: The extra samples value.

**Returns:**
int[] - the extra samples values.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Gets or sets the fax t4 options.

**Returns:**
long - The fax t4 options.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Gets or sets the TIFF file standard.

**Returns:**
int - The TIFF file standard.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Gets or sets the byte bits fill order.

**Returns:**
int - The byte bits fill order.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Gets a value indicating whether [full frame].

Value:  true  if [full frame]; otherwise,  false .

**Returns:**
boolean - a value indicating whether [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Gets or sets the halftone hints.

**Returns:**
int[] - The halftone hints.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Gets the icc profile stream.

**Returns:**
byte[] - The icc profile.
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Gets or sets the image description.

**Returns:**
java.lang.String - The image description.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Gets or sets the image length.

**Returns:**
long - The image length.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Gets or sets the image width.

**Returns:**
long - The image width.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Gets or sets the ink names.

**Returns:**
java.lang.String - The ink names.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Gets or sets the max sample value.

**Returns:**
int[] - The max sample value.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Gets or sets the min sample value.

**Returns:**
int[] - The min sample value.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


The multipage options

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Gets or sets the orientation.

**Returns:**
int - The orientation.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Gets or sets the page name.

**Returns:**
java.lang.String - The page name.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Gets or sets the page number tag.

**Returns:**
int[] - The page number tag.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Gets or sets the color palette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Gets or sets the photometric.

**Returns:**
int - The photometric.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Gets or sets the planar configuration.

**Returns:**
int - The planar configuration.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Gets or sets the predictor for LZW compression.

**Returns:**
int - The predictor type.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Gets or sets a value indicating whether components must be premultiplied.

**Returns:**
boolean -  true  if components must be premultiplied; otherwise,  false .
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
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Gets or sets the resolution unit.

**Returns:**
int - The resolution unit.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Gets or sets the rows per strip.

**Returns:**
long - The rows per strip.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Gets or sets the sample format.

**Returns:**
int[] - The sample format.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Gets the samples per pixel. To change this property value use the  BitsPerSample  property setter.

**Returns:**
int - The samples per pixel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Gets or sets the scanner manufacturer.

**Returns:**
java.lang.String - The scanner manufacturer.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Gets or sets the scanner model.

**Returns:**
java.lang.String - The scanner model.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).

**Returns:**
long[] - The max sample value.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).

**Returns:**
long[] - The min sample value.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Gets or sets the software type.

**Returns:**
java.lang.String - The software type.
### getSource() {#getSource--}
```
public final Source getSource()
```


Gets or sets the source to create image in.

Value: The source to create image in.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Gets or sets the strip byte counts.

**Returns:**
long[] - The strip byte counts.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Gets or sets the strip offsets.

**Returns:**
long[] - The strip offsets.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Gets or sets a general indication of the kind of data contained in this subfile.

**Returns:**
long - The general indication of the kind of data contained in this subfile.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Gets the instance of the tag by type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagKey | int | The tag key. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Gets or sets the tags.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - The tags.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Gets or sets the target printer.

**Returns:**
java.lang.String - The target printer.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Gets or sets the threshholding.

**Returns:**
int - The threshholding.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Gets or sets the tile byte counts.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Gets ot sets tile length.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Gets or sets the tile offsets.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Gets ot sets tile width.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Gets the total pages.

**Returns:**
int - The total pages.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Gets the valid tag count. This is not the total tags count but the number of tags which may be preserved.

**Returns:**
int - The valid tag count.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Gets the valid tags count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | The tags to validate. |

**Returns:**
int - The valid tags count.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Gets or sets the vector rasterization options.

Value: The vector rasterization options.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Gets image author, which used by Windows Explorer.

Value: Image Author, used by Windows Explorer. The  XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) is ignored by Windows Explorer if the  Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) tag exists.

**Returns:**
java.lang.String - image author, which used by Windows Explorer.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Gets comment on image, which used by Windows Explorer.

Value: Comment on image, used by Windows Explorer.

**Returns:**
java.lang.String - comment on image, which used by Windows Explorer.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Gets subject image, which used by Windows Explorer.

Value: Subject image, used by Windows Explorer.

**Returns:**
java.lang.String - subject image, which used by Windows Explorer.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Gets information about image, which used by Windows Explorer.

Value: Information about image, used by Windows Explorer.

**Returns:**
java.lang.String - information about image, which used by Windows Explorer.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Gets information about image, which used by Windows Explorer.

Value: Information about image, used by Windows Explorer. The  XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) is ignored by Windows Explorer if the  ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) tag exists.

**Returns:**
java.lang.String - information about image, which used by Windows Explorer.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets or sets the XMP metadata container.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Gets or sets the x position.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Gets or sets the x resolution.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Gets or sets the YCbCrCoefficients.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - The YCbCrCoefficients.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Gets or sets the subsampling factors for YCbCr photometric.

**Returns:**
int[] - The subsampling factors for YCbCr photometric.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Gets or sets the y position.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Gets or sets the y resolution.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Gets a value indicating whether the extra samples is present.

**Returns:**
boolean -  true  if the extra samples is present; otherwise,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Determines whether tag is present in the options or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | int | The tag id to check. |

**Returns:**
boolean -  true  if tag is present; otherwise,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Gets a value indicating whether image is tiled.

**Returns:**
boolean -  true  if image is tiled; otherwise,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Gets a value indicating whether the  TiffOptions  have been properly configured. Use Validate method as to find the failure reason.

**Returns:**
boolean -  true  if TiffOptions are properly configured; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Removes the tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | int | The tag to remove. |

**Returns:**
boolean - true if successfully removed
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Gets or sets the alpha storage option. Options other than  TiffAlphaStorage.Unspecified  are used when there are more than 3  SamplesPerPixel  defined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The alpha storage option. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Gets or sets the artist.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The artist. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Gets or sets the color of the background. Used for internal purposes to store image's backround color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | The color of the background. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Sets the bits per sample.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The bits per sample value.

When setting this value keep in mind that it will also set SamplesPerPixel value to array length. These 2 properties are very tightly coupled so may be set alltogether only. |

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

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Gets or sets a value indicating the tiff byte order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Gets or sets the color map.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The color map. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Sets compressed image quality. Used with the Jpeg compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | compressed image quality. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Sets the compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The compression. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Sets the copyright.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The copyright. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Gets or sets the date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The date and time. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Gets or sets the default memory allocation limit.

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

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Gets or sets the name of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the document. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Sets the extra samples values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The extra samples value. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Gets or sets the fax t4 options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The fax t4 options. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Gets or sets the TIFF file standard.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The TIFF file standard. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Gets or sets the byte bits fill order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The byte bits fill order. |

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

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Gets or sets the halftone hints.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The halftone hints. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Sets the icc profile stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The icc profile. |

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

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Gets or sets the image description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The image description. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Gets or sets the image length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The image length. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Gets or sets the image width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The image width. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Gets or sets the ink names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The ink names. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Gets or sets the max sample value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The max sample value. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Gets or sets the min sample value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The min sample value. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


The multipage options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Gets or sets the orientation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The orientation. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Gets or sets the page name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The page name. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Gets or sets the page number tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The page number tag. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Gets or sets the color palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Gets or sets the photometric.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The photometric. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Gets or sets the planar configuration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The planar configuration. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Gets or sets the predictor for LZW compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The predictor type. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Gets or sets a value indicating whether components must be premultiplied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if components must be premultiplied; otherwise,  false . |

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

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Gets or sets the resolution unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The resolution unit. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Gets or sets the rows per strip.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The rows per strip. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Gets or sets the sample format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The sample format. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Gets or sets the scanner manufacturer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The scanner manufacturer. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Gets or sets the scanner model.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The scanner model. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | The max sample value. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | The min sample value. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Gets or sets the software type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The software type. |

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

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Gets or sets the strip byte counts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | The strip byte counts. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Gets or sets the strip offsets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] | The strip offsets. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Gets or sets a general indication of the kind of data contained in this subfile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The general indication of the kind of data contained in this subfile. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Gets or sets the tags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | The tags. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Gets or sets the target printer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The target printer. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Gets or sets the threshholding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The threshholding. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Gets or sets the tile byte counts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Gets ot sets tile length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Gets or sets the tile offsets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Gets ot sets tile width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

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

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Sets image author, which used by Windows Explorer.

Value: Image Author, used by Windows Explorer. The  XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) is ignored by Windows Explorer if the  Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) tag exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | image author, which used by Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Sets comment on image, which used by Windows Explorer.

Value: Comment on image, used by Windows Explorer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | comment on image, which used by Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Sets subject image, which used by Windows Explorer.

Value: Subject image, used by Windows Explorer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | subject image, which used by Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Sets information about image, which used by Windows Explorer.

Value: Information about image, used by Windows Explorer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | information about image, which used by Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Sets information about image, which used by Windows Explorer.

Value: Information about image, used by Windows Explorer. The  XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) is ignored by Windows Explorer if the  ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) tag exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | information about image, which used by Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Gets or sets the XMP metadata container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | The XMP data container. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Gets or sets the x position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | The x position. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Gets or sets the x resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | The x resolution. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Gets or sets the YCbCrCoefficients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | The YCbCrCoefficients. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Gets or sets the subsampling factors for YCbCr photometric.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The subsampling factors for YCbCr photometric. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Gets or sets the y position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | The y position. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Gets or sets the y resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | The y resolution. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


Validates if options have valid combination of tags

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

