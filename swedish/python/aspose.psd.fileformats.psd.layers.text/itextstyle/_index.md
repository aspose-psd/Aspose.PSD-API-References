---
title: "ITextStyle klass"
type: docs
weight: 40
url: /sv/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Hämtar eller anger automatisk kerning. |
| auto_leading | bool | r/w | Hämtar eller anger ett värde som indikerar om [automatic leading] är aktiverat. |
| baseline_shift | double | r/w | Baslinjeförskjutningen. |
| contextual_alternates | bool | r/w | De kontextuella alternativen som används för att koppla ihop bokstäver. |
| discretionary_ligatures | bool | r/w | De valfria ligaturerna som används för att koppla ihop bokstäver, särskilt i skriptfonter. |
| faux_bold | bool | r/w | Hämtar eller anger om faux bold är aktiverat. |
| faux_italic | bool | r/w | Hämtar eller anger om faux bold är aktiverat. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger fyllningsfärgen. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | Fontens baslinje. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Fontens versaler. |
| font_index | int | r | Hämtar fontens index. |
| font_name | string | r/w | Hämtar eller anger teckensnittets namn. |
| font_size | double | r/w | Hämtar eller anger storleken på fonten. |
| bråktal | bool | r/w | Bråktalsymbolerna kan ersättas med ett specialtecken. |
| hindi_numbers | bool | r/w | Hämtar eller anger ett värde som indikerar om [hindi numbers]. |
| horizontal_scale | double | r/w | Den horisontella skalan. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Hämtar eller anger den standardvertikala romerska justeringen.<br/>            Detta, baserat på BaselineDirection-resursvärdet, gäller endast när textorienteringen är [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | Hämtar eller anger kerning. |
| language_index | int | r | Hämtar språkindexet. |
| leading | double | r/w | Hämtar eller anger leading. |
| no_break | bool | r/w | Hämtar eller anger värdet för no break. |
| standard_ligatures | bool | r/w | De standardkontextuella ligaturerna som används för att koppla ihop bokstäver. |
| strikethrough | bool | r/w | Hämtar eller anger ett värde som indikerar om [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger färgen på strecket. |
| spårning | int | r/w | Hämtar eller anger spårningen. |
| understrykning | bool | r/w | Hämtar eller anger ett värde som indikerar om [understrykning]. |
| vertikal_skala | double | r/w | Den vertikala skalan. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [apply(style)](#apply_style_1) | Tillämpar den angivna stilen. |
| [is_equal(style)](#is_equal_style_2) | Avgör om den angivna stilen är lika. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Tillämpar den angivna stilen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Stilen. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Avgör om den angivna stilen är lika.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Stilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om den angivna stilen är lika; annars, <c>false</c>. |


