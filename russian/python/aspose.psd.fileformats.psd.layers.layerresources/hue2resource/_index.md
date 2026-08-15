---
title: "Класс Hue2Resource"
type: docs
weight: 350
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Summary:** Class Hue2Resource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Hue2Resource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Hue2Resource()](#Hue2Resource__1) | Инициализирует новый экземпляр класса [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) class. |
| [Hue2Resource(data)](#Hue2Resource_data_2) | Инициализирует новый экземпляр класса [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| colorize | bool | r/w | Возвращает или задает значение, указывающее, является ли этот [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) colorize. |
| hue | short | r/w | Возвращает или задает основной оттенок. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| lightness | short | r/w | Возвращает или задает основную яркость. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| ranges | [ColorRangeHsl[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) | r | Возвращает диапазоны слоя коррекции оттенка/насыщенности.<br/>            Ranges in PS can change names if range is changed, so we should work by index |
| насыщенность | short | r/w | Возвращает или задает основную насыщенность. |
| signature | int | r | Получает подпись. |
| version | short | r | Возвращает версию. Default is 2 |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: Hue2Resource() {#Hue2Resource__1}


```
 Hue2Resource() 
```

Инициализирует новый экземпляр класса [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) class.

### Constructor: Hue2Resource(data) {#Hue2Resource_data_2}


```
 Hue2Resource(data) 
```

Инициализирует новый экземпляр класса [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) class.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет ресурс в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

