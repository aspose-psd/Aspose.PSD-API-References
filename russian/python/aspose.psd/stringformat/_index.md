---
title: "Класс StringFormat"
type: docs
weight: 4260
url: /ru/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | Инициализирует новый объект [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [StringFormat(format)](#StringFormat_format_2) | Инициализирует новый объект [StringFormat](/psd/python-net/aspose.psd/stringformat/) из указанного существующего объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [StringFormat(options)](#StringFormat_options_3) | Инициализирует новый объект [StringFormat](/psd/python-net/aspose.psd/stringformat/) с указанным перечислением [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) и языком. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Получает или задает информацию о выравнивании текста по вертикали. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Получает или задает пользовательский идентификатор символа. |
| digit_substitution_language | int | r/w | Получает или задает язык, используемый при замене локальных цифр на западные цифры. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | Получает или задает метод, используемый для замены цифр. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| first_tab_offset | float | r | Получает количество пробелов между началом строки текста и первой табуляцией. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | Получает или задает перечисление [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/), которое содержит информацию о форматировании. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Получает универсальный объект [StringFormat](/psd/python-net/aspose.psd/stringformat/) по умолчанию. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | Получает универсальный типографский объект [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | Получает или задает объект [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) для этого объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | Получает или задает выравнивание строк по горизонтали. |
| tab_stops | float | r | Получает массив расстояний между табуляциями в единицах, указанных свойством [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | Получает или задает перечисление [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) для этого объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Создает глубокую копию этого объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | Устанавливает табуляцию для этого объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

Инициализирует новый объект [StringFormat](/psd/python-net/aspose.psd/stringformat/).

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

Инициализирует новый объект [StringFormat](/psd/python-net/aspose.psd/stringformat/) из указанного существующего объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) объект, из которого инициализируется новый объект [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

Инициализирует новый объект [StringFormat](/psd/python-net/aspose.psd/stringformat/) с указанным перечислением [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) и языком.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | Перечисление [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) для нового объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Создает глубокую копию этого объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Returns**

| Тип | Описание |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | Глубокая копия текущего объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/). |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

Устанавливает табуляцию для этого объекта [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| first_tab_offset | float | Количество пробелов между началом строки текста и первой табуляцией. |
| tab_stops | float | Массив расстояний между табуляциями в единицах, указанных свойством [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/). |

