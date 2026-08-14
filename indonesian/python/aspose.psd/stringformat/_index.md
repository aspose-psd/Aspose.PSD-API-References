---
title: "Kelas StringFormat"
type: docs
weight: 4260
url: /id/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Menginisialisasi objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) baru. |
| [StringFormat(format)](#StringFormat_format_2) | Menginisialisasi objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) baru dari objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) yang ada yang ditentukan. |
| [StringFormat(options)](#StringFormat_options_3) | Menginisialisasi objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) baru dengan enumerasi [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) dan bahasa yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Mendapatkan atau mengatur informasi perataan teks pada bidang vertikal. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Mendapatkan atau mengatur ident karakter khusus. |
| digit_substitution_language | int | r/w | Mendapatkan atau mengatur bahasa yang digunakan ketika digit lokal digantikan dengan digit barat. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Mendapatkan atau mengatur metode yang akan digunakan untuk substitusi digit. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| first_tab_offset | float | r | Mendapatkan jumlah spasi antara awal baris teks dan tab stop pertama. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Mendapatkan atau mengatur enumerasi [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) yang berisi informasi pemformatan. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Mendapatkan objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) default generik. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Mendapatkan objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) tipografi generik. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Mendapatkan atau mengatur objek [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) untuk objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) ini. |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Mendapatkan atau mengatur perataan baris pada bidang horizontal. |
| tab_stops | float | r | Mendapatkan array jarak antara tab stop dalam satuan yang ditentukan oleh properti [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Mendapatkan atau mengatur enumerasi [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) untuk objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Membuat klon mendalam dari objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) ini. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Mengatur tab stop untuk objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) ini. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Menginisialisasi objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) baru.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Menginisialisasi objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) baru dari objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) yang ada yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) yang digunakan untuk menginisialisasi objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) baru. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Menginisialisasi objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) baru dengan enumerasi [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) dan bahasa yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | Enumerasi [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) untuk objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) baru. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Membuat klon mendalam dari objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | Klon mendalam dari [StringFormat](/psd/python-net/aspose.psd/stringformat/) saat ini. |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Mengatur tab stop untuk objek [StringFormat](/psd/python-net/aspose.psd/stringformat/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| first_tab_offset | float | Jumlah spasi antara awal baris teks dan tab stop pertama. |
| tab_stops | float | Array jarak antara tab stop dalam satuan yang ditentukan oleh properti [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

