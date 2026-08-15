---
title: "Класс ColorComponent"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | Инициализирует новый экземпляр класса [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Пожалуйста, проверьте |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bit_depth | байт | r | Получает глубину цвета компонента/канала. |
| описание | string | r | Получает описание компонента цвета. |
| full_name | string | r | Получает полное название компонента цвета, включающее имя и описание, разделённые пробелом |
| name | string | r | Получает имя компонента цвета. |
| permitted_full_names [static] | string | r | Получает разрешённые полные имена. |
| значение | ulong | r/w | Получает или задаёт значение. <br/> Обратите внимание, если вы попытаетесь установить значение, превышающее <br/> возможное, хранимое при текущей глубине цвета, будет выброшено исключение |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

Инициализирует новый экземпляр класса [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Пожалуйста, проверьте

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| bit_depth | байт | Битовая глубина. |
| full_name | string | Полное имя. |

