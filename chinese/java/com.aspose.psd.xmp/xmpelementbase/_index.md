---
title: "XmpElementBase"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示包含属性的基础 xmp 元素。"
type: docs
weight: 15
url: /zh/java/com.aspose.psd.xmp/xmpelementbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

表示包含属性的基础 xmp 元素。
## Methods

| Method | 描述 |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | 添加属性。 |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | 将指定的 XMP 元素分配给当前元素。 |
| [clearAttributes()](#clearAttributes--) | 移除所有属性。 |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的  Object , 是否等于此实例。 |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | 获取属性。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | 指示当前对象是否等于同一类型的另一个对象。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


添加属性。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 该属性。 |
| 值 | java.lang.String | 该值。 |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


将指定的 XMP 元素分配给当前元素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | 该 XMP 元素。 |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


移除所有属性。

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


克隆此实例。

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的  Object , 是否等于此实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例，则为 true；否则为 false。
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


获取属性。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 该属性。 |

**Returns:**
java.lang.String - 返回指定属性名称的属性。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


指示当前对象是否等于同一类型的另一个对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | 一个用于与此对象比较的对象。 |

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

