---
title: "Класс ImageCreatorsRegistry"
type: docs
weight: 2210
url: /ru/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Получает зарегистрированные дескрипторы. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Возвращает зарегистрированные форматы создания изображений. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Создаёт первый найденный создатель, подходящий для указанного. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанного. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Регистрирует указанный дескриптор создателя изображения. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Регистрирует создателя. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Снимает регистрацию создателя. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Создаёт первый найденный создатель, подходящий для указанного.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Создатель, поддерживающий указанный, или null, если такой создатель не найден. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Получает первый найденный поддерживаемый дескриптор, подходящий для указанного.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Дескриптор создателя, поддерживающий указанный, или null, если такой дескриптор не найден. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Регистрирует указанный дескриптор создателя изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Дескриптор создателя изображения. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Регистрирует создателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Дескриптор создателя для регистрации. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Снимает регистрацию создателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Дескриптор создателя. |

