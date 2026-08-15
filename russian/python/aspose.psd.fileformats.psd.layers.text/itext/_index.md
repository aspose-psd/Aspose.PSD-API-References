---
title: "Класс IText"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Получает элементы. |
| text | string | r | Получает текст. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Получает или задает ориентацию текста. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Добавляет часть текста в конец |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Вставляет [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) в указанную позицию |
| [produce_portion()](#produce_portion__3) | Создаёт новую часть с параметрами по умолчанию |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Создаёт новые части с заданными или параметрами по умолчанию. |
| [remove_portion(index)](#remove_portion_index_5) | Удаляет часть по указанному индексу |
| update_layer_data() | Обновляет данные слоя. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Добавляет часть текста в конец

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Часть. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Вставляет [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) в указанную позицию

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Часть. |
| index | int | Индекс. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Создаёт новую часть с параметрами по умолчанию

**Returns**

| Тип | Описание |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Ссылка на только что созданный [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Создаёт новые части с заданными или параметрами по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| portions_of_text | string | Части текста для создания нового [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/). |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Стиль, который, если не null, будет применён к новому [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), иначе будет использоваться значение по умолчанию. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Параграф, который, если не null, будет применён в новом [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), иначе будет использоваться значение по умолчанию. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Возвращает новые части [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) на основе входных параметров. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Удаляет часть по указанному индексу

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс. |

