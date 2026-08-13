---
title: "XmpArray 类"
type: docs
weight: 290
url: /zh/python-net/aspose.psd.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/). TODO: Array may contain complex data.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpArray

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpArray(type)](#XmpArray_type_1) | 初始化 [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 类的新实例。 |
| [XmpArray(type, items)](#XmpArray_type_items_2) | 初始化 [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| values | string | r | 获取位于 [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 中的值数组。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_item(item)](#add_item_item_1) | 添加新项。 |
| [get_xml_value()](#get_xml_value__2) | 将 XMP 值转换为 XML 表示形式。 |


### Constructor: XmpArray(type) {#XmpArray_type_1}


```
 XmpArray(type) 
```

初始化 [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | 数组的类型。 |

### Constructor: XmpArray(type, items) {#XmpArray_type_items_2}


```
 XmpArray(type, items) 
```

初始化 [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | 数组的类型。 |
| 项 | 字符串 | 项列表。 |

### Method: add_item(item) {#add_item_item_1}


```
 add_item(item) 
```

添加新项。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 项 | 字符串 | 要添加到项列表中的项。 |

### Method: get_xml_value() {#get_xml_value__2}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示形式。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 返回转换为 XML 表示形式的 XMP 值。 |


