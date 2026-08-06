---
title: "PsdLoadOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "PSD 加载选项"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

PSD 加载选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | 初始化 [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | 自定义字体来源 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | 获取或设置在渲染期间是否在图层未被修改时保留原始图层像素。 |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | 获取或设置是否随渲染图像一起保存，是否使用扭曲变换。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | 获取图像背景颜色。 |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | 获取数据恢复模式。 |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | 获取一个值，指示是否 [ignore after load]。 |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | 获取或设置一个值，指示是否[ignore alpha channel]。 |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | 获取或设置一个值，指示在执行 UpdateText 操作时是否忽略 PSD 文本层的固定宽度。 |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | 获取或设置一个值，指示是否[load effects resource]（默认情况下资源未加载）。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取进度事件处理程序。 |
| [getReadOnlyMode()](#getReadOnlyMode--) | 获取或设置一个值，指示是否[use read only mode]。 |
| [getReadOnlyType()](#getReadOnlyType--) | 获取或设置加载 PSD 图像时使用的只读模式。 |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | 获取或设置一个值，指示是否[use disk for load effects resource]（默认使用磁盘加载效果资源，但如果将此值设为 false，则可以使用足够的内存）。 |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | 获取一个值，指示是否应应用 ICC 配置文件转换。 |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | 这是风险许可模式的一部分。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | 获取或设置在渲染期间是否在图层未被修改时保留原始图层像素。 |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | 获取或设置是否随渲染图像一起保存，是否使用扭曲变换。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | 设置图像背景颜色。 |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | 设置数据恢复模式。 |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | 设置一个值，指示是否 [ignore after load]。 |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | 获取或设置一个值，指示是否[ignore alpha channel]。 |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | 获取或设置一个值，指示在执行 UpdateText 操作时是否忽略 PSD 文本层的固定宽度。 |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | 获取或设置一个值，指示是否[load effects resource]（默认情况下资源未加载）。 |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | 获取或设置 memory MGR。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 设置进度事件处理程序。 |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | 获取或设置一个值，指示是否[use read only mode]。 |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | 获取或设置加载 PSD 图像时使用的只读模式。 |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | 获取或设置一个值，指示是否[use disk for load effects resource]（默认使用磁盘加载效果资源，但如果将此值设为 false，则可以使用足够的内存）。 |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | 设置一个值，指示是否应应用 ICC 配置文件转换。 |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | 这是风险许可模式的一部分。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


初始化 [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) 类的新实例。

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


自定义字体来源

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


获取或设置在渲染期间是否在图层未被修改时保留原始图层像素。

值： true  保持未更改图层的原始像素；否则， false 。

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


获取或设置是否随渲染图像一起保存，是否使用扭曲变换。

值： true  使用扭曲变换渲染图像；false 。

**Returns:**
boolean
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Returns:**
int - 缓冲区大小提示，定义为所有内部缓冲区的最大允许大小。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


获取图像背景颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

通常在由于数据损坏导致像素值无法恢复时，会设置背景颜色。
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


获取数据恢复模式。

**Returns:**
int - 数据恢复模式。
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


获取一个值，指示是否 [ignore after load]。

**Returns:**
boolean - 如果 [ignore after load] 为 true；否则为 false。
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


获取或设置一个值，指示是否[ignore alpha channel]。

值： true  如果[ignore alpha channel]；否则， false 。

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


获取或设置一个值，指示在执行 UpdateText 操作时是否忽略 PSD 文本层的固定宽度。

值： true  如果[ignore text layer width]；否则， false 。

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


获取或设置一个值，指示是否[load effects resource]（默认情况下资源未加载）。设置此选项后，仅支持的效果将渲染到最终合并图像中。

值： true  如果[load effects resource]；否则， false 。

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


获取进度事件处理程序。

值：进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


获取或设置一个值，指示是否[use read only mode]。这是只读模式，支持与 Adobe Photoshop 完全兼容。当设置此选项时，对图层所做的所有更改都不会保存到最终图像。所有数据均来自 ImageData 部分，因此与 Photoshop 完全相同。默认情况下，所有加载的图像都不与 Adobe Photoshop 完全兼容。

值： true  如果[use photoshop compatibility mode]；否则， false 。

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


获取或设置加载 PSD 图像时使用的只读模式。

值： ReadOnlyMode（[.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-))中的一个值：

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


获取或设置一个值，指示是否[use disk for load effects resource]（默认使用磁盘加载效果资源，但如果将此值设为 false，则可以使用足够的内存）。

值： true  如果[use disk for load effects resource]；否则， false 。

**Returns:**
boolean
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


获取一个值，指示是否应应用 ICC 配置文件转换。

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


这是风险授权模式的一部分。如果风险向我们传递 LoadOptions 对象，VentureLicenser 将设置此值。

**Returns:**
java.lang.Object
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


获取或设置在渲染期间是否在图层未被修改时保留原始图层像素。

值： true  保持未更改图层的原始像素；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


获取或设置是否随渲染图像一起保存，是否使用扭曲变换。

值： true  使用扭曲变换渲染图像；false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 缓冲区大小提示，定义为所有内部缓冲区的最大允许大小。 |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


设置图像背景颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | 背景颜色。 |

通常在由于数据损坏导致像素值无法恢复时，会设置背景颜色。 |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


设置数据恢复模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 数据恢复模式。 |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


设置一个值，指示是否 [ignore after load]。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 如果 [ignore after load] 为 true；否则为 false。 |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


获取或设置一个值，指示是否[ignore alpha channel]。

值： true  如果[ignore alpha channel]；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


获取或设置一个值，指示在执行 UpdateText 操作时是否忽略 PSD 文本层的固定宽度。

值： true  如果[ignore text layer width]；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


获取或设置一个值，指示是否[load effects resource]（默认情况下资源未加载）。设置此选项后，仅支持的效果将渲染到最终合并图像中。

值： true  如果[load effects resource]；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


获取或设置 memory MGR。

值：memory MGR。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


设置进度事件处理程序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 进度事件处理程序。 |

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


获取或设置一个值，指示是否[use read only mode]。这是只读模式，支持与 Adobe Photoshop 完全兼容。当设置此选项时，对图层所做的所有更改都不会保存到最终图像。所有数据均来自 ImageData 部分，因此与 Photoshop 完全相同。默认情况下，所有加载的图像都不与 Adobe Photoshop 完全兼容。

值： true  如果[use photoshop compatibility mode]；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


获取或设置加载 PSD 图像时使用的只读模式。

值： ReadOnlyMode（[.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-))中的一个值：

 *  
 *  
 *  

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


获取或设置一个值，指示是否[use disk for load effects resource]（默认使用磁盘加载效果资源，但如果将此值设为 false，则可以使用足够的内存）。

值： true  如果[use disk for load effects resource]；否则， false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


设置一个值，指示是否应应用 ICC 配置文件转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


这是风险授权模式的一部分。如果风险向我们传递 LoadOptions 对象，VentureLicenser 将设置此值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

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

