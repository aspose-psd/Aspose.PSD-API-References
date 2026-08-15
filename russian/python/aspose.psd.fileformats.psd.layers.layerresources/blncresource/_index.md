---
title: "Класс BlncResource"
type: docs
weight: 80
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Инициализирует новый экземпляр класса [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| highlights_cyan_red_balance | short | r/w | Получает или задает значение Highlights Cyan Red Balance. |
| highlights_magenta_green_balance | short | r/w | Получает или задает значение Highlights Magenta Green Balance. |
| highlights_yellow_blue_balance | short | r/w | Получает или задает значение Highlights Yellow Blue Balance. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| midtones_cyan_red_balance | short | r/w | Получает или задает значение Midtones Cyan Red Balance. |
| midtones_magenta_green_balance | short | r/w | Получает или задает Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | Получает или задает Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | Получает или задает значение, указывающее, сохраняет ли этот [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) яркость. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| shadows_cyan_red_balance | short | r/w | Получает или задает Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | Получает или задает Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | Получает или задает Shadows Yellow Blue Balance. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Инициализирует новый экземпляр класса [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/).

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

