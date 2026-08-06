---
title: "XmpBasicPackage"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 XMP 基本命名空间。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

表示 XMP 基本命名空间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | 初始化 XmpBasicPackage 类的新实例。 |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | 初始化 XmpBasicPackage 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [RatingMax](#RatingMax) | 评级最大值。 |
| [RatingMin](#RatingMin) | 评级最小值。 |
| [RatingRejected](#RatingRejected) | 评级拒绝值。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | 添加复合类型命名空间。 |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | 添加字符串属性。 |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | 将指定的 XMP 包分配给当前包。 |
| [clear()](#clear--) | 清除此实例。 |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | 合并该包。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 确定指定的键是否包含键。 |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | 获取 XMP 包中的键。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取命名空间 URI。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getXmlNamespace()](#getXmlNamespace--) | 获取 XML 命名空间。 |
| [getXmlValue()](#getXmlValue--) | 将 XMP 值转换为 XML 表示。 |
| [get_Item(String key)](#get-Item-java.lang.String-) | 获取或设置具有指定键的对象。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | 删除具有指定键的值。 |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | 添加资源创建日期。 |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | 添加资源创建日期。 |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | 设置创建者工具。 |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | 设置标识符。 |
| [setLabel(String label)](#setLabel-java.lang.String-) | 设置标签。 |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | 添加元数据最后更改日期。 |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | 添加元数据最后更改日期。 |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | 添加资源最后修改日期。 |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | 添加资源最后修改日期。 |
| [setRating(int choise)](#setRating-int-) | 设置评级。 |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 设置值。 |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | 设置 XMP 布尔值。 |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | 设置 XMP 唯一标识符。 |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | 设置 XMP 类型值。 |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 获取或设置具有指定键的对象。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


初始化 XmpBasicPackage 类的新实例。

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


初始化 XmpBasicPackage 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |
| namespaceUri | java.lang.String | 命名空间 URI。 |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


评级最大值。

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


评级最小值。

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


评级拒绝值。

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


添加复合类型命名空间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| typePrefix | java.lang.String | 类型前缀。 |
| typeNamespaceUri | java.lang.String | 类型命名空间 URI。 |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


添加字符串属性。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | key 的字符串表示形式，用于标识已添加的值。 |
| 值 | java.lang.String | 字符串值。 |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


将指定的 XMP 包分配给当前包。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | XMP 包。 |

### clear() {#clear--}
```
public void clear()
```


清除此实例。

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


合并该包。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 要合并的另一个包。 |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


确定指定的键是否包含键。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 要检查的键。 |

**Returns:**
boolean - 如果指定的键包含键则返回 true。
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


克隆此实例。

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


获取 XMP 包中的键。

值：XMP 包中的键。

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取命名空间 URI。

值：命名空间 URI。

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

值：前缀。

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


获取 XML 命名空间。

值：XML 命名空间。

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 XMP 值转换为 XML 表示。

**Returns:**
java.lang.String - 返回转换为 XML 表示的 XMP 值。
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


获取或设置具有指定键的对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 标识值的键。值：Object。 |

**Returns:**
java.lang.Object - 返回具有指定键的 Object。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


返回一个遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - 一个可用于遍历集合的  T:System.Collections.Generic.IEnumerator1 。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


删除具有指定键的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 标识已删除值的键的字符串表示形式。 |

**Returns:**
boolean - 如果已删除具有指定键的值，则返回 true。
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


添加资源创建日期。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| createdDate | java.lang.String | 创建日期。 |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


添加资源创建日期。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | 创建日期。 |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


设置创建者工具。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| creatorTool | java.lang.String | 工具名称。 |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


设置标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 标识符 | java.lang.String[] | 该标识符。 |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


设置标签。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 标签 | java.lang.String | 该标签。 |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


添加元数据最后更改日期。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| metadataDate | java.lang.String | 元数据日期。 |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


添加元数据最后更改日期。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | 元数据日期。 |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


添加资源最后修改日期。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| modifiedDate | java.lang.String | 最后修改日期。 |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


添加资源最后修改日期。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | 最后修改日期。 |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


设置评级。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 选择 | int | 从 -1 到 5 |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


设置值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | key 的字符串表示形式，用于标识已添加的值。 |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | 要添加到的值。 |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


设置 XMP 布尔值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 键的字符串表示形式，用于标识已设置的值。 |
| 布尔值 | java.lang.String | 布尔值。 |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


设置 XMP 唯一标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 键的字符串表示形式，用于标识已设置的 GUID 值。 |
| GUID | java.lang.String | 唯一标识符。 |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


设置 XMP 类型值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 键的字符串表示形式，用于标识已设置的值。 |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | 要设置的值。 |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


获取或设置具有指定键的对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 标识值的键。值：Object。 |
| 值 | java.lang.Object |  |

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

