---
title: "IRasterImageRawDataLoader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il caricatore di dati grezzi dell'immagine raster."
type: docs
weight: 137
url: /it/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

Il caricatore di dati grezzi dell'immagine raster.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Ottiene le impostazioni attuali dei dati grezzi. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Restituisce un valore che indica se il caricamento di dati grezzi è supportato. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Carica dati grezzi. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Ottiene le impostazioni attuali dei dati grezzi. Nota che quando si usano queste impostazioni i dati vengono caricati senza conversione.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Restituisce un valore che indica se il caricamento di dati grezzi è supportato.

**Returns:**
boolean -  true  se il caricamento di dati grezzi è supportato; altrimenti,  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carica dati grezzi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da cui caricare i dati grezzi. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Le impostazioni dei dati grezzi da utilizzare per i dati caricati. Nota: se i dati non sono nel formato specificato, verrà eseguita la conversione dei dati. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Il caricatore di dati grezzi. |

