---
title: "ListStructure Класс"
type: docs
weight: 90
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure/
---

**Summary:** The list structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ListStructure(key_name)](#ListStructure_key_name_1) | Инициализирует новый экземпляр класса [ListStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Определяет ключ структуры. |
| items_count | int | r | Получает количество элементов. |
| key | int | r | Получает ключ структуры. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает имя ключа. |
| length | int | r | Получает длину [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) в байтах. |
| types | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Получает или задает копию массива структур. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Получает длину заголовка. |
| [save(stream_container)](#save_stream_container_2) | Сохраняет структуру в указанный контейнер потока. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Сохраняет структуру в указанный контейнер потока. |


### Constructor: ListStructure(key_name) {#ListStructure_key_name_1}


```
 ListStructure(key_name) 
```

Инициализирует новый экземпляр класса [ListStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Имя ключа. |

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

