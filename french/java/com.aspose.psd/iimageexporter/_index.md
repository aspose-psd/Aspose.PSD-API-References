---
title: "IImageExporter"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "L'exportateur d'image."
type: docs
weight: 121
url: /fr/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

L'exportateur d'images. Peut exporter des données du format interne Aspose.Imaging vers un format de données spécifié.
## Méthodes

| Méthode | Description |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Exporte les données d'image spécifiées dans le format de données spécifié. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Exporte les données d'image spécifiées dans le format de données spécifié. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Exporte les données d'image spécifiées dans le format de données spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Les données d'image à exporter. |
| stream | java.io.OutputStream | Le flux vers lequel exporter les données. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Options pour l'exportation d'images |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Exporte les données d'image spécifiées dans le format de données spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Les données d'image à exporter. |
| stream | java.io.OutputStream | Le flux vers lequel exporter les données. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Options pour l'exportation d'images |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites. |

