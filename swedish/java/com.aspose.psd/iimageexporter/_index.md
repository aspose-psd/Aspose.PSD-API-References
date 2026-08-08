---
title: "IImageExporter"
second_title: "Aspose.PSD för Java API-referens"
description: "Bildexportören."
type: docs
weight: 121
url: /sv/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

Bildexportören. Kan exportera data från internt Aspose.Imaging-format till ett angivet dataformat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Exporterar den angivna bilddatan till angivet dataformat. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Exporterar den angivna bilddatan till angivet dataformat. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Exporterar den angivna bilddatan till angivet dataformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilddatan att exportera. |
| stream | java.io.OutputStream | Strömmen att exportera data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativ för bildexport |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Exporterar den angivna bilddatan till angivet dataformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilddatan att exportera. |
| stream | java.io.OutputStream | Strömmen att exportera data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativ för bildexport |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Den avgränsande rektangeln. |

