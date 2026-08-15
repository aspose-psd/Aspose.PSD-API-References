---
title: "Класс MixrResource"
type: docs
weight: 680
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Инициализирует новый экземпляр класса [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            Спецификация формата PSD содержит следующее описание:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB или CMYK цвет плюс константа для настроек микшера. 4 * 2 байта цвета с 2 байтами константы. |
| [MixrResource(data)](#MixrResource_data_2) | Инициализирует новый экземпляр класса [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            Спецификация формата PSD содержит следующее описание:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB или CMYK цвет плюс константа для настроек микшера. 4 * 2 байта цвета с 2 байтами константы. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| monochrome | bool | r/w | Получает или задает значение, указывающее, является ли данный [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) монохромным. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| version | short | r/w | Получает или задает версию. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Получает необработанные данные информации канала |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Сохраняет ресурс в указанный контейнер потока. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Задает информацию канала. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Инициализирует новый экземпляр класса [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            Спецификация формата PSD содержит следующее описание:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB или CMYK цвет плюс константа для настроек микшера. 4 * 2 байта цвета с 2 байтами константы.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Инициализирует новый экземпляр класса [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            Спецификация формата PSD содержит следующее описание:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB или CMYK цвет плюс константа для настроек микшера. 4 * 2 байта цвета с 2 байтами константы.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Получает необработанные данные информации канала

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | Необработанный массив байтов информации канала. |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Задает информацию канала.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| channel_index | int | Индекс канала. |
| значение | байт | Значение. |

