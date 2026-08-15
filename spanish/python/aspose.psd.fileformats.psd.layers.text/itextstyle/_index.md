---
title: "Clase ITextStyle"
type: docs
weight: 40
url: /es/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Obtiene o establece el interletraje automático. |
| auto_leading | bool | r/w | Obtiene o establece un valor que indica si [automatic leading]. |
| baseline_shift | double | r/w | El desplazamiento de la línea base. |
| contextual_alternates | bool | r/w | Los alternados contextuales usados para conectar letras entre sí. |
| discretionary_ligatures | bool | r/w | Las ligaduras discrecionales usadas para conectar letras, especialmente en fuentes de escritura. |
| faux_bold | bool | r/w | Obtiene o establece si el faux bold está habilitado. |
| faux_italic | bool | r/w | Obtiene o establece si el faux bold está habilitado. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece el color del relleno. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | La línea base de la fuente. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Las mayúsculas de la fuente. |
| font_index | int | r | Obtiene el índice de la fuente. |
| font_name | string | r/w | Obtiene o establece el nombre de la fuente. |
| font_size | double | r/w | Obtiene o establece el tamaño de la fuente. |
| fractions | bool | r/w | Los símbolos de fracciones pueden ser reemplazados por un glifo especial. |
| hindi_numbers | bool | r/w | Obtiene o establece un valor que indica si [hindi numbers]. |
| horizontal_scale | double | r/w | La escala horizontal. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Obtiene o establece la alineación vertical romana estándar.<br/>            Esto, basado en el valor del recurso BaselineDirection, se aplica solo cuando la orientación del texto es [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | Obtiene o establece el interletraje. |
| language_index | int | r | Obtiene el índice de idioma. |
| leading | double | r/w | Obtiene o establece el interlineado. |
| no_break | bool | r/w | Obtiene o establece el valor de no break. |
| standard_ligatures | bool | r/w | Las ligaduras contextuales estándar utilizadas para conectar letras entre sí. |
| strikethrough | bool | r/w | Obtiene o establece un valor que indica si [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece el color del trazo. |
| tracking | int | r/w | Obtiene o establece el tracking. |
| underline | bool | r/w | Obtiene o establece un valor que indica si [underline]. |
| vertical_scale | double | r/w | La escala vertical. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [apply(style)](#apply_style_1) | Aplica el estilo especificado. |
| [is_equal(style)](#is_equal_style_2) | Determina si el estilo especificado es igual. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Aplica el estilo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | El estilo. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Determina si el estilo especificado es igual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | El estilo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si el estilo especificado es igual; de lo contrario, <c>false</c>. |


