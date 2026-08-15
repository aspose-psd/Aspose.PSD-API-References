---
title: "Класс Font"
type: docs
weight: 1340
url: /ru/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) с указанным размером. Набор символов устанавливается в [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), графическая единица — в [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), стиль шрифта — в [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) с указанным размером и стилем. Набор символов устанавливается в [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), графическая единица — в [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) с указанным размером, стилем и единицей измерения. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) с указанным размером, стилем, единицей измерения и набором символов. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) используя указанный размер и единицу измерения. Набор символов устанавливается в [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), стиль устанавливается в [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Инициализирует новый [Font](/psd/python-net/aspose.psd/font/), который использует указанный существующий [Font](/psd/python-net/aspose.psd/font/) и перечисление [FontStyle](/psd/python-net/aspose.psd/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bold | bool | r | Возвращает значение, указывающее, является ли этот [Font](/psd/python-net/aspose.psd/font/) полужирным. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Возвращает байтовое значение, определяющее набор символов, используемый этим [Font](/psd/python-net/aspose.psd/font/). |
| italic | bool | r | Возвращает значение, указывающее, является ли этот [Font](/psd/python-net/aspose.psd/font/) курсивным. |
| name | string | r | Возвращает название гарнитуры этого [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Возвращает размер em этого [Font](/psd/python-net/aspose.psd/font/) измеренный в единицах, указанных свойством [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | Возвращает значение, указывающее, задает ли этот [Font](/psd/python-net/aspose.psd/font/) горизонтальную линию через шрифт. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Возвращает информацию о стиле этого [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Возвращает значение, указывающее, подчёркнут ли этот [Font](/psd/python-net/aspose.psd/font/). |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Возвращает единицу измерения для этого [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Создаёт точную глубокую копию этого [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) с указанным размером. Набор символов устанавливается в [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), графическая единица — в [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), стиль шрифта — в [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Размер em в пунктах нового шрифта. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) с указанным размером и стилем. Набор символов устанавливается в [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), графическая единица — в [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Размер em в пунктах нового шрифта. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Стиль [FontStyle](/psd/python-net/aspose.psd/fontstyle/) нового шрифта. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) с указанным размером, стилем и единицей измерения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Стиль [FontStyle](/psd/python-net/aspose.psd/fontstyle/) нового шрифта. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Единица измерения [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) нового шрифта. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) с указанным размером, стилем, единицей измерения и набором символов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Стиль [FontStyle](/psd/python-net/aspose.psd/fontstyle/) нового шрифта. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Единица измерения [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) нового шрифта. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Набор символов, используемый для этого шрифта. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Инициализирует новый [Font](/psd/python-net/aspose.psd/font/) используя указанный размер и единицу измерения. Набор символов устанавливается в [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), стиль устанавливается в [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Строковое представление имени [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Размер em нового шрифта в единицах, указанных параметром <paramref name="unit" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Единица измерения [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) нового шрифта. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Инициализирует новый [Font](/psd/python-net/aspose.psd/font/), который использует указанный существующий [Font](/psd/python-net/aspose.psd/font/) и перечисление [FontStyle](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Существующий [Font](/psd/python-net/aspose.psd/font/) из которого создаётся новый [Font](/psd/python-net/aspose.psd/font/). |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) применяемый к новому [Font](/psd/python-net/aspose.psd/font/). Несколько значений перечисления [FontStyle](/psd/python-net/aspose.psd/fontstyle/) могут быть объединены оператором OR. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Создаёт точную глубокую копию этого [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) который создаёт этот метод. |


