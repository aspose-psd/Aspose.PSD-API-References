---
title: "StringFormat Klasse"
type: docs
weight: 4260
url: /de/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initialisiert ein neues [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt. |
| [StringFormat(format)](#StringFormat_format_2) | Initialisiert ein neues [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt aus dem angegebenen vorhandenen [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt. |
| [StringFormat(options)](#StringFormat_options_3) | Initialisiert ein neues [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt mit der angegebenen [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) Aufzählung und Sprache. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Liest oder setzt Textausrichtungsinformationen in der vertikalen Ebene. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Liest oder setzt die benutzerdefinierte Zeichenkennung. |
| digit_substitution_language | int | r/w | Liest oder setzt die Sprache, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Liest oder setzt die Methode, die für die Ziffernersetzung verwendet wird. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| first_tab_offset | float | r | Liest die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Liest oder setzt eine [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) Aufzählung, die Formatierungsinformationen enthält. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Liest ein generisches Standard-[StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Liest ein generisches typografisches [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Liest oder setzt das [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) Objekt für dieses [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt. |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Liest oder setzt die Zeilenausrichtung in der horizontalen Ebene. |
| tab_stops | float | r | Liest ein Array von Abständen zwischen Tabstopps in den durch die [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) Eigenschaft angegebenen Einheiten. |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Liest oder setzt die [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) Aufzählung für dieses [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Erstellt einen tiefen Klon dieses [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekts. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Setzt Tabstopps für dieses [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initialisiert ein neues [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initialisiert ein neues [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt aus dem angegebenen vorhandenen [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Das [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt, aus dem das neue [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt initialisiert wird. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initialisiert ein neues [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt mit der angegebenen [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) Aufzählung und Sprache.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | Die [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) Aufzählung für das neue [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Erstellt einen tiefen Klon dieses [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekts.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | Der tiefe Klon des aktuellen [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Setzt Tabstopps für dieses [StringFormat](/psd/python-net/aspose.psd/stringformat/) Objekt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| first_tab_offset | float | Die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp. |
| tab_stops | float | Ein Array von Abständen zwischen Tabstopps in den durch die [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) Eigenschaft angegebenen Einheiten. |

