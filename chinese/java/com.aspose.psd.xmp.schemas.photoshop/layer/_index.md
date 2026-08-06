---
title: "图层"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 Photoshop 文本图层。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.xmp.schemas.photoshop/layer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

表示 Photoshop 文本图层。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | 初始化一个新的 Layer 类实例。 |
| [Layer()](#Layer--) | 初始化一个新的 Layer 类实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 System.Object 是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 获取或设置文本图层的名称。 |
| [getText()](#getText--) | 获取或设置图层的文本内容。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 返回 XMP 格式中包含的字符串值。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEquals(Layer other)](#isEquals-com.aspose.psd.xmp.schemas.photoshop.Layer-) | 指示当前对象是否等于同一类型的另一个对象。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置文本图层的名称。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置图层的文本内容。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


初始化一个新的 Layer 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerName | java.lang.String | 图层的名称。 |
| layerText | java.lang.String | 图层文本。 |

### Layer() {#Layer--}
```
public Layer()
```


初始化一个新的 Layer 类实例。

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
### getName() {#getName--}
```
public String getName()
```


获取或设置文本图层的名称。

值：文本图层的名称。

**Returns:**
java.lang.String
### getText() {#getText--}
```
public String getText()
```


获取或设置图层的文本内容。

值：图层的文本内容。

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


返回 XMP 格式中包含的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### isEquals(Layer other) {#isEquals-com.aspose.psd.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


指示当前对象是否等于同一类型的另一个对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [Layer](../../com.aspose.psd.xmp.schemas.photoshop/layer) | 一个用于与此对象比较的对象。 |

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




### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


获取或设置文本图层的名称。

值：文本图层的名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


获取或设置图层的文本内容。

值：图层的文本内容。

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

