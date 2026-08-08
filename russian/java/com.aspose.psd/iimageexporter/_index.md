---
title: "IImageExporter"
second_title: "Aspose.PSD for Java API Справочник"
description: "Экспортер изображения."
type: docs
weight: 121
url: /ru/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

Экспортер изображений. Может экспортировать данные из внутреннего формата Aspose.Imaging в указанный формат данных.
## Методы

| Метод | Описание |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Экспортирует указанные данные изображения в указанный формат данных. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Экспортирует указанные данные изображения в указанный формат данных. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Экспортирует указанные данные изображения в указанный формат данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Данные изображения для экспорта. |
| stream | java.io.OutputStream | Поток, в который экспортировать данные. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры экспорта изображения |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Экспортирует указанные данные изображения в указанный формат данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Данные изображения для экспорта. |
| stream | java.io.OutputStream | Поток, в который экспортировать данные. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Параметры экспорта изображения |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник границ. |

