---
title: "ITextStyle Classe"
type: docs
weight: 40
url: /it/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Ottiene o imposta l'auto kerning. |
| auto_leading | bool | r/w | Ottiene o imposta un valore che indica se [automatic leading]. |
| baseline_shift | double | r/w | Lo spostamento della linea di base. |
| contextual_alternates | bool | r/w | Le alternative contestuali usate per collegare le lettere insieme. |
| discretionary_ligatures | bool | r/w | Le legature discrezionali usate per collegare le lettere, specialmente nei font corsivi. |
| faux_bold | bool | r/w | Ottiene o imposta se il faux bold è abilitato. |
| faux_italic | bool | r/w | Ottiene o imposta se il faux bold è abilitato. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta il colore del riempimento. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | La linea di base del carattere. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Le maiuscole del carattere. |
| font_index | int | r | Ottiene l'indice del carattere. |
| font_name | string | r/w | Ottiene o imposta il nome del carattere. |
| font_size | double | r/w | Ottiene o imposta la dimensione del carattere. |
| fractions | bool | r/w | I simboli delle frazioni possono essere sostituiti con un glifo speciale. |
| hindi_numbers | bool | r/w | Ottiene o imposta un valore che indica se [hindi numbers]. |
| horizontal_scale | double | r/w | La scala orizzontale. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Ottiene o imposta l'allineamento verticale romano standard.<br/>            Questo, basato sul valore della risorsa BaselineDirection, si applica solo quando l'orientamento del testo è [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | Ottiene o imposta il kerning. |
| language_index | int | r | Ottiene l'indice della lingua. |
| leading | double | r/w | Ottiene o imposta il leading. |
| no_break | bool | r/w | Ottiene o imposta il valore no_break. |
| standard_ligatures | bool | r/w | Le ligature contestuali standard utilizzate per collegare le lettere insieme. |
| strikethrough | bool | r/w | Ottiene o imposta un valore che indica se [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta il colore del tratto. |
| tracking | int | r/w | Ottiene o imposta il tracking. |
| underline | bool | r/w | Ottiene o imposta un valore che indica se [underline]. |
| vertical_scale | double | r/w | La scala verticale. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(style)](#apply_style_1) | Applica lo stile specificato. |
| [is_equal(style)](#is_equal_style_2) | Determina se lo stile specificato è uguale. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Applica lo stile specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Lo stile. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Determina se lo stile specificato è uguale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Lo stile. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se lo stile specificato è uguale; altrimenti, <c>false</c>. |


