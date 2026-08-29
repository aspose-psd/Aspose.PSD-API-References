---
title: "IImageExporter"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De afbeeldingsexporteur."
type: docs
weight: 121
url: /nl/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

De afbeeldingsexporter. Kan gegevens exporteren van het interne Aspose.Imaging-formaat naar een gespecificeerd gegevensformaat.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Exporteert de opgegeven afbeeldingsgegevens naar het gespecificeerde gegevensformaat. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Exporteert de opgegeven afbeeldingsgegevens naar het gespecificeerde gegevensformaat. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Exporteert de opgegeven afbeeldingsgegevens naar het gespecificeerde gegevensformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeeldingsgegevens om te exporteren. |
| stream | java.io.OutputStream | De stream om gegevens naar te exporteren. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opties voor afbeeldingsexport |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Exporteert de opgegeven afbeeldingsgegevens naar het gespecificeerde gegevensformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeeldingsgegevens om te exporteren. |
| stream | java.io.OutputStream | De stream om gegevens naar te exporteren. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opties voor afbeeldingsexport |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De begrenzingsrechthoek. |

