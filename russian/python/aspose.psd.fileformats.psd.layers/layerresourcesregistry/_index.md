---
title: "Класс LayerResourcesRegistry"
type: docs
weight: 1010
url: /ru/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Получает зарегистрированные дескрипторы. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Получает первый поддерживаемый дескриптор открывателя. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Получает первый поддерживаемый дескриптор по его имени типа. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Загружает [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) с использованием первого найденного открывателя, подходящего для указанного <paramref name=\"stream\" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Регистрирует открыватель. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Снимает регистрацию с открывателя. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Получает первый поддерживаемый дескриптор открывателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| psd_version | int | Версия PSD. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Дескриптор загрузчика ресурсов слоя или null, если для такого потока не поддерживается дескриптор загрузчика. |


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
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Первый найденный дескриптор открывателя или null, если такой дескриптор не найден. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Загружает [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) с использованием первого найденного открывателя, подходящего для указанного <paramref name=\"stream\" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| psd_version | int | Версия PSD. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Загруженный [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) или null, если открыватель не найден. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Регистрирует открыватель.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Дескриптор открывателя для регистрации. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Снимает регистрацию с открывателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Дескриптор открывателя для снятия регистрации. |

