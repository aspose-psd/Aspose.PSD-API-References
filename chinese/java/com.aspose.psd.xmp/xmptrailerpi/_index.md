---
title: "XmpTrailerPi"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 XMP 尾部处理指令。"
type: docs
weight: 22
url: /zh/java/com.aspose.psd.xmp/xmptrailerpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

表示 XMP 尾部处理指令。

end="w" 或 end="r" 部分应由数据包扫描处理器使用，以确定 XMP 是否可以就地修改。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | 初始化 XmpTrailerPi 类的新实例。 |
| [XmpTrailerPi()](#XmpTrailerPi--) | 初始化 XmpTrailerPi 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 System.Object 是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | 将 xmp 值转换为 xml 表示形式。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.psd.xmp.XmpTrailerPi-) | 指示当前对象是否等于同一类型的另一个对象。 |
| [isWritable()](#isWritable--) | 获取或设置一个值，指示此实例是否可写。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWritable(boolean value)](#setWritable-boolean-) | 获取或设置一个值，指示此实例是否可写。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


初始化 XmpTrailerPi 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| isWritable | boolean | 指示 trailer 是否可写。 |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


初始化 XmpTrailerPi 类的新实例。

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpTrailerPi deepClone_internalized()
```


克隆此实例。

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - The cloned object
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
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 xmp 值转换为 xml 表示形式。

**Returns:**
java.lang.String - 返回 XMP 的 XML 表示。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.psd.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


指示当前对象是否等于同一类型的另一个对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | 一个用于与此对象比较的对象。 |

**Returns:**
布尔 - 如果当前对象等于 other 参数，则为 true；否则为 false。
### isWritable() {#isWritable--}
```
public boolean isWritable()
```


获取或设置一个值，指示此实例是否可写。

值：如果此实例可写则为 true；否则为 false。

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




### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


获取或设置一个值，指示此实例是否可写。

值：如果此实例可写则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

