---
title: "XmpRdfRoot"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 rdfRDF 元素。"
type: docs
weight: 21
url: /zh/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

表示 rdf:RDF 元素。单个 XMP 包应使用单个 rdf:RDF XML 元素进行序列化。rdf:RDF 元素的内容应仅包含零个或多个 rdf:Description 元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | 初始化 XmpRdfRoot 类的新实例。 |
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
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | 根据特定前缀获取命名空间 URI。 |
| [getXmlValue()](#getXmlValue--) | 将 xmp 值转换为 xml 表示形式。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | 指示当前对象是否等于同一类型的另一个对象。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | 通过前缀添加命名空间 URI。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


初始化 XmpRdfRoot 类的新实例。

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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


根据特定前缀获取命名空间 URI。前缀可以不以 xmlns 开头。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |

**Returns:**
java.lang.String - 返回包的模式 URI。
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 xmp 值转换为 xml 表示形式。

**Returns:**
java.lang.String - 返回转换为 XML 字符串的 XMP 值。
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




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


通过前缀添加命名空间 URI。前缀可以不以 xmlns 开头。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |
| namespaceUri | java.lang.String | 包模式 URI。 |

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

