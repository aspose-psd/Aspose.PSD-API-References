---
title: "XmpDate"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 XMP 包中的日期。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

表示 XMP 包中的日期。

日期时间值使用以下子集格式表示，正如 Date and Time Formats 中定义的：YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | 初始化  XmpDate  类的新实例。 |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | 初始化  XmpDate  类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | ISO 8601（往返）格式字符串。 |
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | 获取当前值的格式字符串。 |
| [getValue()](#getValue--) | 获取或设置日期值。 |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | 返回 XMP 格式中包含的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | 获取或设置日期值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


初始化  XmpDate  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dateTime | java.util.Date | 日期时间值使用 ISO RFC 8601 格式的子集表示。 |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


初始化  XmpDate  类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dateString | java.lang.String | 日期的字符串表示形式。 |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


ISO 8601（往返）格式字符串。

查看更多：https://en.wikipedia.org/wiki/ISO\_8601。

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


获取当前值的格式字符串。

值：当前值的格式字符串。

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


获取或设置日期值。

值：日期值。

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


返回 XMP 格式中包含的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


获取或设置日期值。

值：日期值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

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

