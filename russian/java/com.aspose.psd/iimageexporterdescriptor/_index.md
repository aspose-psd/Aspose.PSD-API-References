---
title: "IImageExporterDescriptor"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет дескриптор экспортера изображения."
type: docs
weight: 122
url: /ru/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Представляет дескриптор экспортера изображений. Дескриптор экспортера используется для устранения необходимости содержать каждый экземпляр экспортера в памяти и проблем многопоточности.
## Методы

| Метод | Описание |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Определяет, может ли экспортёр изображений экспортировать указанное изображение в указанный формат изображения, заданный параметрами сохранения. |
| [createInstance()](#createInstance--) | Создаёт новый экземпляр экспортёра. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Определяет, может ли экспортёр изображений экспортировать указанное изображение в указанный формат изображения, заданный параметрами сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для экспорта. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | База параметров. |

**Returns:**
boolean -  true  если экспортёр, созданный этим дескриптором, может экспортировать указанное изображение в указанный формат файла; иначе  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Создаёт новый экземпляр экспортёра.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
