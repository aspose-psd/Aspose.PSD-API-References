---
title: "StringFormat Klasse"
type: docs
weight: 4260
url: /nl/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initialiseert een nieuw [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| [StringFormat(format)](#StringFormat_format_2) | Initialiseert een nieuw [StringFormat](/psd/python-net/aspose.psd/stringformat/) object van het opgegeven bestaande [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| [StringFormat(options)](#StringFormat_options_3) | Initialiseert een nieuw [StringFormat](/psd/python-net/aspose.psd/stringformat/) object met de opgegeven [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeratie en taal. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Haalt op of stelt tekstuitlijningsinformatie op het verticale vlak in. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Haalt op of stelt de aangepaste teken‑ident in. |
| digit_substitution_language | int | r/w | Haalt op of stelt de taal in die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Haalt op of stelt de methode in die wordt gebruikt voor cijfervervanging. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| first_tab_offset | float | r | Haalt het aantal spaties op tussen het begin van een regel tekst en de eerste tabstop. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Haalt op of stelt een [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeratie in die opmaakinformatie bevat. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Haalt een generiek standaard [StringFormat](/psd/python-net/aspose.psd/stringformat/) object op. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Haalt een generiek typografisch [StringFormat](/psd/python-net/aspose.psd/stringformat/) object op. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Haalt op of stelt het [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) object in voor dit [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Haalt op of stelt de lijnuitlijning op het horizontale vlak in. |
| tab_stops | float | r | Haalt een array van afstanden tussen tabstops op in de eenheden die zijn opgegeven door de eigenschap [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Haalt op of stelt de [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) enumeratie in voor dit [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Maakt een diepe kloon van dit [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Stelt tabstops in voor dit [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initialiseert een nieuw [StringFormat](/psd/python-net/aspose.psd/stringformat/) object.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initialiseert een nieuw [StringFormat](/psd/python-net/aspose.psd/stringformat/) object van het opgegeven bestaande [StringFormat](/psd/python-net/aspose.psd/stringformat/) object.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Het [StringFormat](/psd/python-net/aspose.psd/stringformat/) object waarvan het nieuwe [StringFormat](/psd/python-net/aspose.psd/stringformat/) object moet worden geïnitialiseerd. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initialiseert een nieuw [StringFormat](/psd/python-net/aspose.psd/stringformat/) object met de opgegeven [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeratie en taal.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | De [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeratie voor het nieuwe [StringFormat](/psd/python-net/aspose.psd/stringformat/) object. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Maakt een diepe kloon van dit [StringFormat](/psd/python-net/aspose.psd/stringformat/) object.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | De diepe kloon van de huidige [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Stelt tabstops in voor dit [StringFormat](/psd/python-net/aspose.psd/stringformat/) object.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| first_tab_offset | float | Het aantal spaties tussen het begin van een regel tekst en de eerste tabstop. |
| tab_stops | float | Een array van afstanden tussen tabstops in de eenheden die zijn opgegeven door de eigenschap [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

