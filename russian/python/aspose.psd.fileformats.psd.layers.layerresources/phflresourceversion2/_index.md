---
title: "Класс PhflResourceVersion2"
type: docs
weight: 800
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion2

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PhflResourceVersion2()](#PhflResourceVersion2__1) | Инициализирует новый экземпляр класса [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
| [PhflResourceVersion2(data)](#PhflResourceVersion2_data_2) | Инициализирует новый экземпляр класса [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| color_space | short | r | Получает цветовое пространство. |
| component_a | short | r/w | Получает или задает компонент A цвета |
| component_b | short | r/w | Получает или задает компонент B |
| component_l | short | r/w | Получает или задает компонент L цвета |
| density | int | r/w | Получает или задает плотность. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| preserve_luminosity | bool | r/w | Получает или задает значение, указывающее, сохраняется ли яркость [preserve luminosity]. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| version | short | r | Получает версию. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Получает цвет. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Сохраняет ресурс в указанный контейнер потока. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Задает цвет RGB. |


### Constructor: PhflResourceVersion2() {#PhflResourceVersion2__1}


```
 PhflResourceVersion2() 
```

Инициализирует новый экземпляр класса [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

### Constructor: PhflResourceVersion2(data) {#PhflResourceVersion2_data_2}


```
 PhflResourceVersion2(data) 
```

Инициализирует новый экземпляр класса [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Получает цвет.

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | RGB‑цвет |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Сохраняет ресурс в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Задает цвет RGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Цвет. |

