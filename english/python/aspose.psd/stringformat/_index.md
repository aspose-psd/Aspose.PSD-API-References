---
title: StringFormat Class
type: docs
weight: 4190
url: /python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initializes a new [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| [StringFormat(format)](#StringFormat_format_2) | Initializes a new [StringFormat](/psd/python-net/aspose.psd/stringformat/) object from the specified existing [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| [StringFormat(options)](#StringFormat_options_3) | Initializes a new [StringFormat](/psd/python-net/aspose.psd/stringformat/) object with the specified [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeration and language. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Gets or sets text alignment information on the vertical plane. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the custom character ident. |
| digit_substitution_language | int | r/w | Gets or sets the language that is used when local digits are substituted for western digits. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Gets or sets the method to be used for digit substitution. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| first_tab_offset | float | r | Gets the number of spaces between the beginning of a line of text and the first tab stop. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Gets or sets a [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeration that contains formatting information. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Gets a generic default [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Gets a generic typographic [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Gets or sets the [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) object for this [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Gets or sets the line alignment on the horizontal plane. |
| tab_stops | float | r | Gets an array of distances between tab stops in the units specified by the [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) property. |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Gets or sets the [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) enumeration for this [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Creates a deep clone of this [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Sets tab stops for this [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initializes a new [StringFormat](/psd/python-net/aspose.psd/stringformat/) object.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initializes a new [StringFormat](/psd/python-net/aspose.psd/stringformat/) object from the specified existing [StringFormat](/psd/python-net/aspose.psd/stringformat/) object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | The [StringFormat](/psd/python-net/aspose.psd/stringformat/) object from which to initialize the new [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initializes a new [StringFormat](/psd/python-net/aspose.psd/stringformat/) object with the specified [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeration and language.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | The [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeration for the new [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Creates a deep clone of this [StringFormat](/psd/python-net/aspose.psd/stringformat/) object.

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | The deep clone of the current [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Sets tab stops for this [StringFormat](/psd/python-net/aspose.psd/stringformat/) object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| first_tab_offset | float | The number of spaces between the beginning of a line of text and the first tab stop. |
| tab_stops | float | An array of distances between tab stops in the units specified by the [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) property. |

