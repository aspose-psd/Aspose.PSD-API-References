---
title: "StringFormat 类"
type: docs
weight: 4260
url: /zh/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | 初始化一个新的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。 |
| [StringFormat(format)](#StringFormat_format_2) | 从指定的现有 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象初始化一个新的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。 |
| [StringFormat(options)](#StringFormat_options_3) | 使用指定的 [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 枚举和语言初始化一个新的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | 获取或设置垂直平面上的文本对齐信息。 |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | 获取或设置自定义字符标识。 |
| digit_substitution_language | int | 读/写 | 获取或设置在本地数字替换为西方数字时使用的语言。 |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | 获取或设置用于数字替换的方法。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| first_tab_offset | float | r | 获取文本行起始与第一个制表位之间的空格数。 |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | 获取或设置一个包含格式信息的 [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 枚举。 |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | 获取一个通用默认的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。 |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | 获取一个通用排版的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。 |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | 获取或设置此 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象的 [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) 对象。 |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | 获取或设置水平平面上的行对齐方式。 |
| tab_stops | float | r | 获取一个数组，包含由 [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) 属性指定单位的制表位之间的距离。 |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | 获取或设置此 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象的 [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) 枚举。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 创建此 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象的深度克隆。 |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | 为此 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象设置制表位。 |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

初始化一个新的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

从指定的现有 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象初始化一个新的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 用于初始化新 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。 |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

使用指定的 [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 枚举和语言初始化一个新的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | 新 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象的 [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 枚举。 |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

创建此 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象的深度克隆。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | 当前 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 的深度克隆。 |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

为此 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 对象设置制表位。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| first_tab_offset | float | 文本行起始与第一个制表位之间的空格数。 |
| tab_stops | float | 由 [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) 属性指定单位的制表位之间距离的数组。 |

