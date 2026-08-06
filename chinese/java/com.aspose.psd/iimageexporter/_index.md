---
title: "IImageExporter"
second_title: "Aspose.PSD 的 Java API 参考"
description: "图像导出器。"
type: docs
weight: 121
url: /zh/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

图像导出器。可以将内部 Aspose.Imaging 格式的数据导出为指定的数据格式。
## Methods

| Method | 描述 |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | 将指定的图像数据导出为指定的数据格式。 |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 将指定的图像数据导出为指定的数据格式。 |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


将指定的图像数据导出为指定的数据格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要导出的图像数据。 |
| stream | java.io.OutputStream | 要导出数据的流。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 图像导出的选项 |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


将指定的图像数据导出为指定的数据格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 要导出的图像数据。 |
| stream | java.io.OutputStream | 要导出数据的流。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 图像导出的选项 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 边界矩形。 |

