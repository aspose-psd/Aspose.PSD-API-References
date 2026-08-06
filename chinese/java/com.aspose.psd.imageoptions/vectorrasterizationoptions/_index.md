---
title: "VectorRasterizationOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "矢量栅格化选项。"
type: docs
weight: 29
url: /zh/java/com.aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class VectorRasterizationOptions extends ImageOptionsBase
```

矢量栅格化选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 复制到。 |
| [deepClone()](#deepClone--) | 克隆此实例。 |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色。 |
| [getBorderX()](#getBorderX--) | 获取或设置边框 X。 |
| [getBorderY()](#getBorderY--) | 获取或设置边框 Y。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getCenterDrawing()](#getCenterDrawing--) | 获取指示是否居中绘制的值。 |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getDrawColor()](#getDrawColor--) | 获取前景颜色。 |
| [getFullFrame()](#getFullFrame--) | 获取一个值，指示是否为 [full frame]。 |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 获取或设置一个值，指示在创建事件后是否忽略。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | 多页选项 |
| [getPageHeight()](#getPageHeight--) | 获取页面高度。 |
| [getPageSize()](#getPageSize--) | 获取页面大小。 |
| [getPageWidth()](#getPageWidth--) | 获取页面宽度。 |
| [getPalette()](#getPalette--) | 获取或设置颜色调色板。 |
| [getPositioning()](#getPositioning--) | 获取定位。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取或设置进度事件处理程序。 |
| [getResolutionSettings()](#getResolutionSettings--) | 获取或设置分辨率设置。 |
| [getSmoothingMode()](#getSmoothingMode--) | 获取平滑模式。 |
| [getSource()](#getSource--) | 获取或设置用于创建图像的源。 |
| [getTextRenderingHint()](#getTextRenderingHint--) | 获取文本渲染提示。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 获取或设置矢量光栅化选项。 |
| [getXmpData()](#getXmpData--) | 获取或设置 XMP 元数据容器。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 设置背景颜色。 |
| [setBorderX(float value)](#setBorderX-float-) | 获取或设置边框 X。 |
| [setBorderY(float value)](#setBorderY-float-) | 获取或设置边框 Y。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | 设置指示是否居中绘制的值。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。 |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | 设置前景颜色。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 设置一个值，指示是否为 [full frame]。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 获取或设置一个值，指示在创建事件后是否忽略。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | 多页选项 |
| [setPageHeight(float value)](#setPageHeight-float-) | 设置页面高度。 |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | 设置页面大小。 |
| [setPageWidth(float value)](#setPageWidth-float-) | 设置页面宽度。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 获取或设置颜色调色板。 |
| [setPositioning(int value)](#setPositioning-int-) | 设置定位。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 获取或设置进度事件处理程序。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 获取或设置分辨率设置。 |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | 设置平滑模式。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 获取或设置用于创建图像的源。 |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | 设置文本渲染提示。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 获取或设置矢量光栅化选项。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | 获取或设置 XMP 元数据容器。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


复制到。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | 矢量栅格化选项。 |

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


获取或设置边框 X。

**Returns:**
float - 边框 X。
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


获取或设置边框 Y。

**Returns:**
float - 边框 Y。
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


获取指示是否居中绘制的值。

**Returns:**
boolean - 一个指示是否居中绘制的值。
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
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


获取前景颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
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
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


获取页面高度。

**Returns:**
float - 页面高度。
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


获取页面大小。

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


获取页面宽度。

**Returns:**
float - 页面宽度。
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


获取或设置颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


获取定位。

Value: 定位。

**Returns:**
int - 定位。
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
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


获取平滑模式。

**Returns:**
int - 平滑模式。
### getSource() {#getSource--}
```
public final Source getSource()
```


获取或设置用于创建图像的源。

值：创建图像的来源。

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


获取文本渲染提示。

Value: 文本渲染提示。

**Returns:**
int - 文本渲染提示。
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


设置背景颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 背景颜色。 |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


获取或设置边框 X。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 边框 X。 |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


获取或设置边框 Y。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 边框 Y。 |

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

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


设置指示是否居中绘制的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 一个指示是否居中绘制的值。 |

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

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


设置前景颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 前景颜色。 |

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

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


设置页面高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 页面高度。 |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


设置页面大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | 页面大小。 |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


设置页面宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 页面宽度。 |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


获取或设置颜色调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


设置定位。

Value: 定位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 定位。 |

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

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


设置平滑模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 平滑模式。 |

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

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


设置文本渲染提示。

Value: 文本渲染提示。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 文本渲染提示。 |

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

