---
title: "PhotoshopPackage"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 Adobe Photoshop 命名空间。"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

表示 Adobe Photoshop 命名空间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | 初始化 PhotoshopPackage 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | 紧急程度最大值。 |
| [UrgencyMin](#UrgencyMin) | 紧急程度最小值。 |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | 获取或设置具有指定键的  Object  。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | 删除具有指定键的值。 |
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | 设置作者的位置。 |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | 设置标题编写者。 |
| [setCategory(String category)](#setCategory-java.lang.String-) | 设置类别。 |
| [setCity(String city)](#setCity-java.lang.String-) | 设置城市。 |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | 设置颜色模式。 |
| [setCountry(String country)](#setCountry-java.lang.String-) | 设置国家。 |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | 设置创建日期。 |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | 设置信用。 |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | 设置文档祖先。 |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | 设置标题。 |
| [setHistory(String history)](#setHistory-java.lang.String-) | 设置历史记录。 |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | 设置 icc 配置文件。 |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | 设置说明。 |
| [setSource(String source)](#setSource-java.lang.String-) | 设置来源。 |
| [setState(String state)](#setState-java.lang.String-) | 设置状态。 |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | 设置补充类别。 |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | 设置传输参考。 |
| [setUrgency(int urgency)](#setUrgency-int-) | 设置紧急程度。 |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 设置值。 |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | 设置 XMP 布尔值。 |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | 设置 XMP 唯一标识符。 |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | 设置 XMP 类型值。 |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 设置具有指定键的  Object  。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


初始化 PhotoshopPackage 类的新实例。

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


紧急程度最大值。

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


紧急程度最小值。

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


获取或设置具有指定键的  Object  。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 标识值的键。 |

**Returns:**
java.lang.Object - 返回具有指定键的  Object  。
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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


设置作者的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| authorsPosition | java.lang.String | 作者的位置。 |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


设置标题编写者。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| captionWriter | java.lang.String | 字幕编写器。 |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


设置类别。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| category | java.lang.String | 类别。 |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


设置城市。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| city | java.lang.String | 城市名称。 |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


设置颜色模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorMode | byte | 颜色模式。 |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


设置国家。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| country | java.lang.String | 国家。 |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


设置创建日期。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| createdDate | java.util.Date | 创建日期。 |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


设置信用。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| credit | java.lang.String | 信用。 |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


设置文档祖先。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ancestors | java.lang.String[] | 祖先。 |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


设置标题。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| headline | java.lang.String | 标题。 |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


设置历史记录。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| history | java.lang.String | 历史。 |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


设置 icc 配置文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| iccProfile | java.lang.String | ICC 配置文件。 |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


设置说明。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 说明 | java.lang.String | 说明。 |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


设置来源。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 来源 | java.lang.String | 来源。 |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


设置状态。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 状态 | java.lang.String | 状态。 |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


设置补充类别。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 补充类别 | java.lang.String[] | 补充类别。 |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


设置传输参考。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 传输参考 | java.lang.String | 传输参考。 |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


设置紧急程度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 紧急程度 | int | 紧急程度。 |

紧急程度应在 1 到 8 的范围内。 |

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


设置具有指定键的  Object  。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | 标识值的键。 |
| 值 | java.lang.Object | 对象值。 |

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

