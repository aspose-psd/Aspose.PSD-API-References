---
title: "Класс LnkeResource"
type: docs
weight: 590
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/
---

**Summary:** Defines the LnkeResource class that contains information about external linked files or assets in the PSD format image.<br/>            The link resource may contain several [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instances which can be accessed by indexer.<br/>            This is a part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files programmatically

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnkeResource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LnkeResource()](#LnkeResource__1) | Инициализирует новый экземпляр класса [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/). |
| [LnkeResource(data_sources)](#LnkeResource_data_sources_2) | Инициализирует новый экземпляр класса [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| data_source_count | int | r | Получает количество источников данных ссылок, доступных через индексатор. |
| is_empty | bool | r | Получает значение, указывающее, пустой ли этот экземпляр ресурса ссылки. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину глобального ресурса ссылки PSD в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет данные блока ресурсов. |


### Constructor: LnkeResource() {#LnkeResource__1}


```
 LnkeResource() 
```

Инициализирует новый экземпляр класса [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/).

### Constructor: LnkeResource(data_sources) {#LnkeResource_data_sources_2}


```
 LnkeResource(data_sources) 
```

Инициализирует новый экземпляр класса [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data_sources | [LinkDataSource[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) | Источники данных. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет данные блока ресурсов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

