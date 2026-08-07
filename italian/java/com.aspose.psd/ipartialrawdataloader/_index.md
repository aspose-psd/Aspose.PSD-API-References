---
title: "IPartialRawDataLoader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il caricatore di dati parziali."
type: docs
weight: 133
url: /it/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

Il caricatore di dati parziali.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Elabora i dati caricati. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Elabora i dati caricati. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Elabora i dati caricati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei dati. |
| dati | byte[] | I dati grezzi. |
| start | [Point](../../com.aspose.psd/point) | Il punto dati iniziale. Se non è uguale a (left,top) significa che non è un rettangolo completo. |
| end | [Point](../../com.aspose.psd/point) | Il punto dati finale. Se non è uguale a (right,bottom) significa che non è un rettangolo completo. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Elabora i dati caricati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei dati. |
| dati | byte[] | I dati grezzi. |
| start | [Point](../../com.aspose.psd/point) | Il punto dati iniziale. Se non è uguale a (left,top) significa che non è un rettangolo completo. |
| end | [Point](../../com.aspose.psd/point) | Il punto dati finale. Se non è uguale a (right,bottom) significa che non è un rettangolo completo. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

