---
title: "Класс PattResourceData"
type: docs
weight: 780
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | Инициализирует новый экземпляр класса PattResourceData |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| height | short | r | Получает высоту. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Возвращает режим изображения. |
| длина | int | r | Возвращает длину шаблона. |
| name | string | r/w | Возвращает или задает имя. |
| pattern_data | int | r | Возвращает данные шаблона. |
| pattern_id | string | r/w | Получает или задает идентификатор шаблона. |
| version | int | r | Получает версию. |
| width | short | r | Получает ширину. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Сохраняет данные шаблона. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Устанавливает шаблон. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

Инициализирует новый экземпляр класса PattResourceData

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Сохраняет данные шаблона.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Устанавливает шаблон.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | int | Пиксели. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Границы. |

