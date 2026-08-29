---
title: "Classe ITextStyle"
type: docs
weight: 40
url: /fr/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Obtient ou définit le crénage automatique. |
| auto_leading | bool | r/w | Obtient ou définit une valeur indiquant si [espacement automatique]. |
| baseline_shift | double | r/w | Le décalage de la ligne de base. |
| contextual_alternates | bool | r/w | Les alternatives contextuelles utilisées pour connecter les lettres entre elles. |
| discretionary_ligatures | bool | r/w | Les ligatures discrétionnaires utilisées pour connecter les lettres, notamment dans les polices cursives. |
| faux_bold | bool | r/w | Obtient ou définit si le faux gras est activé. |
| faux_italic | bool | r/w | Obtient ou définit si le faux gras est activé. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit la couleur du remplissage. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | La ligne de base de la police. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Les majuscules de la police. |
| font_index | int | r | Obtient l'index de la police. |
| font_name | chaîne | r/w | Obtient ou définit le nom de la police. |
| font_size | double | r/w | Obtient ou définit la taille de la police. |
| fractions | bool | r/w | Les symboles de fractions peuvent être remplacés par un glyphe spécial. |
| hindi_numbers | bool | r/w | Obtient ou définit une valeur indiquant si [nombres hindi]. |
| horizontal_scale | double | r/w | L'échelle horizontale. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Obtient ou définit l'alignement romain vertical standard.<br/>            Cela, basé sur la valeur de la ressource BaselineDirection, ne s'applique que lorsque l'orientation du texte est [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | Obtient ou définit le kerning. |
| language_index | int | r | Obtient l'index de langue. |
| leading | double | r/w | Obtient ou définit le leading. |
| no_break | bool | r/w | Obtient ou définit la valeur no_break. |
| standard_ligatures | bool | r/w | Les ligatures contextuelles standard utilisées pour connecter les lettres entre elles. |
| strikethrough | bool | r/w | Obtient ou définit une valeur indiquant si [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit la couleur du trait. |
| tracking | int | r/w | Obtient ou définit le tracking. |
| underline | bool | r/w | Obtient ou définit une valeur indiquant si [underline]. |
| vertical_scale | double | r/w | L'échelle verticale. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(style)](#apply_style_1) | Applique le style spécifié. |
| [is_equal(style)](#is_equal_style_2) | Détermine si le style spécifié est égal. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Applique le style spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Le style. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Détermine si le style spécifié est égal.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Le style. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si le style spécifié est égal ; sinon, <c>false</c>. |


