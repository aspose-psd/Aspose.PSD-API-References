---
title: "ITextStyle Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Liest oder setzt das automatische Kerning. |
| auto_leading | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [automatic leading] verwendet wird. |
| baseline_shift | double | r/w | Die Grundlinienverschiebung. |
| contextual_alternates | bool | r/w | Die kontextbezogenen Alternativen, die verwendet werden, um Buchstaben zu verbinden. |
| discretionary_ligatures | bool | r/w | Die fakultativen Ligaturen, die verwendet werden, um Buchstaben zu verbinden, insbesondere in Schreibschrift-Schriften. |
| faux_bold | bool | r/w | Liest oder setzt, ob Faux-Bold aktiviert ist. |
| faux_italic | bool | r/w | Liest oder setzt, ob Faux-Bold aktiviert ist. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt die Füllfarbe. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | Die Schriftgrundlinie. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Die Großbuchstaben der Schrift. |
| font_index | int | r | Liest den Schriftindex. |
| font_name | string | r/w | Liest oder setzt den Schriftartnamen. |
| font_size | double | r/w | Liest oder setzt die Schriftgröße. |
| fractions | bool | r/w | Die Bruchzeichen können durch spezielle Glyphen ersetzt werden. |
| hindi_numbers | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [hindi numbers]. |
| horizontal_scale | double | r/w | Die horizontale Skalierung. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Liest oder setzt die standardmäßige vertikale römische Ausrichtung.<br/>            Dieser basierend auf dem BaselineDirection-Ressourcenwert gilt nur, wenn die Textorientierung [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/) ist. |
| kerning | int | r/w | Liest oder setzt das Kerning. |
| language_index | int | r | Liest den Sprachindex. |
| leading | double | r/w | Liest oder setzt das Leading. |
| no_break | bool | r/w | Liest oder setzt den No‑Break‑Wert. |
| standard_ligatures | bool | r/w | Die standardmäßigen kontextuellen Ligaturen, die zum Verbinden von Buchstaben verwendet werden. |
| strikethrough | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt die Farbe des Strichs. |
| tracking | int | r/w | Liest oder setzt das Tracking. |
| underline | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [underline]. |
| vertical_scale | double | r/w | Die vertikale Skalierung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [apply(style)](#apply_style_1) | Wendet den angegebenen Stil an. |
| [is_equal(style)](#is_equal_style_2) | Bestimmt, ob der angegebene Stil gleich ist. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Wendet den angegebenen Stil an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Der Stil. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Bestimmt, ob der angegebene Stil gleich ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Der Stil. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn der angegebene Stil gleich ist; andernfalls <c>false</c>. |


