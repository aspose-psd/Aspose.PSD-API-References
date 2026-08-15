---
title: "Класс AnimatedDataSectionResource"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---

**Summary:** The Animated Data Section Plug-In resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.AnimatedDataSectionResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Подпись ресурса ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Обычная подпись ресурса Photoshop. |
| animated_data_section | [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | r | Получает или задает структуру анимированного раздела данных. |
| data_size | int | r | Получает размер данных ресурса в байтах. |
| id | short | r/w | Получает или задает уникальный идентификатор ресурса. |
| key_name | string | r | Имя ключа ресурса. |
| minimal_version | int | r | Получает минимальную требуемую версию PSD. |
| name | string | r/w | Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| signature | int | r | Получает подпись ресурса. Должна всегда быть '8BIM'. |
| размер | int | r | Получает размер блока ресурса в байтах, включая его данные. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream)](#save_stream_1) | Сохраняет данные блока ресурсов. |
| validate_values() | Проверяет значения ресурса. |


### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Сохраняет данные блока ресурсов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

