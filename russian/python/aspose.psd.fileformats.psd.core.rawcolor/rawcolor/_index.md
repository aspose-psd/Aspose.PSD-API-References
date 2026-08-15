---
title: "Класс RawColor"
type: docs
weight: 20
url: /ru/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Инициализирует новый экземпляр класса [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/). |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Инициализирует новый экземпляр класса [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) из формата пиксельных данных, используя предопределённые режимы цвета. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Режим, которому следует цвет. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Получает компоненты цвета. Каждый компонент — отдельный канал, и если вы используете непопулярную<br/>            схему цветов, лучше работать с каждым каналом отдельно. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Получает цвет как int, если это возможно. |
| [get_as_long()](#get_as_long__2) | Получает цвет как long, если это возможно. |
| [get_bit_depth()](#get_bit_depth__3) | Получает глубину цвета Raw Color. <br/>            Например, для цвета ARGB с 8 битами на канал/компонент глубина составляет 32<br/>            Глубина полного цвета ARGB с 16 битами на канал/компонент составляет 64.<br/>            Глубина цвета суммируется из глубин отдельных каналов. <br/>            Это возможно, если разные каналы имеют разную глубину. |
| [get_color_mode_name()](#get_color_mode_name__4) | Получает название режима цвета. Название режима цвета формируется из названий каналов/компонентов. |
| [set_as_int(value)](#set_as_int_value_5) | Устанавливает данные во все каналы из аргумента типа int, если это возможно. |
| [set_as_long(value)](#set_as_long_value_6) | Устанавливает данные во все каналы из аргумента типа int, если это возможно. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Инициализирует новый экземпляр класса [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | Пользовательские компоненты цвета. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Инициализирует новый экземпляр класса [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) из формата пиксельных данных, используя предопределённые режимы цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Формат пиксельных данных. |
| color_mode | short | Режим, которому следует цвет. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Получает цвет как int, если это возможно.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Данные каналов хранятся в типе Int. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Получает цвет как long, если это возможно.

**Returns**

| Тип | Описание |
| :- | :- |
| long | Данные каналов хранятся в типе Int. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Получает глубину цвета Raw Color. <br/>            Например, для цвета ARGB с 8 битами на канал/компонент глубина составляет 32<br/>            Глубина полного цвета ARGB с 16 битами на канал/компонент составляет 64.<br/>            Глубина цвета суммируется из глубин отдельных каналов. <br/>            Это возможно, если разные каналы имеют разную глубину.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Сумма глубин всех каналов. |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Получает название режима цвета. Название режима цвета формируется из названий каналов/компонентов.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Строка с названием режима цвета. |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Устанавливает данные во все каналы из аргумента типа int, если это возможно.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | int | Значение типа int, содержащее данные компонента. |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Устанавливает данные во все каналы из аргумента типа int, если это возможно.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | long | Значение типа int, содержащее данные компонента. |

