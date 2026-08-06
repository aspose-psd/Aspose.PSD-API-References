---
title: "PsdOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "PSD 文件格式创建选项。"
type: docs
weight: 21
url: /zh/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

PSD 文件格式创建选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | 初始化 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 类的新实例。 |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | 初始化 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 类的新实例。 |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | 初始化 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [deepClone()](#deepClone--) | 克隆此实例。 |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | 获取或设置背景颜色。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getChannelBitsCount()](#getChannelBitsCount--) | 获取或设置每个颜色通道的位数。 |
| [getChannelsCount()](#getChannelsCount--) | 获取或设置颜色通道的数量。 |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | 获取或设置 PSD 的颜色模式。 |
| [getCompressionMethod()](#getCompressionMethod--) | 获取或设置 PSD 的压缩方式。 |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getFullFrame()](#getFullFrame--) | 获取一个值，指示是否为 [full frame]。 |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 获取或设置一个值，指示在创建事件后是否忽略。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | 多页选项 |
| [getPalette()](#getPalette--) | 获取或设置颜色调色板。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取或设置进度事件处理程序。 |
| [getPsdVersion()](#getPsdVersion--) | 获取或设置文件格式版本。 |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | 获取或设置一个值，指示是否 [refresh image preview data] - 此选项用于最大程度兼容其他 PSD 图像查看器。 |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | 获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本图层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本图层相关）。 |
| [getResolutionSettings()](#getResolutionSettings--) | 获取或设置分辨率设置。 |
| [getResources()](#getResources--) | 获取或设置 PSD 资源。 |
| [getSource()](#getSource--) | 获取或设置用于创建图像的源。 |
| [getUpdateMetadata()](#getUpdateMetadata--) | 获取或设置一个值，指示是否 [update metadata]。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 获取或设置矢量光栅化选项。 |
| [getVersion()](#getVersion--) | 获取或设置 PSD 文件版本。 |
| [getXmpData()](#getXmpData--) | 获取或设置 XMP 数据容器 |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | 显示是否已分配 ColorMode 属性。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 获取或设置背景颜色。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | 获取或设置每个颜色通道的位数。 |
| [setChannelsCount(short value)](#setChannelsCount-short-) | 获取或设置颜色通道的数量。 |
| [setColorMode(short value)](#setColorMode-short-) | 获取或设置 PSD 的颜色模式。 |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | 获取或设置 PSD 的压缩方式。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 设置一个值，指示是否为 [full frame]。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 获取或设置一个值，指示在创建事件后是否忽略。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | 多页选项 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 获取或设置颜色调色板。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 获取或设置进度事件处理程序。 |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | 获取或设置文件格式版本。 |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | 获取或设置一个值，指示是否 [refresh image preview data] - 此选项用于最大程度兼容其他 PSD 图像查看器。 |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | 获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本图层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本图层相关）。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 获取或设置分辨率设置。 |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | 获取或设置 PSD 资源。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 获取或设置用于创建图像的源。 |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | 获取或设置一个值，指示是否 [update metadata]。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 获取或设置矢量光栅化选项。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置 PSD 文件版本。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | 获取或设置 XMP 数据容器 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


初始化 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 类的新实例。

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


初始化 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | 选项。 |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


初始化 [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | 图像。 |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


获取或设置背景颜色。它可以在透明对象下看到。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


获取或设置每个颜色通道的位数。

值：每个颜色通道的位数。

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


获取或设置颜色通道的数量。

值：颜色通道的数量。

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


获取或设置 PSD 的颜色模式。

值：该颜色模式。

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


获取或设置 PSD 的压缩方式。

值：压缩方法。

**Returns:**
short
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
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


获取或设置文件格式版本。它可以是 PSD 或 PSB。

值：文件格式版本。

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


获取或设置一个值，指示是否 [refresh image preview data] - 此选项用于最大程度兼容其他 PSD 图像查看器。请注意，紧凑框架平台不支持将文本图层绘制到最终布局。

值：如果 [refresh image preview data] 为 true；否则为 false。

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本图层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本图层相关）。使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：菜单 "Text" -> "Process absent fonts"。完成此操作后，所有文本将再次出现。请注意，此操作可能导致部分最终布局的更改。

值：如果 [remove global text engine resource] 为 true；否则为 false。

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


获取或设置分辨率设置。

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


获取或设置 PSD 资源。如果值为：NULL - 则保存原始 ImageResources（默认行为）；Not Empty - 则保存传入此属性的资源 + [required resources]；Empty - 则仅保存 [required resources]。必需的资源：ResolutionInfoResource、XmpResource。

值：psd 资源。

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


获取或设置用于创建图像的源。

值：创建图像的来源。

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


获取或设置一个值，指示是否 [update metadata]。如果该值为 true，则在保存图像时会更新元数据。

值： true 如果 [update metadata]；否则， false。

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


获取或设置矢量光栅化选项。

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取或设置 PSD 文件版本。

值：psd 文件版本。

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


获取或设置 XMP 数据容器

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


显示是否已分配 ColorMode 属性。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
```


获取或设置背景颜色。它可以在透明对象下看到。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


获取或设置每个颜色通道的位数。

值：每个颜色通道的位数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


获取或设置颜色通道的数量。

值：颜色通道的数量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


获取或设置 PSD 的颜色模式。

值：该颜色模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


获取或设置 PSD 的压缩方式。

值：压缩方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


获取或设置文件格式版本。它可以是 PSD 或 PSB。

值：文件格式版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


获取或设置一个值，指示是否 [refresh image preview data] - 此选项用于最大程度兼容其他 PSD 图像查看器。请注意，紧凑框架平台不支持将文本图层绘制到最终布局。

值：如果 [refresh image preview data] 为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本图层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本图层相关）。使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：菜单 "Text" -> "Process absent fonts"。完成此操作后，所有文本将再次出现。请注意，此操作可能导致部分最终布局的更改。

值：如果 [remove global text engine resource] 为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


获取或设置分辨率设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


获取或设置 PSD 资源。如果值为：NULL - 则保存原始 ImageResources（默认行为）；Not Empty - 则保存传入此属性的资源 + [required resources]；Empty - 则仅保存 [required resources]。必需的资源：ResolutionInfoResource、XmpResource。

值：psd 资源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


获取或设置一个值，指示是否 [update metadata]。如果该值为 true，则在保存图像时会更新元数据。

值： true 如果 [update metadata]；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


获取或设置矢量光栅化选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


获取或设置 PSD 文件版本。

值：psd 文件版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


获取或设置 XMP 数据容器

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

