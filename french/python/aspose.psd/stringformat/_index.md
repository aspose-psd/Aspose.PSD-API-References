---
title: "Classe StringFormat"
type: docs
weight: 4260
url: /fr/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Initialise un nouvel objet [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Initialise un nouvel objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) à partir de l'objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) existant spécifié. |
| [StringFormat(options)](#StringFormat_options_3) | Initialise un nouvel objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) avec l'énumération [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) spécifiée et la langue. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Obtient ou définit les informations d'alignement du texte sur le plan vertical. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtient ou définit l'identifiant de caractère personnalisé. |
| digit_substitution_language | int | r/w | Obtient ou définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Obtient ou définit la méthode à utiliser pour la substitution des chiffres. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| first_tab_offset | float | r | Obtient le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Obtient ou définit une énumération [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) qui contient des informations de formatage. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Obtient un objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) générique par défaut. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Obtient un objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) typographique générique. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Obtient ou définit l'objet [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) pour cet objet [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Obtient ou définit l'alignement de ligne sur le plan horizontal. |
| tab_stops | float | r | Obtient un tableau de distances entre les arrêts de tabulation dans les unités spécifiées par la propriété [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Obtient ou définit l'énumération [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) pour cet objet [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crée une copie profonde de cet objet [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Définit les arrêts de tabulation pour cet objet [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Initialise un nouvel objet [StringFormat](/psd/python-net/aspose.psd/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Initialise un nouvel objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) à partir de l'objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) existant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | L'objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) à partir duquel initialiser le nouvel objet [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Initialise un nouvel objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) avec l'énumération [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) spécifiée et la langue.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | L'énumération [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) pour le nouvel objet [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crée une copie profonde de cet objet [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Returns**

| Type | Description |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | La copie profonde de l'objet [StringFormat](/psd/python-net/aspose.psd/stringformat/) actuel. |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Définit les arrêts de tabulation pour cet objet [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| first_tab_offset | float | Le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |
| tab_stops | float | Un tableau de distances entre les arrêts de tabulation dans les unités spécifiées par la propriété [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

