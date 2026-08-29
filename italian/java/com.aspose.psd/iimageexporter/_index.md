---
title: "IImageExporter"
second_title: "Riferimento API Aspose.PSD per Java"
description: "L'esportatore di immagini."
type: docs
weight: 121
url: /it/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

L'esportatore di immagini. Può esportare dati dal formato interno Aspose.Imaging a un formato dati specificato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Esporta i dati immagine specificati nel formato dati specificato. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Esporta i dati immagine specificati nel formato dati specificato. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Esporta i dati immagine specificati nel formato dati specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | I dati immagine da esportare. |
| stream | java.io.OutputStream | Il flusso verso cui esportare i dati. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opzioni per l'esportazione di immagini |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Esporta i dati immagine specificati nel formato dati specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | I dati immagine da esportare. |
| stream | java.io.OutputStream | Il flusso verso cui esportare i dati. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opzioni per l'esportazione di immagini |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei limiti. |

