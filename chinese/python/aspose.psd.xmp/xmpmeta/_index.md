---
title: "XmpMeta 类"
type: docs
weight: 410
url: /zh/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | 初始化 [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) 类的新实例。 |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | 初始化 [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | 字符串 | 读/写 | 获取或设置 Adobe Xmp 工具包版本。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | 添加属性。 |
| clear_attributes() | 移除所有属性。 |
| [get_attribute(attribute)](#get_attribute_attribute_2) | 获取属性。 |
| [get_xml_value()](#get_xml_value__3) | 将 XMP 值转换为 XML 表示形式。 |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

初始化 [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) 类的新实例。

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

初始化 [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| toolkit_version | 字符串 | Adobe XMP 工具包版本。 |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

添加属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 属性 | 字符串 | 属性。 |
| value | 字符串 | 值。 |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

获取属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 属性 | 字符串 | 属性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 返回指定属性名称的属性。 |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示形式。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 返回转换为 XML 表示形式的 XMP 值。 |


