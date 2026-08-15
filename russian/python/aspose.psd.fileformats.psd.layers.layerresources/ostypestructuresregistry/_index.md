---
title: "Класс OSTypeStructuresRegistry"
type: docs
weight: 720
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | Получает зарегистрированные дескрипторы. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Получает первый поддерживаемый дескриптор открывателя. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Получает первый поддерживаемый дескриптор по его имени типа. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | Загружает [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) с использованием первого найденного открывателя, подходящего для указанного <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Регистрирует открыватель. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Снимает регистрацию с открывателя. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Получает первый поддерживаемый дескриптор открывателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Дескриптор загрузчика ресурсов слоя или null, если для такого потока не поддерживается дескриптор загрузчика. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Получает первый поддерживаемый дескриптор по его имени типа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| descriptor_type_name | string | Имя типа дескриптора. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Первый найденный дескриптор открывателя или null, если такой дескриптор не найден. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

Загружает [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) с использованием первого найденного открывателя, подходящего для указанного <paramref name="stream" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Загруженный [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) или null, если открыватель не найден. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Регистрирует открыватель.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Дескриптор открывателя для регистрации. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Снимает регистрацию с открывателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Дескриптор открывателя для снятия регистрации. |

