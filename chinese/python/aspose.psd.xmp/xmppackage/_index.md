---
title: "XmpPackage 类"
type: docs
weight: 430
url: /zh/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | 字符串 | r | 获取命名空间 URI。 |
| 前缀 | 字符串 | r | 获取前缀。 |
| xml_namespace | 字符串 | r | 获取 XML 命名空间。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 添加该值。 |
| clear() | 清除此实例。 |
| [contains_key(key)](#contains_key_key_2) | 确定指定的键是否包含键。 |
| [get_xml_value()](#get_xml_value__3) | 将 XMP 值转换为 XML 表示形式。 |
| [remove(key)](#remove_key_4) | 删除具有指定键的值。 |
| [set_value(key, value)](#set_value_key_value_5) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | 设置 XMP 类型值。 |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

添加该值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | 字符串 | 要添加的值。 |

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


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 要添加的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 键的字符串表示形式，该键与设置的值关联。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 要设置的值。 |

