---
title: "Timecode"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示视频中的 timecode 值。"
type: docs
weight: 15
url: /zh/java/com.aspose.psd.xmp.schemas.xmpdm/timecode/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

表示视频中的 timecode 值。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | 初始化 Timecode 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 System.Object 是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | 获取或设置在 TimeValue 中使用的格式。 |
| [getTimeValue()](#getTimeValue--) | 获取或设置指定格式下的时间值。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 返回 XMP 格式中包含的字符串值。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEquals(Timecode other)](#isEquals-com.aspose.psd.xmp.schemas.xmpdm.Timecode-) | 指示当前对象是否等于同一类型的另一个对象。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-) | 获取或设置在 TimeValue 中使用的格式。 |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | 获取或设置指定格式下的时间值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


初始化 Timecode 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat) | 时间格式。 |
| timeValue | java.lang.String | 时间值。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 System.Object 是否等于此实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 System.Object。 |

**Returns:**
布尔 - 如果指定的 System.Object 等于此实例，则为 true；否则为 false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


获取或设置在 TimeValue 中使用的格式。

值：在 TimeValue 中使用的格式。

**Returns:**
[TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat)
### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


获取或设置指定格式下的时间值。

值：指定格式中的时间值。

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


返回 XMP 格式中包含的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式的字符串值。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### isEquals(Timecode other) {#isEquals-com.aspose.psd.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


指示当前对象是否等于同一类型的另一个对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.psd.xmp.schemas.xmpdm/timecode) | 一个用于与此对象比较的对象。 |

**Returns:**
布尔 - 如果当前对象等于 other 参数，则为 true；否则为 false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFormat(TimeFormat value) {#setFormat-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


获取或设置在 TimeValue 中使用的格式。

值：在 TimeValue 中使用的格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat) |  |

### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


获取或设置指定格式下的时间值。

值：指定格式中的时间值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

