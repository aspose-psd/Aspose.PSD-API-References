---
title: "ITextParagraph Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---

**Summary:** The interface to work with paragraph

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextParagraph

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| auto_hyphenate | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [automatic hyphenate]. |
| auto_leading | double | r/w | Liest oder setzt den automatischen Zeilenabstand. |
| burasagari | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/) burasagiri ist. |
| consecutive_hyphens | int | r/w | Liest oder setzt die aufeinanderfolgenden Bindestriche. |
| end_indent | double | r/w | Liest oder setzt den Endeinzug. |
| every_line_composer | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [every line composer]. |
| first_line_indent | double | r/w | Liest oder setzt den ersten Zeileneinzug. |
| glyph_spacing | double | r/w | Liest oder setzt den Glyphenabstand. |
| hanging | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieser [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/) hängend ist. |
| hyphenated_word_size | int | r/w | Liest oder setzt die Größe des getrennten Wortes. |
| justification | [JustificationMode](/psd/python-net/aspose.psd.fileformats.psd/justificationmode) | r/w | Liest oder setzt die Ausrichtung. |
| kinsoku_order | int | r/w | Liest oder setzt die Kinsoku‑Reihenfolge. |
| leading_type | [LeadingType](/psd/python-net/aspose.psd.fileformats.psd/leadingtype) | r/w | Liest oder setzt den Typ des Zeilenabstands. |
| letter_spacing | double | r/w | Liest oder setzt den Buchstabenabstand. |
| post_hyphen | int | r/w | Liest oder setzt den nachfolgenden Bindestrich. |
| pre_hyphen | int | r/w | Liest oder setzt den vorangestellten Bindestrich. |
| space_after | double | r/w | Liest oder setzt den Abstand nach. |
| space_before | double | r/w | Liest oder setzt den Abstand vor. |
| start_indent | double | r/w | Liest oder setzt den Anfangseinzug. |
| word_spacing | double | r/w | Liest oder setzt den Wortabstand. |
| zone | double | r/w | Liest oder setzt die Zone. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [apply(paragraph)](#apply_paragraph_1) | Wendet den angegebenen Absatz an. |
| [is_equal(paragraph)](#is_equal_paragraph_2) | Bestimmt, ob der angegebene Absatz gleich ist. |


### Method: apply(paragraph) {#apply_paragraph_1}


```
 apply(paragraph) 
```

Wendet den angegebenen Absatz an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Der Absatz. |

### Method: is_equal(paragraph) {#is_equal_paragraph_2}


```
 is_equal(paragraph) 
```

Bestimmt, ob der angegebene Absatz gleich ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Der Absatz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn der angegebene Absatz gleich ist; andernfalls <c>false</c>. |


