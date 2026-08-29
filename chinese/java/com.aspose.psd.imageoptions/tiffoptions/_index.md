---
title: "TiffOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "TIFF 文件格式选项。"
type: docs
weight: 25
url: /zh/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

tiff 文件格式选项。请注意，宽度和高度标签将在图像创建时被宽度和高度参数覆盖，因此无需直接指定它们。请注意，许多选项会返回默认值，但这并不意味着该选项已显式设置为标签值。要验证标签是否存在，请使用 Tags 属性或相应的 IsTagPresent 方法。

警告！在保存期间切勿修改 tiff 选项，因为这可能导致副作用并产生难以发现的错误。以下行被特意保留为注释，因为它导致了数据起始位置的错误判断。传入的选项未包含 spp（虽然在这种情况下选项本身不正确，但仍会导致错误），下一行导致添加了 +spp 标签和 +bpp 标签，并且当选项在数据完全写入后再写入时，它们会覆盖未压缩编解码器的数据起始位置！！！请参阅 TiffUncompressedCodec.Encode。this.Options.SamplesPerPixel = 3;
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | 初始化 TiffOptions 类的新实例。 |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | 初始化 TiffOptions 类的新实例。 |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | 初始化 TiffOptions 类的新实例。 |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | 初始化 TiffOptions 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | 添加新标签。 |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 添加标签。 |
| [clone()](#clone--) |  |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [deepClone()](#deepClone--) | 克隆此实例。 |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | 获取或设置 alpha 存储选项。 |
| [getArtist()](#getArtist--) | 获取或设置艺术家。 |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | 获取或设置背景颜色。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取每像素位数。 |
| [getBitsPerSample()](#getBitsPerSample--) | 获取每个样本的位数。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getByteOrder()](#getByteOrder--) | 获取或设置指示 TIFF 字节顺序的值。 |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | 获取缓存。 |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | 获取或设置颜色映射。 |
| [getCompressedQuality()](#getCompressedQuality--) | 获取压缩图像质量。 |
| [getCompression()](#getCompression--) | 获取压缩方式。 |
| [getCopyright()](#getCopyright--) | 获取版权信息。 |
| [getDateTime()](#getDateTime--) | 获取或设置日期和时间。 |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | 获取或设置默认内存分配限制。 |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getDocumentName()](#getDocumentName--) | 获取或设置文档名称。 |
| [getExifIfd()](#getExifIfd--) | 获取或设置指向 EXIF IFD 的指针。 |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | 获取额外样本计数。 |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | 获取额外样本值。 |
| [getFaxT4Options()](#getFaxT4Options--) | 获取或设置传真 T4 选项。 |
| [getFileStandard()](#getFileStandard--) | 获取或设置 TIFF 文件标准。 |
| [getFillOrder()](#getFillOrder--) | 获取或设置字节位填充顺序。 |
| [getFullFrame()](#getFullFrame--) | 获取一个值，指示是否为 [full frame]。 |
| [getHalfToneHints()](#getHalfToneHints--) | 获取或设置半色调提示。 |
| [getIccProfile()](#getIccProfile--) | 获取 ICC 配置文件流。 |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 获取或设置一个值，指示在创建事件后是否忽略。 |
| [getImageDescription()](#getImageDescription--) | 获取或设置图像描述。 |
| [getImageLength()](#getImageLength--) | 获取或设置图像长度。 |
| [getImageWidth()](#getImageWidth--) | 获取或设置图像宽度。 |
| [getInkNames()](#getInkNames--) | 获取或设置墨水名称。 |
| [getMaxSampleValue()](#getMaxSampleValue--) | 获取或设置最大样本值。 |
| [getMinSampleValue()](#getMinSampleValue--) | 获取或设置最小样本值。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | 多页选项 |
| [getOrientation()](#getOrientation--) | 获取或设置方向。 |
| [getPageName()](#getPageName--) | 获取或设置页面名称。 |
| [getPageNumber()](#getPageNumber--) | 获取或设置页码标签。 |
| [getPalette()](#getPalette--) | 获取或设置颜色调色板。 |
| [getPhotometric()](#getPhotometric--) | 获取或设置光度。 |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | 获取或设置平面配置。 |
| [getPredictor()](#getPredictor--) | 获取或设置 LZW 压缩的预测器。 |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | 获取或设置指示组件是否必须预乘的值。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取或设置进度事件处理程序。 |
| [getResolutionSettings()](#getResolutionSettings--) | 获取或设置分辨率设置。 |
| [getResolutionUnit()](#getResolutionUnit--) | 获取或设置分辨率单位。 |
| [getRowsPerStrip()](#getRowsPerStrip--) | 获取或设置每条带的行数。 |
| [getSampleFormat()](#getSampleFormat--) | 获取或设置样本格式。 |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | 获取每像素的样本数。 |
| [getScannerManufacturer()](#getScannerManufacturer--) | 获取或设置扫描仪制造商。 |
| [getScannerModel()](#getScannerModel--) | 获取或设置扫描仪型号。 |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | 获取或设置最大样本值。 |
| [getSminSampleValue()](#getSminSampleValue--) | 获取或设置最小样本值。 |
| [getSoftwareType()](#getSoftwareType--) | 获取或设置软件类型。 |
| [getSource()](#getSource--) | 获取或设置用于创建图像的源。 |
| [getStripByteCounts()](#getStripByteCounts--) | 获取或设置条带字节计数。 |
| [getStripOffsets()](#getStripOffsets--) | 获取或设置条带偏移。 |
| [getSubFileType()](#getSubFileType--) | 获取或设置此子文件中包含的数据类型的一般指示。 |
| [getTagByType(int tagKey)](#getTagByType-int-) | 按类型获取标签的实例。 |
| [getTags()](#getTags--) | 获取或设置标签。 |
| [getTargetPrinter()](#getTargetPrinter--) | 获取或设置目标打印机。 |
| [getThreshholding()](#getThreshholding--) | 获取或设置阈值化。 |
| [getTileByteCounts()](#getTileByteCounts--) | 获取或设置瓦片字节计数。 |
| [getTileLength()](#getTileLength--) | 获取或设置瓦片长度。 |
| [getTileOffsets()](#getTileOffsets--) | 获取或设置瓦片偏移。 |
| [getTileWidth()](#getTileWidth--) | 获取或设置瓦片宽度。 |
| [getTotalPages()](#getTotalPages--) | 获取总页数。 |
| [getValidTagCount()](#getValidTagCount--) | 获取有效标签计数。 |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | 获取有效标签的计数。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 获取或设置矢量光栅化选项。 |
| [getXPAuthor()](#getXPAuthor--) | 获取图像作者，Windows 资源管理器使用。 |
| [getXPComment()](#getXPComment--) | 获取图像注释，Windows 资源管理器使用。 |
| [getXPKeywords()](#getXPKeywords--) | 获取图像主题，Windows 资源管理器使用。 |
| [getXPSubject()](#getXPSubject--) | 获取图像信息，供 Windows Explorer 使用。 |
| [getXPTitle()](#getXPTitle--) | 获取图像信息，供 Windows Explorer 使用。 |
| [getXmpData()](#getXmpData--) | 获取或设置 XMP 元数据容器。 |
| [getXposition()](#getXposition--) | 获取或设置 x 位置。 |
| [getXresolution()](#getXresolution--) | 获取或设置 X 分辨率。 |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | 获取或设置 YCbCrCoefficients。 |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | 获取或设置 YCbCr 光度的子采样因子。 |
| [getYposition()](#getYposition--) | 获取或设置 y 位置。 |
| [getYresolution()](#getYresolution--) | 获取或设置 Y 分辨率。 |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | 获取一个值，指示是否存在额外样本。 |
| [isTagPresent(int tag)](#isTagPresent-int-) | 确定选项中是否存在标签。 |
| [isTiled()](#isTiled--) | 获取一个值，指示图像是否为平铺。 |
| [isValid()](#isValid--) | 获取一个值，指示 TiffOptions 是否已正确配置。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | 移除标签。 |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | 获取或设置 alpha 存储选项。 |
| [setArtist(String value)](#setArtist-java.lang.String-) | 获取或设置艺术家。 |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | 获取或设置背景颜色。 |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | 设置每个样本的位数。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setByteOrder(int value)](#setByteOrder-int-) | 获取或设置指示 TIFF 字节顺序的值。 |
| [setColorMap(int[] value)](#setColorMap-int---) | 获取或设置颜色映射。 |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | 设置压缩图像质量。 |
| [setCompression(int value)](#setCompression-int-) | 设置压缩方式。 |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 设置版权信息。 |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | 获取或设置日期和时间。 |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | 获取或设置默认内存分配限制。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。 |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | 获取或设置文档名称。 |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | 设置额外样本的值。 |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | 获取或设置传真 T4 选项。 |
| [setFileStandard(int value)](#setFileStandard-int-) | 获取或设置 TIFF 文件标准。 |
| [setFillOrder(int value)](#setFillOrder-int-) | 获取或设置字节位填充顺序。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 设置一个值，指示是否为 [full frame]。 |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | 获取或设置半色调提示。 |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | 设置 ICC 配置文件流。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 获取或设置一个值，指示在创建事件后是否忽略。 |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | 获取或设置图像描述。 |
| [setImageLength(long value)](#setImageLength-long-) | 获取或设置图像长度。 |
| [setImageWidth(long value)](#setImageWidth-long-) | 获取或设置图像宽度。 |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | 获取或设置墨水名称。 |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | 获取或设置最大样本值。 |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | 获取或设置最小样本值。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | 多页选项 |
| [setOrientation(int value)](#setOrientation-int-) | 获取或设置方向。 |
| [setPageName(String value)](#setPageName-java.lang.String-) | 获取或设置页面名称。 |
| [setPageNumber(int[] value)](#setPageNumber-int---) | 获取或设置页码标签。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 获取或设置颜色调色板。 |
| [setPhotometric(int value)](#setPhotometric-int-) | 获取或设置光度。 |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | 获取或设置平面配置。 |
| [setPredictor(int value)](#setPredictor-int-) | 获取或设置 LZW 压缩的预测器。 |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | 获取或设置指示组件是否必须预乘的值。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 获取或设置进度事件处理程序。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 获取或设置分辨率设置。 |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | 获取或设置分辨率单位。 |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | 获取或设置每条带的行数。 |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | 获取或设置样本格式。 |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | 获取或设置扫描仪制造商。 |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | 获取或设置扫描仪型号。 |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | 获取或设置最大样本值。 |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | 获取或设置最小样本值。 |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | 获取或设置软件类型。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 获取或设置用于创建图像的源。 |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | 获取或设置条带字节计数。 |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | 获取或设置条带偏移。 |
| [setSubFileType(long value)](#setSubFileType-long-) | 获取或设置此子文件中包含的数据类型的一般指示。 |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 获取或设置标签。 |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | 获取或设置目标打印机。 |
| [setThreshholding(int value)](#setThreshholding-int-) | 获取或设置阈值化。 |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | 获取或设置瓦片字节计数。 |
| [setTileLength(long value)](#setTileLength-long-) | 获取或设置瓦片长度。 |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | 获取或设置瓦片偏移。 |
| [setTileWidth(long value)](#setTileWidth-long-) | 获取或设置瓦片宽度。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 获取或设置矢量光栅化选项。 |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | 设置图像作者，供 Windows Explorer 使用。 |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | 设置图像注释，供 Windows Explorer 使用。 |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | 设置图像主题，供 Windows Explorer 使用。 |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | 设置图像信息，供 Windows Explorer 使用。 |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | 设置图像信息，供 Windows Explorer 使用。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | 获取或设置 XMP 元数据容器。 |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 x 位置。 |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 X 分辨率。 |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | 获取或设置 YCbCrCoefficients。 |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | 获取或设置 YCbCr 光度的子采样因子。 |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 y 位置。 |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | 获取或设置 Y 分辨率。 |
| [toString()](#toString--) |  |
| [validate()](#validate--) | 验证选项是否具有有效的标签组合。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


初始化 TiffOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| expectedFormat | int | 预期的 tiff 文件格式。 |
| byteOrder | int | 要使用的 TIFF 文件格式字节序。 |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


初始化 TiffOptions 类的新实例。默认使用小端字节序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| expectedFormat | int | 预期的 tiff 文件格式。 |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


初始化 TiffOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | 要复制的选项。 |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


初始化 TiffOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 用于初始化选项的标签。 |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


添加新标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 要添加的标签。 |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


添加标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 要添加的标签。 |

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


实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。此方法仅调用 dispose 方法。

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


克隆此实例。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


克隆此实例。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


释放当前实例。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


获取或设置 alpha 存储选项。当定义的 SamplesPerPixel 超过 3 时，除 TiffAlphaStorage.Unspecified 之外的选项将被使用。

**Returns:**
int - alpha 存储选项。
### getArtist() {#getArtist--}
```
public String getArtist()
```


获取或设置艺术家。

**Returns:**
java.lang.String - 艺术家。
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


获取或设置背景颜色。用于内部存储图像的背景颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取每像素位数。

**Returns:**
int - 每像素的位数。
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


获取每个样本的位数。

**Returns:**
int[] - 每个样本的位数值。

设置此值时请记住，它还会将 SamplesPerPixel 的值设为数组长度。这两个属性紧密耦合，因而只能一起设置。
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


获取或设置指示 TIFF 字节顺序的值。

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


获取缓存。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 标签 | int | 标签（数组类型）。 |

**Returns:**
long[] - 标签值。
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


获取或设置颜色映射。

**Returns:**
int[] - 颜色映射表。
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


获取压缩图像质量。与 Jpeg 压缩一起使用。

**Returns:**
int - 压缩图像质量。
### getCompression() {#getCompression--}
```
public int getCompression()
```


获取压缩方式。

**Returns:**
int - 压缩方式。
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


获取版权信息。

**Returns:**
java.lang.String - 版权信息。
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


获取或设置日期和时间。

**Returns:**
java.lang.String - 日期和时间。
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


获取或设置默认内存分配限制。

**Returns:**
int - 默认内存分配限制。
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。要获取默认字体的正确名称，可以使用以下代码片段：System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \\{ DefaultReplacementFont = defaultFontName \\});

值：默认替代字体。

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


获取或设置文档名称。

**Returns:**
java.lang.String - 文档名称。
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


获取或设置指向 EXIF IFD 的指针。

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


获取额外样本计数。

值：额外样本计数。

**Returns:**
long - 额外样本计数。
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


获取额外样本值。

值：额外样本值。

**Returns:**
int[] - 额外样本值数组。
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


获取或设置传真 T4 选项。

**Returns:**
long - 传真 t4 选项。
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


获取或设置 TIFF 文件标准。

**Returns:**
int - TIFF 文件标准。
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


获取或设置字节位填充顺序。

**Returns:**
int - 字节位填充顺序。
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


获取一个值，指示是否为 [full frame]。

值：如果是 [full frame] 则为 true；否则为 false。

**Returns:**
布尔型 - 指示是否为 [full frame] 的值。
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


获取或设置半色调提示。

**Returns:**
int[] - 半色调提示。
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


获取 ICC 配置文件流。

**Returns:**
byte[] - ICC 配置文件。
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


获取或设置一个值，指示在创建事件后是否忽略。

值：如果在创建事件后忽略则为 true；否则为 false。

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


获取或设置图像描述。

**Returns:**
java.lang.String - 图像描述。
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


获取或设置图像长度。

**Returns:**
long - 图像长度。
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


获取或设置图像宽度。

**Returns:**
long - 图像宽度。
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


获取或设置墨水名称。

**Returns:**
java.lang.String - 墨水名称。
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


获取或设置最大样本值。

**Returns:**
int[] - 最大样本值。
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


获取或设置最小样本值。

**Returns:**
int[] - 最小样本值。
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


多页选项

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


获取或设置方向。

**Returns:**
int - 方向。
### getPageName() {#getPageName--}
```
public String getPageName()
```


获取或设置页面名称。

**Returns:**
java.lang.String - 页面名称。
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


获取或设置页码标签。

**Returns:**
int[] - 页面编号标签。
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


获取或设置颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


获取或设置光度。

**Returns:**
int - 光度。
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


获取或设置平面配置。

**Returns:**
int - 平面配置。
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


获取或设置 LZW 压缩的预测器。

**Returns:**
int - 预测器类型。
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


获取或设置指示组件是否必须预乘的值。

**Returns:**
boolean - 若组件必须预乘则为 true；否则为 false。
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


获取或设置进度事件处理程序。

值：进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


获取或设置分辨率设置。

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


获取或设置分辨率单位。

**Returns:**
int - 分辨率单位。
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


获取或设置每条带的行数。

**Returns:**
long - 每条带的行数。
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


获取或设置样本格式。

**Returns:**
int[] - 样本格式。
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


获取每像素的样本数。要更改此属性值，请使用 BitsPerSample 属性设置器。

**Returns:**
int - 每像素的样本数。
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


获取或设置扫描仪制造商。

**Returns:**
java.lang.String - 扫描仪制造商。
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


获取或设置扫描仪型号。

**Returns:**
java.lang.String - 扫描仪型号。
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


获取或设置最大样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。

**Returns:**
long[] - 最大样本值。
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


获取或设置最小样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。

**Returns:**
long[] - 最小样本值。
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


获取或设置软件类型。

**Returns:**
java.lang.String - 软件类型。
### getSource() {#getSource--}
```
public final Source getSource()
```


获取或设置用于创建图像的源。

值：创建图像的来源。

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


获取或设置条带字节计数。

**Returns:**
long[] - 条带字节计数。
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


获取或设置条带偏移。

**Returns:**
long[] - 条带偏移。
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


获取或设置此子文件中包含的数据类型的一般指示。

**Returns:**
long - 对此子文件中包含的数据类型的一般指示。
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


按类型获取标签的实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| tagKey | int | 标签键。 |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


获取或设置标签。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - 标签。
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


获取或设置目标打印机。

**Returns:**
java.lang.String - 目标打印机。
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


获取或设置阈值化。

**Returns:**
int - 阈值设定。
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


获取或设置瓦片字节计数。

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


获取或设置瓦片长度。

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


获取或设置瓦片偏移。

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


获取或设置瓦片宽度。

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


获取总页数。

**Returns:**
int - 总页数。
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


获取有效标签计数。这不是标签的总计数，而是可能被保留的标签数量。

**Returns:**
int - 有效标签计数。
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


获取有效标签的计数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 要验证的标签。 |

**Returns:**
int - 有效标签的计数。
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


获取或设置矢量光栅化选项。

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


获取图像作者，Windows 资源管理器使用。

值：图像作者，由 Windows Explorer 使用。如果存在 Artist（[.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) 标签，则 Windows Explorer 会忽略 XPAuthor（ \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)）。

**Returns:**
java.lang.String - 图像作者，由 Windows Explorer 使用。
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


获取图像注释，Windows 资源管理器使用。

值：图像注释，由 Windows Explorer 使用。

**Returns:**
java.lang.String - 图像注释，由 Windows Explorer 使用。
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


获取图像主题，Windows 资源管理器使用。

值：图像主题，由 Windows Explorer 使用。

**Returns:**
java.lang.String - 图像主题，由 Windows Explorer 使用。
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


获取图像信息，供 Windows Explorer 使用。

值：图像信息，由 Windows Explorer 使用。

**Returns:**
java.lang.String - 图像信息，由 Windows Explorer 使用。
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


获取图像信息，供 Windows Explorer 使用。

值：图像信息，由 Windows Explorer 使用。如果存在 ImageDescription（[.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) 标签，则 Windows Explorer 会忽略 XPTitle（ \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)）。

**Returns:**
java.lang.String - 图像信息，由 Windows Explorer 使用。
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


获取或设置 XMP 元数据容器。

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


获取或设置 x 位置。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


获取或设置 X 分辨率。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


获取或设置 YCbCrCoefficients。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - YCbCr 系数。
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


获取或设置 YCbCr 光度的子采样因子。

**Returns:**
int[] - YCbCr 颜色空间的子采样因子。
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


获取或设置 y 位置。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


获取或设置 Y 分辨率。

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


获取一个值，指示是否存在额外样本。

**Returns:**
boolean -  true  如果存在额外样本；否则，  false 。
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


确定选项中是否存在标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 标签 | int | 要检查的标签 ID。 |

**Returns:**
boolean -  true  如果标签存在；否则，  false 。
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


获取一个值，指示图像是否为平铺。

**Returns:**
boolean -  true  如果图像为平铺；否则，  false 。
### isValid() {#isValid--}
```
public boolean isValid()
```


获取一个值，指示 TiffOptions 是否已正确配置。使用 Validate 方法查找失败原因。

**Returns:**
boolean -  true  如果 TiffOptions 已正确配置；否则，  false 。
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


移除标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 标签 | int | 要移除的标签。 |

**Returns:**
boolean - true 如果成功移除
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


获取或设置 alpha 存储选项。当定义的 SamplesPerPixel 超过 3 时，除 TiffAlphaStorage.Unspecified 之外的选项将被使用。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | Alpha 存储选项。 |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


获取或设置艺术家。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 艺术家。 |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


获取或设置背景颜色。用于内部存储图像的背景颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 背景颜色。 |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


设置每个样本的位数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 每个样本的位数值。 |

设置此值时请记住，它还会将 SamplesPerPixel 的值设为数组长度。这两个属性紧密耦合，必须一起设置。 |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


获取或设置指示 TIFF 字节顺序的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


获取或设置颜色映射。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | 颜色映射表。 |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


设置压缩图像质量。用于 JPEG 压缩。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 压缩图像质量。 |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


设置压缩方式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 压缩。 |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


设置版权信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 版权信息。 |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


获取或设置日期和时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 日期和时间。 |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


获取或设置默认内存分配限制。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 默认内存分配限制。 |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。要获取默认字体的正确名称，可以使用以下代码片段：System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \\{ DefaultReplacementFont = defaultFontName \\});

值：默认替代字体。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


获取或设置文档名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 文档名称。 |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


设置额外样本的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | 额外样本值。 |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


获取或设置传真 T4 选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long | 传真 t4 选项。 |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


获取或设置 TIFF 文件标准。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | TIFF 文件标准。 |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


获取或设置字节位填充顺序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 字节位填充顺序。 |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


设置一个值，指示是否为 [full frame]。

值：如果是 [full frame] 则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示是否为 [full frame] 的值。 |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


获取或设置半色调提示。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | 半色调提示。 |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


设置 ICC 配置文件流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] | ICC 配置文件。 |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


获取或设置一个值，指示在创建事件后是否忽略。

值：如果在创建事件后忽略则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


获取或设置图像描述。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像描述。 |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


获取或设置图像长度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long | 图像长度。 |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


获取或设置图像宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long | 图像宽度。 |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


获取或设置墨水名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 墨水名称。 |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


获取或设置最大样本值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | 最大样本值。 |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


获取或设置最小样本值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | 最小样本值。 |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


多页选项

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


获取或设置方向。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 方向。 |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


获取或设置页面名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 页面名称。 |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


获取或设置页码标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | 页面编号标签。 |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


获取或设置颜色调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


获取或设置光度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 光度学。 |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


获取或设置平面配置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 平面配置。 |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


获取或设置 LZW 压缩的预测器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 预测器类型。 |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


获取或设置指示组件是否必须预乘的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | true 如果组件必须预乘；否则， false。 |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


获取或设置进度事件处理程序。

值：进度事件处理程序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


获取或设置分辨率设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


获取或设置分辨率单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 分辨率单位。 |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


获取或设置每条带的行数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long | 每条带的行数。 |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


获取或设置样本格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | 样本格式。 |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


获取或设置扫描仪制造商。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 扫描仪制造商。 |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


获取或设置扫描仪型号。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 扫描仪型号。 |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


获取或设置最大样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long[] | 最大样本值。 |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


获取或设置最小样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long[] | 最小样本值。 |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


获取或设置软件类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 软件类型。 |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


获取或设置用于创建图像的源。

值：创建图像的来源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


获取或设置条带字节计数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long[] | 条带字节计数。 |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


获取或设置条带偏移。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long[] | 条带偏移。 |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


获取或设置此子文件中包含的数据类型的一般指示。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long | 此子文件中包含的数据类型的一般指示。 |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


获取或设置标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 标签。 |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


获取或设置目标打印机。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 目标打印机。 |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


获取或设置阈值化。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 阈值处理。 |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


获取或设置瓦片字节计数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


获取或设置瓦片长度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


获取或设置瓦片偏移。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


获取或设置瓦片宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


获取或设置矢量光栅化选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


设置图像作者，供 Windows Explorer 使用。

值：Image Author，由 Windows Explorer 使用。如果存在 Artist（[.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)）标签，则 Windows Explorer 会忽略 XPAuthor（[.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像作者，由 Windows Explorer 使用。 |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


设置图像注释，供 Windows Explorer 使用。

值：图像注释，由 Windows Explorer 使用。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像注释，由 Windows Explorer 使用。 |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


设置图像主题，供 Windows Explorer 使用。

值：图像主题，由 Windows Explorer 使用。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 主题图像，由 Windows Explorer 使用。 |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


设置图像信息，供 Windows Explorer 使用。

值：图像信息，由 Windows Explorer 使用。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像信息，由 Windows Explorer 使用。 |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


设置图像信息，供 Windows Explorer 使用。

值：图像信息，由 Windows Explorer 使用。如果存在 ImageDescription（[.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)）标签，则 Windows Explorer 会忽略 XPTitle（[.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String)）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 图像信息，由 Windows Explorer 使用。 |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


获取或设置 XMP 元数据容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP 数据容器。 |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


获取或设置 x 位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x 位置。 |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


获取或设置 X 分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x 分辨率。 |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


获取或设置 YCbCrCoefficients。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | YCbCrCoefficients。 |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


获取或设置 YCbCr 光度的子采样因子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] | YCbCr 影像的子采样因子。 |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


获取或设置 y 位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y 位置。 |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


获取或设置 Y 分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y 分辨率。 |

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


验证选项是否具有有效的标签组合。

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

