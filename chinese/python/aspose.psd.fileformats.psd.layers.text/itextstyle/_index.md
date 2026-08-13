---
title: "ITextStyle 类"
type: docs
weight: 40
url: /zh/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | 获取或设置自动字距调整。 |
| auto_leading | bool | 读/写 | 获取或设置指示是否为[自动行距]的值。 |
| baseline_shift | double | 读/写 | 基线偏移。 |
| contextual_alternates | bool | 读/写 | 用于将字母连接在一起的上下文替代字形。 |
| discretionary_ligatures | bool | 读/写 | 用于连接字母的可选连字，尤其在手写体字体中。 |
| faux_bold | bool | 读/写 | 获取或设置 faux bold 是否已启用。 |
| faux_italic | bool | 读/写 | 获取或设置 faux bold 是否已启用。 |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置填充的颜色。 |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | 字体基线。 |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | 字体大写。 |
| font_index | int | r | 获取字体索引。 |
| font_name | 字符串 | 读/写 | 获取或设置字体名称。 |
| font_size | double | 读/写 | 获取或设置字体的大小。 |
| fractions | bool | 读/写 | 分数符号可以替换为特殊字形。 |
| hindi_numbers | bool | 读/写 | 获取或设置一个值，指示是否 [hindi numbers]。 |
| horizontal_scale | double | 读/写 | 水平比例。 |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | 获取或设置标准的垂直罗马对齐。<br/>            这基于 BaselineDirection 资源值，仅在文本方向为 [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/) 时适用。 |
| kerning | int | 读/写 | 获取或设置字距。 |
| language_index | int | r | 获取语言索引。 |
| leading | double | 读/写 | 获取或设置行距。 |
| no_break | bool | 读/写 | 获取或设置 no break 值。 |
| standard_ligatures | bool | 读/写 | 用于将字母连接在一起的标准上下文连字。 |
| strikethrough | bool | 读/写 | 获取或设置一个值，指示是否为 [strikethrough]。 |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置笔画的颜色。 |
| tracking | int | 读/写 | 获取或设置跟踪。 |
| underline | bool | 读/写 | 获取或设置一个值，指示是否为 [underline]。 |
| vertical_scale | double | 读/写 | 垂直比例。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(style)](#apply_style_1) | 应用指定的样式。 |
| [is_equal(style)](#is_equal_style_2) | 确定指定的样式是否相等。 |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

应用指定的样式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | 样式。 |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

确定指定的样式是否相等。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | 样式。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果指定的样式相等；否则为 <c>false</c>。 |


