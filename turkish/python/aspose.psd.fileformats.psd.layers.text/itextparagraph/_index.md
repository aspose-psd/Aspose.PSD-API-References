---
title: "ITextParagraph Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---

**Summary:** The interface to work with paragraph

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextParagraph

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| auto_hyphenate | bool | r/w | Bu değeri alır veya ayarlar; [automatic hyphenate] olup olmadığını gösterir. |
| auto_leading | double | r/w | Otomatik satır aralığını alır veya ayarlar. |
| burasagari | bool | r/w | Bu değeri alır veya ayarlar; bu [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/) öğesinin burasagiri olup olmadığını gösterir. |
| consecutive_hyphens | int | r/w | Ardışık tireleri alır veya ayarlar. |
| end_indent | double | r/w | Son girintiyi alır veya ayarlar. |
| every_line_composer | bool | r/w | Bu değeri alır veya ayarlar; [every line composer] olup olmadığını gösterir. |
| first_line_indent | double | r/w | İlk satır girintisini alır veya ayarlar. |
| glyph_spacing | double | r/w | Glif aralığını alır veya ayarlar. |
| hanging | bool | r/w | Bu değeri alır veya ayarlar; bu [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/) öğesinin asılı olup olmadığını gösterir. |
| hyphenated_word_size | int | r/w | Tireli kelimenin boyutunu alır veya ayarlar. |
| justification | [JustificationMode](/psd/python-net/aspose.psd.fileformats.psd/justificationmode) | r/w | Hizalamayı alır veya ayarlar. |
| kinsoku_order | int | r/w | Kinsoku sırasını alır veya ayarlar. |
| leading_type | [LeadingType](/psd/python-net/aspose.psd.fileformats.psd/leadingtype) | r/w | Ön boşluğun tipini alır veya ayarlar. |
| letter_spacing | double | r/w | Harf aralığını alır veya ayarlar. |
| post_hyphen | int | r/w | Son tireyi alır veya ayarlar. |
| pre_hyphen | int | r/w | Ön tireyi alır veya ayarlar. |
| space_after | double | r/w | Sonraki boşluğu alır veya ayarlar. |
| space_before | double | r/w | Öncesindeki boşluğu alır veya ayarlar. |
| start_indent | double | r/w | Başlangıç girintisini alır veya ayarlar. |
| word_spacing | double | r/w | Kelime aralığını alır veya ayarlar. |
| zone | double | r/w | Bölgeyi alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [apply(paragraph)](#apply_paragraph_1) | Belirtilen paragrafı uygular. |
| [is_equal(paragraph)](#is_equal_paragraph_2) | Belirtilen paragrafın eşit olup olmadığını belirler. |


### Method: apply(paragraph) {#apply_paragraph_1}


```
 apply(paragraph) 
```

Belirtilen paragrafı uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Paragraf. |

### Method: is_equal(paragraph) {#is_equal_paragraph_2}


```
 is_equal(paragraph) 
```

Belirtilen paragrafın eşit olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Paragraf. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer belirtilen paragraf eşitse; aksi takdirde <c>false</c>. |


