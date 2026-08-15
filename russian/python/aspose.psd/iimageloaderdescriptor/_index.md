---
title: "Класс IImageLoaderDescriptor"
type: docs
weight: 1820
url: /ru/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Получает поддерживаемый формат. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Определяет, может ли загрузчик изображений читать новое изображение из указанного потока и при необходимости использовать <paramref name=\"loadOptions\" />. |
| [create_instance()](#create_instance__2) | Создаёт новый экземпляр загрузчика. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Определяет, может ли загрузчик изображений читать новое изображение из указанного потока и при необходимости использовать <paramref name=\"loadOptions\" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Подробности формата файла, указанные в <paramref name=\"loadOptions\" />. <paramref name=\"loadOptions\" /> может быть null. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c>, если загрузчик изображений, созданный этим дескриптором, может читать изображение из потока; иначе <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Создаёт новый экземпляр загрузчика.

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Новый экземпляр загрузчика. |


