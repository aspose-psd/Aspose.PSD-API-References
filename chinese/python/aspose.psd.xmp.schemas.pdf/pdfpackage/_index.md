---
title: "PdfPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | 初始化 PdfPackage 类的新实例 |
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
| [set_keywords(keywords)](#set_keywords_keywords_5) | 设置关键字。 |
| [set_pdf_version(version)](#set_pdf_version_version_6) | 设置 PDF 版本。 |
| [set_producer(producer)](#set_producer_producer_7) | 设置创建 PDF 的工具名称。 |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | 设置 trapped。 |
| [set_value(key, value)](#set_value_key_value_9) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | 设置 XMP 类型值。 |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

初始化 PdfPackage 类的新实例

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

设置关键字。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 关键字 | 字符串 | 关键字。 |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

设置 PDF 版本。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| version | 字符串 | PDF 版本，例如：1.0、1.3 等。 |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

设置创建 PDF 的工具名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 生成器 | 字符串 | 生成器名称。 |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

设置 trapped。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| is_trapped | bool | 如果设置为 <c>true</c>，文档已被 trapped。 |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 标识已添加值的 key 的字符串表示形式。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 要添加的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| key | 字符串 | 键的字符串表示形式，该键与设置的值关联。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 要设置的值。 |

