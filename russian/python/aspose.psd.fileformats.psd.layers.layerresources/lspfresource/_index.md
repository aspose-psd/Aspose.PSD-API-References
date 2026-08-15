---
title: "LspfResource Класс"
type: docs
weight: 640
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | Инициализирует новый экземпляр класса [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
| [LspfResource(data)](#LspfResource_data_2) | Инициализирует новый экземпляр класса [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).<br/>            С пользовательским или неизвестным значением |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | Инициализирует новый экземпляр класса [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации инструмента типа 1819504742 |
| is_composite_protected | bool | r/w | Получает или задает значение, указывающее, защищён ли этот экземпляр от составной защиты. |
| is_position_protected | bool | r/w | Получает или задает значение, указывающее, защищён ли этот экземпляр от позиционной защиты. |
| is_transparency_protected | bool | r/w | Получает или задает значение, указывающее, защищён ли этот экземпляр от защиты прозрачности. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | Получает или задает тип блокировки. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

Инициализирует новый экземпляр класса [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

Инициализирует новый экземпляр класса [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).<br/>            С пользовательским или неизвестным значением

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

Инициализирует новый экземпляр класса [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| is_transparency_protected | bool | если установлено в <c>true</c> [защищено от прозрачности]. |
| is_composite_protected | bool | если установлено в <c>true</c> [защищено от композитных]. |
| is_position_protected | bool | если установлено в <c>true</c> [защищено от позиционирования]. |

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

