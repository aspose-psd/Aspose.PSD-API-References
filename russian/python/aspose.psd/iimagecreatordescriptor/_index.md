---
title: "Класс IImageCreatorDescriptor"
type: docs
weight: 1770
url: /ru/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Получает поддерживаемый формат. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Определяет, может ли создатель изображения создать новое изображение, используя <paramref name="imageOptions" />. |
| [create_instance()](#create_instance__2) | Создает новый экземпляр создателя. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Определяет, может ли создатель изображения создать новое изображение, используя <paramref name="imageOptions" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>True</c> если создатель изображения, созданный этим дескриптором, может создавать данные изображения, используя указанный <paramref name="imageOptions" />; в противном случае <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Создает новый экземпляр создателя.

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Новый экземпляр создателя. |


