---
title: "Класс PropertyStructure"
type: docs
weight: 130
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/
---

**Summary:** The property structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.PropertyStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PropertyStructure(key_name, class_id, key_id)](#PropertyStructure_key_name_class_id_key_id_1) | Инициализирует новый экземпляр класса [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Определяет ключ структуры. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает идентификатор класса. |
| class_name | string | r/w | Получает или задает имя класса. |
| key | int | r | Получает ключ структуры. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает идентификатор ключа. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает имя ключа. |
| length | int | r | Получает длину [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) в байтах. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Получает длину заголовка. |
| [save(stream_container)](#save_stream_container_2) | Сохраняет структуру в указанный контейнер потока. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Сохраняет структуру в указанный контейнер потока. |


### Constructor: PropertyStructure(key_name, class_id, key_id) {#PropertyStructure_key_name_class_id_key_id_1}


```
 PropertyStructure(key_name, class_id, key_id) 
```

Инициализирует новый экземпляр класса [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Имя ключа. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор класса. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор ключа. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Получает длину заголовка.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Длина заголовка |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Сохраняет структуру в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Сохраняет структуру в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |

