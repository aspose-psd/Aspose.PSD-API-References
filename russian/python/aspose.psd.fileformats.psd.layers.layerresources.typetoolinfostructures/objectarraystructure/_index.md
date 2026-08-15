---
title: "ObjectArrayStructure Класс"
type: docs
weight: 100
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Summary:** Defines the ObjectArrayStructure class that usually holds [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) array.<br/>            It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ObjectArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ObjectArrayStructure(key, key_name, class_id, class_name, structures)](#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1) | Инициализирует новый экземпляр [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) класса. |
| [ObjectArrayStructure(key_name, class_id_name, structures)](#ObjectArrayStructure_key_name_class_id_name_structures_2) | Инициализирует новый экземпляр [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) класса. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Определяет ключ структуры 'ObAr'. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает ID класса объектного массива. |
| class_name | string | r/w | Получает или задает имя класса объектного массива. |
| key | int | r | Получает ключ структуры объектного массива. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает имя ключа. |
| length | int | r | Получает длину [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) в байтах. |
| structure_count | int | r | Получает количество подструктур объектного массива. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Получает или задает копию массива структур. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Получает длину заголовка. |
| [save(stream_container)](#save_stream_container_2) | Сохраняет структуру в указанный контейнер потока. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Сохраняет структуру в указанный контейнер потока. |


### Constructor: ObjectArrayStructure(key, key_name, class_id, class_name, structures) {#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1}


```
 ObjectArrayStructure(key, key_name, class_id, class_name, structures) 
```

Инициализирует новый экземпляр [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) класса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | int | Целочисленный ключ. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Имя ключа. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор класса. |
| class_name | string | Имя класса. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Структуры. |

### Constructor: ObjectArrayStructure(key_name, class_id_name, structures) {#ObjectArrayStructure_key_name_class_id_name_structures_2}


```
 ObjectArrayStructure(key_name, class_id_name, structures) 
```

Инициализирует новый экземпляр [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) класса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key_name | string | Имя ключа. |
| class_id_name | string | Имя идентификатора класса. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Структуры. |

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

