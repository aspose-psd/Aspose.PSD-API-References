---
title: "Класс GlobalAltitudeResource"
type: docs
weight: 90
url: /ru/python-net/aspose.psd.fileformats.psd.resources/globalaltituderesource/
---

**Summary:** Global altitude resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GlobalAltitudeResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GlobalAltitudeResource()](#GlobalAltitudeResource__1) | Инициализирует новый экземпляр класса GlobalAltitudeResource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Подпись ресурса ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Обычная подпись ресурса Photoshop. |
| высота | int | r/w | Получает или задает высоту. |
| data_size | int | r | Получает размер данных ресурса в байтах. |
| id | short | r/w | Получает или задает уникальный идентификатор ресурса. |
| minimal_version | int | r | Получает минимальную требуемую версию PSD. |
| name | string | r/w | Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| signature | int | r | Получает подпись ресурса. Должна всегда быть '8BIM'. |
| размер | int | r | Получает размер блока ресурса в байтах, включая его данные. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream)](#save_stream_1) | Сохраняет блок ресурса в указанный поток. |
| validate_values() | Проверяет значения ресурса. |


### Constructor: GlobalAltitudeResource() {#GlobalAltitudeResource__1}


```
 GlobalAltitudeResource() 
```

Инициализирует новый экземпляр класса GlobalAltitudeResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Сохраняет блок ресурса в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Поток, в который сохраняется блок ресурса. |

