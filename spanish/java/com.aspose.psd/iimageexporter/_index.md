---
title: "IImageExporter"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El exportador de imágenes."
type: docs
weight: 121
url: /es/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

El exportador de imágenes. Puede exportar datos del formato interno de Aspose.Imaging a un formato de datos especificado.
## Métodos

| Método | Descripción |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Exporta los datos de imagen especificados al formato de datos especificado. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Exporta los datos de imagen especificados al formato de datos especificado. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Exporta los datos de imagen especificados al formato de datos especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Los datos de imagen a exportar. |
| stream | java.io.OutputStream | El flujo al que exportar los datos. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opciones para la exportación de imágenes |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Exporta los datos de imagen especificados al formato de datos especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Los datos de imagen a exportar. |
| stream | java.io.OutputStream | El flujo al que exportar los datos. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opciones para la exportación de imágenes |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de límites. |

