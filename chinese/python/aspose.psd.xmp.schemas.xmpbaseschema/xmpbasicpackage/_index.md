---
title: "XmpBasicPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | 初始化一个新的 [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) 类实例。 |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | 初始化一个新的 [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | 评级最大值。 |
| RATING_MIN [static] | int | r | 评级最小值。 |
| RATING_REJECTED [static] | int | r | 评级拒绝值。 |
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
| [set_created_date(created_date)](#set_created_date_created_date_5) | 添加资源创建日期。 |
| [set_created_date(created_date)](#set_created_date_created_date_6) | 添加资源创建日期。 |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | 设置创建工具。 |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | 设置标识符。 |
| [set_label(label)](#set_label_label_9) | 设置标签。 |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | 添加元数据最后更改日期。 |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | 添加元数据最后更改日期。 |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | 添加资源最后修改日期。 |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | 添加资源最后修改日期。 |
| [set_rating(choise)](#set_rating_choise_14) | 设置评级。 |
| [set_value(key, value)](#set_value_key_value_15) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | 设置 XMP 类型值。 |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

初始化一个新的 [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) 类实例。

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

初始化一个新的 [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 前缀 | 字符串 | 前缀。 |
| namespace_uri | 字符串 | 命名空间 URI。 |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

添加资源创建日期。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| created_date | datetime | 创建日期。 |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

添加资源创建日期。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| created_date | 字符串 | 创建日期。 |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

设置创建工具。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| creator_tool | 字符串 | 工具名称。 |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

设置标识符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| idenfifier | 字符串 | 该 idenfifier。 |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

设置标签。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| label | 字符串 | 该标签。 |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

添加元数据最后更改日期。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| metadata_date | datetime | 元数据日期。 |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

添加元数据最后更改日期。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| metadata_date | 字符串 | 元数据日期。 |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

添加资源最后修改日期。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| modified_date | datetime | 最后修改日期。 |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

添加资源最后修改日期。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| modified_date | 字符串 | 最后修改日期。 |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

设置评级。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| choise | int | 从 -1 到 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 要添加的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 键的字符串表示形式，该键与设置的值关联。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 要设置的值。 |

