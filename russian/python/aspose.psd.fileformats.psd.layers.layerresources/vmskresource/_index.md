---
title: "Класс VmskResource"
type: docs
weight: 1100
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---

**Summary:** Class VmskResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VmskResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [VmskResource()](#VmskResource__1) | Инициализирует новый экземпляр класса [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/). |
| [VmskResource(data)](#VmskResource_data_2) | Инициализирует новый экземпляр класса [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| is_disabled | bool | r/w | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| is_inverted | bool | r/w | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| is_not_linked | bool | r/w | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Получает или задает записи пути. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| version | int | r/w | Получает или задает версию. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: VmskResource() {#VmskResource__1}


```
 VmskResource() 
```

Инициализирует новый экземпляр класса [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/).

### Constructor: VmskResource(data) {#VmskResource_data_2}


```
 VmskResource(data) 
```

Инициализирует новый экземпляр класса [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/).

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

