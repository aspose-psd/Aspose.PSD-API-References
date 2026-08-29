---
title: "IImageExporter"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Bildexporter."
type: docs
weight: 121
url: /de/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

Der Bildexporter. Kann Daten aus dem internen Aspose.Imaging-Format in ein angegebenes Datenformat exportieren.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Exportiert die angegebenen Bilddaten in das angegebene Datenformat. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Exportiert die angegebenen Bilddaten in das angegebene Datenformat. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Exportiert die angegebenen Bilddaten in das angegebene Datenformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Die zu exportierenden Bilddaten. |
| stream | java.io.OutputStream | Der Stream, in den Daten exportiert werden sollen. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Optionen für den Bildexport |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Exportiert die angegebenen Bilddaten in das angegebene Datenformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Die zu exportierenden Bilddaten. |
| stream | java.io.OutputStream | Der Stream, in den Daten exportiert werden sollen. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Optionen für den Bildexport |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Begrenzungsrechteck. |

