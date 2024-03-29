---
title: Enum CompressionMethod
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.CompressionMethod enum. Definisce il metodo di compressione utilizzato per i dati dellimmagine.
type: docs
weight: 1620
url: /it/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Definisce il metodo di compressione utilizzato per i dati dell'immagine.

```csharp
public enum CompressionMethod : short
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Raw | `0` | Nessuna compressione. I dati dell'immagine memorizzati come byte grezzi nell'ordine planare RGBA. Ciò significa che prima vengono scritti tutti i dati R, quindi vengono scritti tutti i dati G, quindi vengono scritti tutti i dati B e infine tutti i dati A. |
| RLE | `1` | RLE compressi i dati dell'immagine iniziano con i conteggi di byte per tutte le linee di scansione (righe * canali), con ciascun conteggio memorizzato come valore a due byte. Seguono i dati compressi RLE, con ogni riga di scansione compressa separatamente. La compressione RLE è lo stesso algoritmo di compressione utilizzato dalla routine ROM Macintosh PackBits e dallo standard TIFF. |
| ZipWithoutPrediction | `2` | ZIP senza previsione. |
| ZipWithPrediction | `3` | ZIP con previsione. |

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assemblea [Aspose.PSD](../../)


