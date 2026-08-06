---
title: "Jpeg2000LoadOptions"
second_title: "Aspose.PSD 的 Java API 参考"
description: "JPEG2000 加载选项"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.imageloadoptions/jpeg2000loadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

JPEG2000 加载选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | 初始化 Jpeg2000LoadOptions 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | 自定义字体来源 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | 获取图像背景颜色。 |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | 获取数据恢复模式。 |
| [getDefaultMaximumDecodingTime_internalized()](#getDefaultMaximumDecodingTime-internalized--) | 获取默认的最大解码时间。 |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | 获取一个值，指示是否 [ignore after load]。 |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | 获取以秒为单位的最大解码时间（此选项可用于内存非常慢的机器，以防在处理非常大的图像时（分辨率超过 5500x6500 像素）挂起）。 |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | 获取瓦片的最大解码时间。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取进度事件处理程序。 |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | 获取一个值，指示是否应应用 ICC 配置文件转换。 |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | 这是风险许可模式的一部分。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | 设置图像背景颜色。 |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | 设置数据恢复模式。 |
| [setDefaultMaximumDecodingTime_internalized(int value)](#setDefaultMaximumDecodingTime-internalized-int-) | 设置默认的最大解码时间。 |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | 设置一个值，指示是否 [ignore after load]。 |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | 设置以秒为单位的最大解码时间（此选项可用于非常慢且内存不足的机器，以防在处理非常大的图像时挂起——分辨率超过 5500x6500 像素）。 |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | 设置瓦片的最大解码时间。 |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | 获取或设置 memory MGR。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 设置进度事件处理程序。 |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | 设置一个值，指示是否应应用 ICC 配置文件转换。 |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | 这是风险许可模式的一部分。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


初始化 Jpeg2000LoadOptions 类的新实例。

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
### getDefaultMaximumDecodingTime_internalized() {#getDefaultMaximumDecodingTime-internalized--}
```
public static int getDefaultMaximumDecodingTime_internalized()
```


获取默认的最大解码时间。

**Returns:**
int - 默认最大解码时间。
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


获取一个值，指示是否 [ignore after load]。

**Returns:**
boolean - 如果 [ignore after load] 为 true；否则为 false。
### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


获取以秒为单位的最大解码时间（此选项可用于内存非常慢的机器，以防在处理非常大的图像时（分辨率超过 5500x6500 像素）挂起）。

**Returns:**
int - 最大解码时间。
### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


获取瓦片的最大解码时间。

值：瓦片的最大解码时间。

**Returns:**
int - 瓦片的最大解码时间。
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


获取进度事件处理程序。

值：进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
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

### setDefaultMaximumDecodingTime_internalized(int value) {#setDefaultMaximumDecodingTime-internalized-int-}
```
public static void setDefaultMaximumDecodingTime_internalized(int value)
```


设置默认的最大解码时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 默认最大解码时间。 |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


设置一个值，指示是否 [ignore after load]。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 如果 [ignore after load] 为 true；否则为 false。 |

### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


设置以秒为单位的最大解码时间（此选项可用于非常慢且内存不足的机器，以防在处理非常大的图像时挂起——分辨率超过 5500x6500 像素）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 最大解码时间。 |

### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


设置瓦片的最大解码时间。

值：瓦片的最大解码时间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 瓦片的最大解码时间。 |

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

