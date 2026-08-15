---
title: "RawDataStructure Класс"
type: docs
weight: 140
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure/
---

**Summary:** The raw data structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.RawDataStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [RawDataStructure(key_name)](#RawDataStructure_key_name_1) | Инициализирует новый экземпляр класса [RawDataStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Определяет ключ структуры. |
| данные | байт | r/w | Получает или задает данные. |
| key | int | r | Получает ключ. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает имя ключа. |
| length | int | r | Получает длину [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) в байтах. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Получает длину заголовка. |
| [save(stream_container)](#save_stream_container_2) | Сохраняет структуру в указанный контейнер потока. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Сохраняет структуру в указанный контейнер потока. |


### Constructor: RawDataStructure(key_name) {#RawDataStructure_key_name_1}


```
 RawDataStructure(key_name) 
```

Инициализирует новый экземпляр класса [RawDataStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure/).

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

