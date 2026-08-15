---
title: "Класс IopaResource"
type: docs
weight: 440
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | Инициализирует новый экземпляр класса [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) |
| [IopaResource(data)](#IopaResource_data_2) | Инициализирует новый экземпляр класса [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| непрозрачность_заполнения | байт | r/w | Получает или задает непрозрачность заливки. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

Инициализирует новый экземпляр класса [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/)

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

Инициализирует новый экземпляр класса [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Необработанные байтовые данные. |

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

