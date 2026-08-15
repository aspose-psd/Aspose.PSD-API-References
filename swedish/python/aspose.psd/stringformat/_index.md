---
title: "StringFormat Class"
type: docs
weight: 4260
url: /sv/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initierar ett nytt [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objekt. |
| [StringFormat(format)](#StringFormat_format_2) | Initierar ett nytt [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objekt från det angivna befintliga [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objektet. |
| [StringFormat(options)](#StringFormat_options_3) | Initierar ett nytt [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objekt med den angivna [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/)‑enumerationen och språket. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Hämtar eller anger information om textjustering på den vertikala planet. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Hämtar eller anger den anpassade tecken‑identiteten. |
| digit_substitution_language | int | r/w | Hämtar eller anger språket som används när lokala siffror ersätts med västerländska siffror. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Hämtar eller anger metoden som ska användas för sifferersättning. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| first_tab_offset | float | r | Hämtar antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Hämtar eller anger en [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeration som innehåller formateringsinformation. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Hämtar ett generiskt standard [StringFormat](/psd/python-net/aspose.psd/stringformat/) objekt. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Hämtar ett generiskt typografiskt [StringFormat](/psd/python-net/aspose.psd/stringformat/) objekt. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Hämtar eller anger [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/)‑objektet för detta [StringFormat](/psd/python-net/aspose.psd/stringformat/) objekt. |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Hämtar eller anger radjusteringen på den horisontella planet. |
| tab_stops | float | r | Hämtar en array av avstånd mellan tabbstopp i de enheter som anges av egenskapen [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Hämtar eller anger [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) enumeration för detta [StringFormat](/psd/python-net/aspose.psd/stringformat/) objekt. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Skapar en djup klon av detta [StringFormat](/psd/python-net/aspose.psd/stringformat/) objekt. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Anger tabbstopp för detta [StringFormat](/psd/python-net/aspose.psd/stringformat/) objekt. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initierar ett nytt [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objekt.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initierar ett nytt [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objekt från det angivna befintliga [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objektet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objektet som ska användas för att initiera det nya [StringFormat](/psd/python-net/aspose.psd/stringformat/) objektet. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initierar ett nytt [StringFormat](/psd/python-net/aspose.psd/stringformat/)‑objekt med den angivna [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/)‑enumerationen och språket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) enumeration för det nya [StringFormat](/psd/python-net/aspose.psd/stringformat/) objektet. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Skapar en djup klon av detta [StringFormat](/psd/python-net/aspose.psd/stringformat/) objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | Den djupa klonen av den aktuella [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Anger tabbstopp för detta [StringFormat](/psd/python-net/aspose.psd/stringformat/) objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| first_tab_offset | float | Antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| tab_stops | float | En array av avstånd mellan tabbstopp i de enheter som anges av egenskapen [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

