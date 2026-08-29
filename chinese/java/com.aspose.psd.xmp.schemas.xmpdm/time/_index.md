---
title: "Time"
second_title: "Aspose.PSD 的 Java API 参考"
description: "以秒为单位的时间值表示。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

以秒为单位的时间值表示。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | 初始化 Time 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | 获取或设置时间值的比例。 |
| [getValue()](#getValue--) | 获取或设置指定比例中的时间值。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | 获取或设置时间值的比例。 |
| [setValue(int value)](#setValue-int-) | 获取或设置指定比例中的时间值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


初始化 Time 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | 比例。 |
| 值 | int | 该值。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getScale() {#getScale--}
```
public Rational getScale()
```


获取或设置时间值的比例。

对于 NTSC，使用 1001/30000，或不太精确的 100/2997。对于 PAL，使用 1/25。值：时间值的比例。

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


获取或设置指定比例中的时间值。

值：指定比例中的时间值。

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式的字符串值。
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


获取或设置时间值的比例。

对于 NTSC，使用 1001/30000，或不太精确的 100/2997。对于 PAL，使用 1/25。值：时间值的比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


获取或设置指定比例中的时间值。

值：指定比例中的时间值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

