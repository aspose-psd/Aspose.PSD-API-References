---
title: Font Class
type: docs
weight: 1330
url: /python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size. The character set is set to [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), the graphics unit to [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), the font style to [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size and style. The character set is set to [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), the graphics unit to [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size, style, and unit. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size, style, unit, and character set. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size and unit. The character set is set to [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), the style is set to [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Initializes a new [Font](/psd/python-net/aspose.psd/font/) that uses the specified existing [Font](/psd/python-net/aspose.psd/font/) and [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeration. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bold | bool | r | Gets a value indicating whether this [Font](/psd/python-net/aspose.psd/font/) is bold. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Gets a byte value that specifies the character set that this [Font](/psd/python-net/aspose.psd/font/) uses. |
| italic | bool | r | Gets a value indicating whether this [Font](/psd/python-net/aspose.psd/font/) is italic. |
| name | string | r | Gets the face name of this [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Gets the em-size of this [Font](/psd/python-net/aspose.psd/font/) measured in the units specified by the [Font.unit](/psd/python-net/aspose.psd/font/) property. |
| strikeout | bool | r | Gets a value indicating whether this [Font](/psd/python-net/aspose.psd/font/) specifies a horizontal line through the font. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Gets style information for this [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Gets a value indicating whether this [Font](/psd/python-net/aspose.psd/font/) is underlined. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Gets the unit of measure for this [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Creates an exact deep copy of this [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size. The character set is set to [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), the graphics unit to [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), the font style to [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/psd/python-net/aspose.psd/font/) name. |
| em_size | float | The em-size, in points, of the new font. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size and style. The character set is set to [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), the graphics unit to [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/psd/python-net/aspose.psd/font/) name. |
| em_size | float | The em-size, in points, of the new font. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | The [FontStyle](/psd/python-net/aspose.psd/fontstyle/) of the new font. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size, style, and unit.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/psd/python-net/aspose.psd/font/) name. |
| em_size | float | The em-size of the new font in the units specified by the <paramref name="unit" /> parameter. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | The [FontStyle](/psd/python-net/aspose.psd/fontstyle/) of the new font. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) of the new font. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size, style, unit, and character set.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/psd/python-net/aspose.psd/font/) name. |
| em_size | float | The em-size of the new font in the units specified by the <paramref name="unit" /> parameter. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | The [FontStyle](/psd/python-net/aspose.psd/fontstyle/) of the new font. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) of the new font. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | A character set to use for this font. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Initializes a new [Font](/psd/python-net/aspose.psd/font/) using a specified size and unit. The character set is set to [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), the style is set to [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | A string representation of the [Font](/psd/python-net/aspose.psd/font/) name. |
| em_size | float | The em-size of the new font in the units specified by the <paramref name="unit" /> parameter. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) of the new font. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Initializes a new [Font](/psd/python-net/aspose.psd/font/) that uses the specified existing [Font](/psd/python-net/aspose.psd/font/) and [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeration.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | The existing [Font](/psd/python-net/aspose.psd/font/) from which to create the new [Font](/psd/python-net/aspose.psd/font/). |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | The [FontStyle](/psd/python-net/aspose.psd/fontstyle/) to apply to the new [Font](/psd/python-net/aspose.psd/font/). Multiple values of the [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeration can be combined with the OR operator. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Creates an exact deep copy of this [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Type | Description |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | The [Font](/psd/python-net/aspose.psd/font/) this method creates. |


