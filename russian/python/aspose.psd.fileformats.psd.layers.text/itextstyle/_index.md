---
title: "ITextStyle Класс"
type: docs
weight: 40
url: /ru/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | Получает или задает автоматическое кернинг. |
| auto_leading | bool | r/w | Получает или задает значение, указывающее, включено ли [automatic leading]. |
| baseline_shift | double | r/w | Смещение базовой линии. |
| contextual_alternates | bool | r/w | Контекстные альтернативы, используемые для соединения букв вместе. |
| discretionary_ligatures | bool | r/w | Дополнительные лигатуры, используемые для соединения букв, особенно в курсивных шрифтах. |
| faux_bold | bool | r/w | Получает или задает, включён ли faux bold. |
| faux_italic | bool | r/w | Получает или задает, включён ли faux bold. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает цвет заливки. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | Базовая линия шрифта. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | Заглавные буквы шрифта. |
| font_index | int | r | Получает индекс шрифта. |
| font_name | string | r/w | Получает или задает имя шрифта. |
| font_size | double | r/w | Получает или задает размер шрифта. |
| fractions | bool | r/w | Символы дробей могут быть заменены специальным глифом. |
| hindi_numbers | bool | r/w | Получает или задает значение, указывающее, включены ли [hindi numbers]. |
| horizontal_scale | double | r/w | Горизонтальный масштаб. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | Получает или задает стандартное вертикальное выравнивание по римскому стилю.<br/>            Это, основанное на значении ресурса BaselineDirection, применяется только когда ориентация текста — [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/). |
| kerning | int | r/w | Получает или задает кернинг. |
| language_index | int | r | Получает индекс языка. |
| leading | double | r/w | Получает или задает межстрочный интервал. |
| no_break | bool | r/w | Получает или задает значение без разрыва. |
| standard_ligatures | bool | r/w | Стандартные контекстные лигатуры, используемые для соединения букв. |
| strikethrough | bool | r/w | Получает или задает значение, указывающее, применено ли [strikethrough]. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает цвет штриха. |
| tracking | int | r/w | Получает или задает трекинг. |
| underline | bool | r/w | Получает или задает значение, указывающее, применено ли [underline]. |
| vertical_scale | double | r/w | Вертикальный масштаб. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [apply(style)](#apply_style_1) | Применяет указанный стиль. |
| [is_equal(style)](#is_equal_style_2) | Определяет, равен ли указанный стиль. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

Применяет указанный стиль.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Стиль. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

Определяет, равен ли указанный стиль.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Стиль. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если указанный стиль равен; иначе <c>false</c>. |


