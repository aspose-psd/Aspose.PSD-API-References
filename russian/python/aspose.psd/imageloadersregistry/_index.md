---
title: "Класс ImageLoadersRegistry"
type: docs
weight: 2260
url: /ru/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | Получает зарегистрированные дескрипторы. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Возвращает зарегистрированные форматы загрузки изображений. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Создаёт первый найденный загрузчик, подходящий для указанного <paramref name="stream" /> и, при необходимости, <paramref name="loadOptions" />. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Возвращает первый найденный поддерживаемый дескриптор, подходящий для указанного <paramref name="stream" /> и, при необходимости, <paramref name="loadOptions" />. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Возвращает первый поддерживаемый формат файла по его имени типа. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Получает первый поддерживаемый дескриптор по его имени типа. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Регистрирует указанный дескриптор загрузчика изображений. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Регистрирует загрузчик. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Снимает регистрацию загрузчика. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Создаёт первый найденный загрузчик, подходящий для указанного <paramref name="stream" /> и, при необходимости, <paramref name="loadOptions" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Загрузчик, поддерживающий указанные <paramref name="stream" /> и <paramref name="loadOptions" />, или null, если такой загрузчик не найден. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Возвращает первый найденный поддерживаемый дескриптор, подходящий для указанного <paramref name="stream" /> и, при необходимости, <paramref name="loadOptions" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Дескриптор загрузчика, поддерживающий указанные <paramref name="stream" /> и <paramref name="loadOptions" />, или null, если такой дескриптор не найден. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Возвращает первый поддерживаемый формат файла по его имени типа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | Поддерживаемый формат файла дескриптора. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Первый найденный дескриптор загрузчика или null, если такой дескриптор не найден. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


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
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Первый найденный дескриптор загрузчика или null, если такой дескриптор не найден. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Регистрирует указанный дескриптор загрузчика изображений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Дескриптор загрузчика изображений. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Регистрирует загрузчик.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Дескриптор загрузчика для регистрации. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Снимает регистрацию загрузчика.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Дескриптор загрузчика для снятия регистрации. |

