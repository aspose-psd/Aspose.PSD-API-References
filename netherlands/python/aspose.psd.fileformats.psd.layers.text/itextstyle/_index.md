---
title: "ITextStyle Klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Haalt de automatische kerning op of stelt deze in. |
| auto_leading | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of [automatic leading] is. |
| baseline_shift | double | r/w | De baselineverschuiving. |
| contextual_alternates | bool | r/w | De contextuele alternatieven die worden gebruikt om letters met elkaar te verbinden. |
| discretionary_ligatures | bool | r/w | De discretionaire ligaturen die worden gebruikt om letters te verbinden, vooral in scriptlettertypen. |
| faux_bold | bool | r/w | Haalt op of stelt in of faux bold is ingeschakeld. |
| faux_italic | bool | r/w | Haalt op of stelt in of faux bold is ingeschakeld. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt de vulkleur op of stelt deze in. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | De lettertype-baseline. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | De hoofdletters van het lettertype. |
| font_index | int | r | Haalt de lettertype-index op. |
| font_name | string | r/w | Haalt of stelt de lettertype‑naam in. |
| font_size | double | r/w | Haalt de grootte van het lettertype op of stelt deze in. |
| fractions | bool | r/w | De breuktekens kunnen worden vervangen door een speciaal glyph. |
| hindi_numbers | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of [hindi numbers] is. |
| horizontal_scale | double | r/w | De horizontale schaal. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Haalt de standaard verticale Romeinse uitlijning op of stelt deze in.<br/>            Dit, gebaseerd op de BaselineDirection resourcewaarde, is alleen van toepassing wanneer de tekstoriëntatie [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/) is. |
| kerning | int | r/w | Haalt of stelt de kerning in. |
| language_index | int | r | Haalt de taalindex op. |
| leading | double | r/w | Haalt of stelt de leading in. |
| no_break | bool | r/w | Haalt of stelt de no-break-waarde in. |
| standard_ligatures | bool | r/w | De standaard contextuele ligaturen die worden gebruikt om letters met elkaar te verbinden. |
| strikethrough | bool | r/w | Haalt of stelt een waarde in die aangeeft of [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt of stelt de kleur van de lijn in. |
| tracking | int | r/w | Haalt of stelt de tracking in. |
| underline | bool | r/w | Haalt of stelt een waarde in die aangeeft of [underline]. |
| vertical_scale | double | r/w | De verticale schaal. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [apply(style)](#apply_style_1) | Past de opgegeven stijl toe. |
| [is_equal(style)](#is_equal_style_2) | Bepaalt of de opgegeven stijl gelijk is. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Past de opgegeven stijl toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | De stijl. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Bepaalt of de opgegeven stijl gelijk is.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | De stijl. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als de opgegeven stijl gelijk is; anders <c>false</c>. |


