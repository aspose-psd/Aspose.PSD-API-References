---
title: "IImageCreatorDescriptor"
second_title: "Aspose.PSD for Java API Справочник"
description: "Дескриптор создателя изображения, указывающий свойства создателя."
type: docs
weight: 119
url: /ru/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Дескриптор image creator descriptor, указывающий свойства creator properties. Дескриптор creator используется для преодоления необходимости хранить каждый image creator instance в памяти и проблем многопоточности.
## Методы

| Метод | Описание |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | Определяет, может ли image creator создать новое изображение, используя  imageOptions . |
| [createInstance()](#createInstance--) | Создаёт новый экземпляр создателя. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Определяет, может ли image creator создать новое изображение, используя  imageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры изображения. |

**Returns:**
boolean -  true  если image creator, созданный этим дескриптором, может создавать данные изображения, используя указанные  imageOptions ; иначе,  false .
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Создаёт новый экземпляр создателя.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
