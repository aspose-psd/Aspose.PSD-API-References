---
title: "XmpMediaManagementPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | 初始化 XmpMediaManagementPackage 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | 字符串 | r | 获取命名空间 URI。 |
| 前缀 | 字符串 | r | 获取前缀。 |
| xml_namespace | 字符串 | r | 获取 XML 命名空间。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 添加字符串属性。 |
| clear() | 清除此实例。 |
| [contains_key(key)](#contains_key_key_2) | 确定指定的键是否包含键。 |
| [get_xml_value()](#get_xml_value__3) | 将 XMP 值转换为 XML 表示形式。 |
| [remove(key)](#remove_key_4) | 删除具有指定键的值。 |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | 设置派生自。 |
| [set_document_id(guid)](#set_document_id_guid_6) | 设置文档标识符。 |
| [set_document_id(guid)](#set_document_id_guid_7) | 设置文档标识符。 |
| [set_instance_id(guid)](#set_instance_id_guid_8) | 设置实例 ID。 |
| [set_instance_id(guid)](#set_instance_id_guid_9) | 设置实例 ID。 |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | 设置原始文档 ID。 |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | 设置原始文档 ID。 |
| [set_value(key, value)](#set_value_key_value_12) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | 设置 XMP 类型值。 |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

初始化 XmpMediaManagementPackage 类的新实例

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

添加字符串属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | 字符串 | 字符串值。 |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

确定指定的键是否包含键。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 要检查的键。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的键包含键，则返回 true。 |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示形式。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 返回转换为 XML 表示形式的 XMP 值。 |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

删除具有指定键的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已删除值的 key 的字符串表示形式。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果具有指定键的值已被删除，则返回 true。 |


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

设置派生自。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | 资源引用。 |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

设置文档标识符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| guid | Guid | 唯一标识符。 |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

设置文档标识符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| guid | 字符串 | 唯一标识符。 |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

设置实例 ID。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| guid | Guid | 唯一标识符。 |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

设置实例 ID。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| guid | 字符串 | 唯一标识符。 |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

设置原始文档 ID。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| guid | Guid | 唯一标识符。 |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

设置原始文档 ID。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| guid | 字符串 | 唯一标识符。 |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 要添加的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 键的字符串表示形式，该键与设置的值关联。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 要设置的值。 |

