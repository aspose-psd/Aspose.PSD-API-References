---
title: "Kelas ITextStyle"
type: docs
weight: 40
url: /id/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Mendapatkan atau mengatur auto kerning. |
| auto_leading | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [automatic leading]. |
| baseline_shift | double | r/w | Perpindahan baseline. |
| contextual_alternates | bool | r/w | Alternatif kontekstual yang digunakan untuk menghubungkan huruf bersama-sama. |
| discretionary_ligatures | bool | r/w | Ligatur diskresi yang digunakan untuk menghubungkan huruf, terutama dalam font skrip. |
| faux_bold | bool | r/w | Mendapatkan atau mengatur apakah faux bold diaktifkan. |
| faux_italic | bool | r/w | Mendapatkan atau mengatur apakah faux bold diaktifkan. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna isian. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | Baseline font. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Kapital font. |
| font_index | int | r | Mendapatkan indeks font. |
| font_name | string | r/w | Mendapatkan atau mengatur nama font. |
| font_size | double | r/w | Mendapatkan atau mengatur ukuran font. |
| fractions | bool | r/w | Simbol pecahan dapat diganti dengan glif khusus. |
| hindi_numbers | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [hindi numbers]. |
| horizontal_scale | double | r/w | Skala horizontal. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Mendapatkan atau mengatur perataan Romawi vertikal standar.<br/>            Ini berdasarkan nilai sumber daya BaselineDirection hanya berlaku ketika orientasi teks adalah [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | Mendapatkan atau mengatur kerning. |
| language_index | int | r | Mendapatkan indeks bahasa. |
| leading | double | r/w | Mendapatkan atau mengatur leading. |
| no_break | bool | r/w | Mendapatkan atau mengatur nilai no break. |
| standard_ligatures | bool | r/w | Ligatur kontekstual standar yang digunakan untuk menghubungkan huruf bersama. |
| strikethrough | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna goresan. |
| tracking | int | r/w | Mendapatkan atau mengatur tracking. |
| underline | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [underline]. |
| vertical_scale | double | r/w | Skala vertikal. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [apply(style)](#apply_style_1) | Menerapkan gaya yang ditentukan. |
| [is_equal(style)](#is_equal_style_2) | Menentukan apakah gaya yang ditentukan sama. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Menerapkan gaya yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Gaya. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Menentukan apakah gaya yang ditentukan sama.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Gaya. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika gaya yang ditentukan sama; jika tidak, <c>false</c>. |


