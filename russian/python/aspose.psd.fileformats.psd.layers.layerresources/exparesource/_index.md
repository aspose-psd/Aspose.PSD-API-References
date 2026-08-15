---
title: "Класс ExpaResource"
type: docs
weight: 280
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | Инициализирует новый экземпляр класса [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | Инициализирует новый экземпляр класса [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | Инициализирует новый экземпляр класса [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| экспозиция | float | r/w | Получает или задает экспозицию. |
| коррекция_гаммы | float | r/w | Получает или задает гамму. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| offset | float | r/w | Получает или задает смещение. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| version | short | r | Получает версию. По умолчанию 1. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

Инициализирует новый экземпляр класса [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

Инициализирует новый экземпляр класса [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | байт | Байты. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

Инициализирует новый экземпляр класса [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| экспозиция | float | Экспозиция. |
| offset | float | Смещение. |
| гамма | float | Гамма. |

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

