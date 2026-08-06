---
title: "PngOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "PNG 文件格式创建选项。"
type: docs
weight: 19
url: /zh/java/com.aspose.psd.imageoptions/pngoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

PNG 文件格式创建选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PngOptions()](#PngOptions--) | 初始化 PngOptions 类的新实例。 |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.psd.imageoptions.PngOptions-) | 初始化 JpegOptions 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | 默认压缩级别。 |
## Methods

| Method | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [deepClone()](#deepClone--) | 克隆此实例。 |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | 获取位深度。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 获取或设置颜色的类型。 |
| [getCompressionLevel()](#getCompressionLevel--) | png 图像压缩级别在 0-9 范围内，9 为最高压缩，0 为存储模式。 |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getFilterType()](#getFilterType--) | 获取或设置 png 文件保存过程中使用的过滤器类型。 |
| [getFullFrame()](#getFullFrame--) | 获取一个值，指示是否为 [full frame]。 |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 获取或设置一个值，指示在创建事件后是否忽略。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | 多页选项 |
| [getPalette()](#getPalette--) | 获取或设置颜色调色板。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取或设置进度事件处理程序。 |
| [getProgressive()](#getProgressive--) | 获取或设置一个值，指示此 PngOptions 是否为渐进式。 |
| [getResolutionSettings()](#getResolutionSettings--) | 获取或设置分辨率设置。 |
| [getSource()](#getSource--) | 获取或设置用于创建图像的源。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 获取或设置矢量光栅化选项。 |
| [getXmpData()](#getXmpData--) | 获取或设置 XMP 元数据容器。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitDepth(byte value)](#setBitDepth-byte-) | 设置位深度。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setColorType(int value)](#setColorType-int-) | 获取或设置颜色的类型。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | png 图像压缩级别在 0-9 范围内，9 为最高压缩，0 为存储模式。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。 |
| [setFilterType(int value)](#setFilterType-int-) | 获取或设置 png 文件保存过程中使用的过滤器类型。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 设置一个值，指示是否为 [full frame]。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 获取或设置一个值，指示在创建事件后是否忽略。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | 多页选项 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 获取或设置颜色调色板。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 获取或设置进度事件处理程序。 |
| [setProgressive(boolean value)](#setProgressive-boolean-) | 获取或设置一个值，指示此 PngOptions 是否为渐进式。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 获取或设置分辨率设置。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 获取或设置用于创建图像的源。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 获取或设置矢量光栅化选项。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | 获取或设置 XMP 元数据容器。 |
| [toString()](#toString--) |  |
| [validate_internalized()](#validate-internalized--) | 选项验证例程。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngOptions() {#PngOptions--}
```
public PngOptions()
```


初始化 PngOptions 类的新实例。

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.psd.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


初始化 JpegOptions 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.psd.imageoptions/pngoptions) | PNG 选项。 |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


默认压缩级别。

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
### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


获取位深度。

**Returns:**
byte - 位深度。
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


获取或设置颜色的类型。

**Returns:**
int - 颜色的类型。
### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


png 图像压缩级别在 0-9 范围内，9 为最高压缩，0 为存储模式。

**Returns:**
int - 0-9 范围内的压缩级别，9 为最大压缩，0 为存储模式。
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
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


获取或设置 png 文件保存过程中使用的过滤器类型。

**Returns:**
int - png 文件保存过程中使用的过滤类型。
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


获取一个值，指示是否为 [full frame]。

值：如果是 [full frame] 则为 true；否则为 false。

**Returns:**
布尔型 - 指示是否为 [full frame] 的值。
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


获取或设置一个值，指示在创建事件后是否忽略。

值：如果在创建事件后忽略则为 true；否则为 false。

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


多页选项

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


获取或设置颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


获取或设置进度事件处理程序。

值：进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


获取或设置一个值，指示此 PngOptions 是否为渐进式。

**Returns:**
boolean - progressive 为 true；否则为 false。
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


获取或设置分辨率设置。

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


获取或设置用于创建图像的源。

值：创建图像的来源。

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


获取或设置矢量光栅化选项。

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


获取或设置 XMP 元数据容器。

值：XMP 数据容器。

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




### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


设置位深度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte | 位深度。 |

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

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


获取或设置颜色的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 颜色的类型。 |

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


png 图像压缩级别在 0-9 范围内，9 为最高压缩，0 为存储模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 0-9 范围内的压缩级别，9 为最大压缩，0 为存储模式。 |

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

### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


获取或设置 png 文件保存过程中使用的过滤器类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | png 文件保存过程中使用的过滤类型。 |

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

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


多页选项

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


获取或设置颜色调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

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

### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


获取或设置一个值，指示此 PngOptions 是否为渐进式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | progressive 为 true；否则为 false。 |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


获取或设置分辨率设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

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

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


获取或设置矢量光栅化选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


获取或设置 XMP 元数据容器。

值：XMP 数据容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate_internalized() {#validate-internalized--}
```
public void validate_internalized()
```


选项验证例程。

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

