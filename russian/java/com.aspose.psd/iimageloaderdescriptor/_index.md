---
title: "IImageLoaderDescriptor"
second_title: "Aspose.PSD for Java API Справочник"
description: "Дескриптор загрузчика изображения, указывающий свойства загрузчика."
type: docs
weight: 124
url: /ru/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Дескриптор загрузчика изображений, указывающий свойства загрузчика. Дескриптор загрузчика используется для преодоления необходимости содержать каждый экземпляр загрузчика изображений в памяти и проблем многопоточности.
## Методы

| Метод | Описание |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока и при необходимости используя  loadOptions . |
| [createInstance()](#createInstance--) | Создаёт новый экземпляр загрузчика. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока и при необходимости используя  loadOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Подробности формата файла, указанные в  loadOptions .  loadOptions  может быть null. |

**Returns:**
boolean -  true  если загрузчик изображений, созданный этим дескриптором, может читать изображение из потока; иначе,  false .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Создаёт новый экземпляр загрузчика.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
