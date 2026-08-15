---
title: "StringFormat Sınıfı"
type: docs
weight: 4260
url: /tr/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Yeni bir [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi başlatır. |
| [StringFormat(format)](#StringFormat_format_2) | Belirtilen mevcut [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesinden yeni bir [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi başlatır. |
| [StringFormat(options)](#StringFormat_options_3) | Belirtilen [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enum ve dil ile yeni bir [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Dikey düzlemde metin hizalama bilgisini alır veya ayarlar. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Özel karakter kimliğini alır veya ayarlar. |
| digit_substitution_language | int | r/w | Yerel rakamlar batı rakamlarıyla değiştirildiğinde kullanılan dili alır veya ayarlar. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Rakam ikamesi için kullanılacak yöntemi alır veya ayarlar. |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| first_tab_offset | float | r | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını alır. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Biçimlendirme bilgilerini içeren bir [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumerasyonunu alır veya ayarlar. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Genel bir varsayılan [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesini alır. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Genel bir tipografik [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesini alır. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Bu [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi için [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) nesnesini alır veya ayarlar. |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Yatay düzlemde satır hizalamasını alır veya ayarlar. |
| tab_stops | float | r | [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) özelliği tarafından belirtilen birimlerde sekme durakları arasındaki mesafelerin bir dizisini alır. |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Bu [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi için [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) enumerasyonunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Bu [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesinin derin bir klonunu oluşturur. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Bu [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi için sekme duraklarını ayarlar. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Yeni bir [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi başlatır.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Belirtilen mevcut [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesinden yeni bir [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Yeni [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesini başlatmak için kullanılacak [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Belirtilen [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enum ve dil ile yeni bir [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | Yeni [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi için [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumerasyonu. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Bu [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesinin derin bir klonunu oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | Mevcut [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesinin derin klonu. |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Bu [StringFormat](/psd/python-net/aspose.psd/stringformat/) nesnesi için sekme duraklarını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| first_tab_offset | float | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısı. |
| tab_stops | float | [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) özelliği tarafından belirtilen birimlerde sekme durakları arasındaki mesafelerin bir dizisi. |

