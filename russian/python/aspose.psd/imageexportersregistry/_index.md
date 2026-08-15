---
title: "Класс ImageExportersRegistry"
type: docs
weight: 2230
url: /ru/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Получает зарегистрированные дескрипторы экспортеров. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Получает зарегистрированные форматы экспорта. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Регистрирует указанный дескриптор экспортера изображения. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Регистрирует экспортёр. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Снимает регистрацию экспортёра. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для экспорта. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры сохранения, используемые для экспорта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Экспортёр, который поддерживает указанное изображение и параметры сохранения, или null, если такой экспортёр не найден. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для экспорта. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Дескриптор экспортёра, который поддерживает указанное изображение и параметры сохранения, или null, если такой дескриптор не найден. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Регистрирует указанный дескриптор экспортера изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Дескриптор экспортёра изображений. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Регистрирует экспортёр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Дескриптор экспортёра для регистрации. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Снимает регистрацию экспортёра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Дескриптор экспортёра для снятия регистрации. |

