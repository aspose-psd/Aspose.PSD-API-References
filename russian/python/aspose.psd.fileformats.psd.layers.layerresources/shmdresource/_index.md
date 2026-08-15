---
title: "Класс ShmdResource"
type: docs
weight: 890
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---

**Summary:** Class ShmdResource. Metadata settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ShmdResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ShmdResource()](#ShmdResource__1) | Создаёт новый экземпляр класса [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/). |
| [ShmdResource(data)](#ShmdResource_data_2) | Создаёт новый экземпляр класса [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| SUB_RESOURCE_HEADER_LENGTH [static] | int | r | Длина заголовка подресурса |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| key | int | r | Получает ключ ресурса слоя. |
| layer_created_date_time | datetime | r/w | Получает или задаёт время создания слоя. Если время создания слоя не указано, то возвращает new DateTime(0). |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| sub_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r | Получает подресурсы shmd‑ресурса. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет указанный контейнер потока. |


### Constructor: ShmdResource() {#ShmdResource__1}


```
 ShmdResource() 
```

Создаёт новый экземпляр класса [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/).

### Constructor: ShmdResource(data) {#ShmdResource_data_2}


```
 ShmdResource(data) 
```

Создаёт новый экземпляр класса [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |
| psd_version | int | Версия PSD. |

