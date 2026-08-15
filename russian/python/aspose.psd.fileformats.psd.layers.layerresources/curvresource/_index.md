---
title: "Класс CurvResource"
type: docs
weight: 190
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | Инициализирует новый экземпляр класса [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | Инициализирует новый экземпляр класса [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| is_data_stored_discretely | bool | r/w | Получает или задает значение, указывающее, хранится ли данные этого экземпляра дискретно. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Получает активный менеджер. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Получает данные канала. |
| [get_curve_manager()](#get_curve_manager__3) | Получает менеджер кривой. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

Инициализирует новый экземпляр класса [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | байт | Байты. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

Инициализирует новый экземпляр класса [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| max_channel_count | int | Максимальное количество каналов. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Получает активный менеджер.

**Returns**

| Тип | Описание |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Активный менеджер |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Получает данные канала.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | Данные канала |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Получает менеджер кривой.

**Returns**

| Тип | Описание |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) или [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Сохраняет ресурс в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

