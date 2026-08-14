---
title: "Classe StringFormat"
type: docs
weight: 4260
url: /it/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Inizializza un nuovo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Inizializza un nuovo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) a partire dall'oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) esistente specificato. |
| [StringFormat(options)](#StringFormat_options_3) | Inizializza un nuovo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) con l'enumerazione [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) e la lingua specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Ottiene o imposta le informazioni di allineamento del testo sul piano verticale. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Ottiene o imposta l'identificatore del carattere personalizzato. |
| digit_substitution_language | int | r/w | Ottiene o imposta la lingua utilizzata quando le cifre locali vengono sostituite con cifre occidentali. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Ottiene o imposta il metodo da utilizzare per la sostituzione delle cifre. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| first_tab_offset | float | r | Ottiene il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Ottiene o imposta una enumerazione [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) che contiene le informazioni di formattazione. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Ottiene un oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) generico predefinito. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Ottiene un oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) tipografico generico. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Ottiene o imposta l'oggetto [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) per questo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Ottiene o imposta l'allineamento della linea sul piano orizzontale. |
| tab_stops | float | r | Ottiene un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Ottiene o imposta l'enumerazione [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) per questo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una copia profonda di questo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Imposta le tabulazioni per questo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Inizializza un nuovo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Inizializza un nuovo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) a partire dall'oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) esistente specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | L'oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) da cui inizializzare il nuovo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Inizializza un nuovo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/) con l'enumerazione [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) e la lingua specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | L'enumerazione [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) per il nuovo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una copia profonda di questo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | La copia profonda dell'attuale [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Imposta le tabulazioni per questo oggetto [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| first_tab_offset | float | Il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |
| tab_stops | float | Un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

