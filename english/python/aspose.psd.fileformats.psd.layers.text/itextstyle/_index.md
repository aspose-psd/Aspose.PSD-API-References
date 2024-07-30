---
title: ITextStyle Class
type: docs
weight: 40
url: /python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.6.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Gets or sets the auto kerning. |
| auto_leading | bool | r/w | Gets or sets a value indicating whether [automatic leading]. |
| baseline_shift | double | r/w | The baseline shift. |
| contextual_alternates | bool | r/w | The contextual alternates used to connect letters together. |
| discretionary_ligatures | bool | r/w | The discretionary ligatures used to connect letters, especially in script fonts. |
| faux_bold | bool | r/w | Gets or sets the faux bold is enabled. |
| faux_italic | bool | r/w | Gets or sets the faux bold is enabled. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets or sets the color of the fill. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | The font baseline. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | The font caps. |
| font_index | int | r | Gets the font index. |
| font_name | string | r/w | Gets or sets the font name. |
| font_size | double | r/w | Gets or sets the size of the font. |
| fractions | bool | r/w | The fractions symbols can be replaced with special glyph. |
| hindi_numbers | bool | r/w | Gets or sets a value indicating whether [hindi numbers]. |
| horizontal_scale | double | r/w | The horizontal scale. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Gets or sets the standard vertical Roman alignment.<br/>            This based on BaselineDirection resource value applies only when text orientation is [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | Gets or sets the kerning. |
| language_index | int | r | Gets the language index. |
| leading | double | r/w | Gets or sets the leading. |
| no_break | bool | r/w | Gets ot sets the no break value. |
| standard_ligatures | bool | r/w | The standard contextual ligatures used to connect letters together. |
| strikethrough | bool | r/w | Gets or sets a value indicating whether [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Gets or sets the color of the stroke. |
| tracking | int | r/w | Gets or sets the tracking. |
| underline | bool | r/w | Gets or sets a value indicating whether [underline]. |
| vertical_scale | double | r/w | The vertical scale. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(style)](#apply_style_1) | Applies the specified style. |
| [is_equal(style)](#is_equal_style_2) | Determines whether the specified style is equal. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Applies the specified style.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | The style. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Determines whether the specified style is equal.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | The style. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if the specified style is equal; otherwise, <c>false</c>. |


