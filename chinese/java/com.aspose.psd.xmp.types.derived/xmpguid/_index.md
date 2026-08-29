---
title: "XmpGuid"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 XMP 全局唯一标识符。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.xmp.types.derived/xmpguid/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

表示 XMP 全局唯一标识符。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | 初始化 XmpGuid 类的新实例。 |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | 初始化 XmpGuid 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPrefix()](#getPrefix--) | 获取或设置类似 uuid 的前缀。 |
| [getValue()](#getValue--) | 获取或设置该值。 |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | 获取或设置类似 uuid 的前缀。 |
| [setValue(UUID value)](#setValue-java.util.UUID-) | 获取或设置该值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


初始化 XmpGuid 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 该值。 |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


初始化 XmpGuid 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| GUID | java.util.UUID | 唯一标识符。 |

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
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取或设置类似 uuid 的前缀。

值：类似 uuid 的前缀。

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public UUID getValue()
```


获取或设置该值。

值：该值。

**Returns:**
java.util.UUID
### getValue_internalized() {#getValue-internalized--}
```
public System.Guid getValue_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
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




### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


获取或设置类似 uuid 的前缀。

值：类似 uuid 的前缀。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


获取或设置该值。

值：该值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

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

