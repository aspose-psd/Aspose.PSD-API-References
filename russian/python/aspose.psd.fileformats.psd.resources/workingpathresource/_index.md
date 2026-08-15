---
title: "Класс WorkingPathResource"
type: docs
weight: 320
url: /ru/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Инициализирует новый экземпляр класса [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Подпись ресурса ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Обычная подпись ресурса Photoshop. |
| data_size | int | r | Получает размер данных ресурса в байтах. |
| id | short | r/w | Получает или задает уникальный идентификатор ресурса. |
| is_disabled | bool | r/w | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| is_inverted | bool | r/w | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| is_not_linked | bool | r/w | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| minimal_version | int | r | Получает минимальную требуемую версию PSD. |
| name | string | r/w | Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Получает или задает записи пути. |
| signature | int | r | Получает подпись ресурса. Должна всегда быть '8BIM'. |
| размер | int | r | Получает размер блока ресурса в байтах, включая его данные. |
| version | int | r/w | Получает или задает версию. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream)](#save_stream_1) | Сохраняет блок ресурса в указанный поток. |
| validate_values() | Проверяет значения ресурса. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Инициализирует новый экземпляр класса [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data_bytes | байт | Данные векторного пути. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Сохраняет блок ресурса в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Поток, в который сохраняется блок ресурса. |

