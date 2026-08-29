---
title: "ITextStyle Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Otomatik harf aralığını alır veya ayarlar. |
| auto_leading | bool | r/w | Otomatik satır aralığını gösterip göstermediğini belirten bir değeri alır veya ayarlar. |
| baseline_shift | double | r/w | Taban kayması. |
| contextual_alternates | bool | r/w | Harfleri birleştirmek için kullanılan bağlamsal alternatifler. |
| discretionary_ligatures | bool | r/w | Özellikle el yazısı fontlarında harfleri birleştirmek için kullanılan isteğe bağlı birleşik karakterler. |
| faux_bold | bool | r/w | Sahte kalının etkin olup olmadığını alır veya ayarlar. |
| faux_italic | bool | r/w | Sahte kalının etkin olup olmadığını alır veya ayarlar. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Dolgu rengini alır veya ayarlar. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | Yazı tipi tabanı. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Yazı tipi büyük harfleri. |
| font_index | int | r | Yazı tipi dizinini alır. |
| font_name | string | r/w | Yazı tipi adını alır veya ayarlar. |
| font_size | double | r/w | Yazı tipi boyutunu alır veya ayarlar. |
| fractions | bool | r/w | Kesir sembolleri özel bir glif ile değiştirilebilir. |
| hindi_numbers | bool | r/w | Hint rakamlarını gösterip göstermediğini belirten bir değeri alır veya ayarlar. |
| horizontal_scale | double | r/w | Yatay ölçek. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Standart dikey Roman hizalamasını alır veya ayarlar.<br/>            Bu, BaselineDirection kaynak değerine dayanır ve yalnızca metin yönelimi [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/) olduğunda uygulanır. |
| kerning | int | r/w | Kerning değerini alır veya ayarlar. |
| language_index | int | r | Dil indeksini alır. |
| leading | double | r/w | Leading değerini alır veya ayarlar. |
| no_break | bool | r/w | No break değerini alır veya ayarlar. |
| standard_ligatures | bool | r/w | Harfleri birleştirmek için kullanılan standart bağlamsal ligatürler. |
| strikethrough | bool | r/w | Üstü çizili olup [strikethrough] olduğunu gösteren bir değeri alır veya ayarlar. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Çizgi rengini alır veya ayarlar. |
| tracking | int | r/w | Tracking değerini alır veya ayarlar. |
| underline | bool | r/w | Altı çizili olup [underline] olduğunu gösteren bir değeri alır veya ayarlar. |
| vertical_scale | double | r/w | Dikey ölçek. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [apply(style)](#apply_style_1) | Belirtilen stili uygular. |
| [is_equal(style)](#is_equal_style_2) | Belirtilen stilin eşit olup olmadığını belirler. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Belirtilen stili uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Stil. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Belirtilen stilin eşit olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Stil. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer belirtilen stil eşitse; aksi takdirde <c>false</c>. |


