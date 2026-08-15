---
title: "OffsetStructure Класс"
type: docs
weight: 110
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/offsetstructure/
---

**Summary:** The offset structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.OffsetStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [OffsetStructure(key_name, class_id)](#OffsetStructure_key_name_class_id_1) | Инициализирует новый экземпляр класса [OffsetStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/offsetstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Определяет ключ структуры. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает идентификатор класса. |
| class_name | string | r/w | Получает или задает имя класса. |
| key | int | r | Получает ключ структуры. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает имя ключа. |
| length | int | r | Получает длину [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) в байтах. |
| значение | int | r/w | Получает или задает целочисленное значение. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Получает длину заголовка. |
| [save(stream_container)](#save_stream_container_2) | Сохраняет структуру в указанный контейнер потока. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Сохраняет структуру в указанный контейнер потока. |


### Constructor: OffsetStructure(key_name, class_id) {#OffsetStructure_key_name_class_id_1}


```
 OffsetStructure(key_name, class_id) 
```

Инициализирует новый экземпляр класса [OffsetStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/offsetstructure/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Имя ключа. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор класса. |

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

