---
title: "IImageExporter"
second_title: "Java için Aspose.PSD API Referansı"
description: "Görüntü dışa aktarıcı."
type: docs
weight: 121
url: /tr/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

Görüntü dışa aktarıcı. İç dahili Aspose.Imaging formatından belirtilen bir veri formatına veri dışa aktarabilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Belirtilen görüntü verisini belirtilen veri formatına dışa aktarır. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Belirtilen görüntü verisini belirtilen veri formatına dışa aktarır. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Belirtilen görüntü verisini belirtilen veri formatına dışa aktarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Dışa aktarılacak görüntü verisi. |
| stream | java.io.OutputStream | Verinin dışa aktarılacağı akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Görüntü dışa aktarımı seçenekleri |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Belirtilen görüntü verisini belirtilen veri formatına dışa aktarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Dışa aktarılacak görüntü verisi. |
| stream | java.io.OutputStream | Verinin dışa aktarılacağı akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Görüntü dışa aktarımı seçenekleri |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Sınır dikdörtgeni. |

