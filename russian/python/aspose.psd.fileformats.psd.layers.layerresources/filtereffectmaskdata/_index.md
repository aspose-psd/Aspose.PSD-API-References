---
title: "Класс FilterEffectMaskData"
type: docs
weight: 310
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Инициализирует новый экземпляр класса [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Получает каналы. |
| guid | string | r | Получает GUID. |
| длина | int | r | Получает длину данных маски фильтра в байтах. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Получает прямоугольник листовой маски. |
| max_channels | int | r | Получает максимальное количество каналов. |
| pixels_depth | int | r | Получает глубину пикселей. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Получает прямоугольник каналов. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Получает листовую маску. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Получает пользовательскую маску. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Инициализирует новый экземпляр класса [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | string | guid ресурса. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник каналов. |
| pixels_depth | int | Глубина пикселей. |
| max_channels | int | Значение максимального количества каналов. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Каналы. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Пользовательская маска. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник маски листа. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Маска листа. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Сохраняет ресурс в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |

