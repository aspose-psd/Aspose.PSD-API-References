---
title: "Класс CustResource"
type: docs
weight: 230
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CustResource()](#CustResource__1) | Создаёт новый экземпляр класса [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
| [CustResource(data)](#CustResource_data_2) | Создаёт новый экземпляр класса [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| key | int | r | Получает ключ ресурса слоя. |
| layer_created_date_time | datetime | r/w | Получает или задаёт дату создания слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

Создаёт новый экземпляр класса [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

Создаёт новый экземпляр класса [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

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

