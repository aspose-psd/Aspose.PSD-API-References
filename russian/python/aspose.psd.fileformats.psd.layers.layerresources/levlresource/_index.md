---
title: "Класс LevlResource"
type: docs
weight: 490
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Инициализирует новый экземпляр класса [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/). |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Инициализирует новый экземпляр класса [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Поддерживается в режимах GrayScale, Duotone, RGB, CMYK, Lab color<br/>            2 байта — Version (=2)<br/>            29 * 10 байт — Sets of level records with 5 short integers<br/>            4 байта — Lvls header (Starts at 292 index)<br/>            2 байта — Version (=3)<br/>            2 байта — Count of total level record<br/>            10 * (Total Count - 29)<br/>            Zero ending of Lvls resource should be fold for four too |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| version | short | r | Возвращает версию. Default is 2 |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Получает канал. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Инициализирует новый экземпляр класса [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Инициализирует новый экземпляр класса [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Поддерживается в режимах GrayScale, Duotone, RGB, CMYK, Lab color<br/>            2 байта — Version (=2)<br/>            29 * 10 байт — Sets of level records with 5 short integers<br/>            4 байта — Lvls header (Starts at 292 index)<br/>            2 байта — Version (=3)<br/>            2 байта — Count of total level record<br/>            10 * (Total Count - 29)<br/>            Zero ending of Lvls resource should be fold for four too

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | байт | Байты. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Получает канал.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Данные уровня канала |


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

