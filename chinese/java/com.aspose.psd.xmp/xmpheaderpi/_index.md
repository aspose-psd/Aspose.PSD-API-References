---
title: "XmpHeaderPi"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 XMP 标头处理指令。"
type: docs
weight: 16
url: /zh/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

表示 XMP 标头处理指令。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | 初始化 XmpHeaderPi 类的新实例。 |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | 初始化 XmpHeaderPi 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 System.Object 是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | 表示 Header Guid。 |
| [getXmlValue()](#getXmlValue--) | 将 XMP 值转换为 XML 表示。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | 指示当前对象是否等于同一类型的另一个对象。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | 表示 Header Guid。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


初始化 XmpHeaderPi 类的新实例。

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


初始化 XmpHeaderPi 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| GUID | java.lang.String | 唯一标识符。 |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


克隆此实例。

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
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
### getGuid() {#getGuid--}
```
public String getGuid()
```


表示 Header Guid。

标题 PI 的文本包含 GUID，使其不太可能在数据流中意外出现。

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 XMP 值转换为 XML 表示。

**Returns:**
java.lang.String - 返回转换为 XML 表示的 XMP 值。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


指示当前对象是否等于同一类型的另一个对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | 一个用于与此对象比较的对象。 |

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




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


表示 Header Guid。

标题 PI 的文本包含 GUID，使其不太可能在数据流中意外出现。

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

