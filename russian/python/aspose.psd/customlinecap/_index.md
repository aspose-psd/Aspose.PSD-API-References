---
title: "Класс CustomLineCap"
type: docs
weight: 1010
url: /ru/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Инициализирует новый экземпляр класса [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) с указанным контуром и заливкой. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Инициализирует новый экземпляр класса [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) из указанного существующего перечисления [LineCap](/psd/python-net/aspose.psd/linecap/) с указанным контуром и заливкой. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Инициализирует новый экземпляр класса [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) из указанного существующего перечисления [LineCap](/psd/python-net/aspose.psd/linecap/) с указанным контуром, заливкой и отступом. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Получает или задает перечисление [LineCap](/psd/python-net/aspose.psd/linecap/), на котором основан этот [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/). |
| base_inset | float | r/w | Получает или задает расстояние между наконечником и линией. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Получает или задает объект, определяющий заливку для пользовательского наконечника. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Получает или задает перечисление [LineJoin](/psd/python-net/aspose.psd/linejoin/), определяющее, как соединяются линии, составляющие объект [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/). |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Получает или задает объект, определяющий контур пользовательского наконечника. |
| width_scale | float | r/w | Получает или задает величину, на которую масштабировать объект класса [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) относительно ширины объекта. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Получает наконечники, используемые для начала и окончания линий, составляющих этот пользовательский наконечник. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Задает наконечники, используемые для начала и окончания линий, составляющих этот пользовательский наконечник. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Инициализирует новый экземпляр класса [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) с указанным контуром и заливкой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Объект [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), определяющий заливку пользовательского наконечника. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Объект [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), определяющий контур пользовательского наконечника. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Инициализирует новый экземпляр класса [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) из указанного существующего перечисления [LineCap](/psd/python-net/aspose.psd/linecap/) с указанным контуром и заливкой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Объект [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), определяющий заливку пользовательского наконечника. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Объект [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), определяющий контур пользовательского наконечника. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Наконечник линии, из которого создаётся пользовательский наконечник. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Инициализирует новый экземпляр класса [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) из указанного существующего перечисления [LineCap](/psd/python-net/aspose.psd/linecap/) с указанным контуром, заливкой и отступом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Объект [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), определяющий заливку пользовательского наконечника. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Объект [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), определяющий контур пользовательского наконечника. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Наконечник линии, из которого создаётся пользовательский наконечник. |
| base_inset | float | Расстояние между наконечником и линией. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Получает наконечники, используемые для начала и окончания линий, составляющих этот пользовательский наконечник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Перечисление [LineCap](/psd/python-net/aspose.psd/linecap/), используемое в начале линии внутри этого наконечника. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Перечисление [LineCap](/psd/python-net/aspose.psd/linecap/), используемое в конце линии внутри этого наконечника. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Задает наконечники, используемые для начала и окончания линий, составляющих этот пользовательский наконечник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Перечисление [LineCap](/psd/python-net/aspose.psd/linecap/), используемое в начале линии внутри этого наконечника. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Перечисление [LineCap](/psd/python-net/aspose.psd/linecap/), используемое в конце линии внутри этого наконечника. |

