---
title: "Clase StringFormat"
type: docs
weight: 4260
url: /es/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Inicializa un nuevo objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Inicializa un nuevo objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/) a partir del objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/) existente especificado. |
| [StringFormat(options)](#StringFormat_options_3) | Inicializa un nuevo objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/) con la enumeración [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) y el idioma especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Obtiene o establece la información de alineación de texto en el plano vertical. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtiene o establece el identificador de carácter personalizado. |
| digit_substitution_language | int | r/w | Obtiene o establece el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Obtiene o establece el método que se utilizará para la sustitución de dígitos. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| first_tab_offset | float | r | Obtiene el número de espacios entre el inicio de una línea de texto y la primera tabulación. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Obtiene o establece una enumeración [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) que contiene información de formato. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Obtiene un objeto genérico predeterminado [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Obtiene un objeto genérico tipográfico [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Obtiene o establece el objeto [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) para este objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Obtiene o establece la alineación de línea en el plano horizontal. |
| tab_stops | float | r | Obtiene una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Obtiene o establece la enumeración [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) para este objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una clonación profunda de este objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Establece tabulaciones para este objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Inicializa un nuevo objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Inicializa un nuevo objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/) a partir del objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/) existente especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | El objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/) del cual inicializar el nuevo objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Inicializa un nuevo objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/) con la enumeración [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) y el idioma especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | La enumeración [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) para el nuevo objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una clonación profunda de este objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | La clonación profunda del [StringFormat](/psd/python-net/aspose.psd/stringformat/) actual. |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Establece tabulaciones para este objeto [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| first_tab_offset | float | El número de espacios entre el inicio de una línea de texto y la primera tabulación. |
| tab_stops | float | Una matriz de distancias entre tabulaciones en las unidades especificadas por la propiedad [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

