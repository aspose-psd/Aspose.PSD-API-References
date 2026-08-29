---
title: "XmpPacketWrapper"
second_title: "Aspose.PSD 的 Java API 参考"
description: "包含已序列化的 xmp 包，包括头部和尾部。"
type: docs
weight: 20
url: /zh/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

包含已序列化的 xmp 包，包括头部和尾部。

一个由一对 XML 处理指令（PIs）组成的包装器可以放置在 rdf:RDF 元素周围。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | 初始化 XmpPacketWrapper 类的新实例。 |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | 初始化 XmpPacketWrapper 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | 添加该包。 |
| [clearPackages()](#clearPackages--) | 移除 XMP 中的所有 XmpPackage。 |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | 确定 XMP 包是否存在于包装器中。 |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | 获取标题处理指令。 |
| [getMeta()](#getMeta--) | 获取 XMP 元数据。 |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | 按命名空间 URI 获取包。 |
| [getPackages()](#getPackages--) | 获取 XMP 中的 XmpPackage 数组。 |
| [getPackagesCount()](#getPackagesCount--) | 获取 XMP 结构中包的数量。 |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | 获取根 RDF 元素。 |
| [getTrailerPi()](#getTrailerPi--) | 获取尾部处理指令。 |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | 将 XMP 值转换为 XML 表示。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | 移除 XMP 包。 |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | 设置头部处理指令。 |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | 设置 XMP 元数据。 |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | 设置根 RDF 元素。 |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | 设置尾部处理指令。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


初始化 XmpPacketWrapper 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | XMP 处理指令的头部。 |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | XMP 处理指令的尾部。 |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP 元数据。 |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


初始化 XmpPacketWrapper 类的新实例。

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


添加该包。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 该包。 |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


移除 XMP 中的所有 XmpPackage。

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


确定 XMP 包是否存在于包装器中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| namespaceUri | java.lang.String | 包模式 URI。 |

**Returns:**
boolean - 如果 XMP 包装器中存在具有指定命名空间 Uri 的包，则返回 true。
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


克隆此实例。

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


获取标题处理指令。

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


获取 XMP 元数据。可选。

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


按命名空间 URI 获取包。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| namespaceUri | java.lang.String | 包模式 URI。 |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


获取 XMP 中的 XmpPackage 数组。

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - XMP 中的 XmpPackage 数组。
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


获取 XMP 结构中包的数量。

**Returns:**
int - XMP 结构中包的数量。
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


获取根 RDF 元素。

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


获取尾部处理指令。

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


将 XMP 值转换为 XML 表示。

**Returns:**
java.lang.String - 返回转换为 XML 的 XMP 值。
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


移除 XMP 包。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 该包。 |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


设置头部处理指令。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | 头部处理指令。 |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


设置 XMP 元数据。可选。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP 元数据。可选。 |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


设置根 RDF 元素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | RDF 根元素。 |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


设置尾部处理指令。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | 尾部处理指令。 |

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

