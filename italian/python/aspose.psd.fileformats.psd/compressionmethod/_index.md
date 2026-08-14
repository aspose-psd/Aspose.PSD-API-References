---
title: "CompressionMethod Enumerazione"
type: docs
weight: 2410
url: /it/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Definisce il metodo di compressione utilizzato per i dati dell'immagine.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Nome membro** | **Description** |
| :- | :- |
| RAW | Nessuna compressione. I dati dell'immagine sono memorizzati come byte grezzi in ordine planare RGBA.<br/>            Ciò significa che prima vengono scritti tutti i dati R, poi tutti i dati G, poi tutti i dati B e infine tutti i dati A. |
| RLE | I dati dell'immagine compressi con RLE iniziano con i conteggi dei byte per tutte le linee di scansione (righe * canali), con ciascun<br/>            conteggio memorizzato come valore a due byte. Seguono i dati compressi con RLE, con ogni linea di scansione compressa separatamente.<br/>            La compressione RLE è lo stesso algoritmo di compressione utilizzato dalla routine PackBits della ROM Macintosh e dallo standard TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP senza predizione. |
| ZIP_WITH_PREDICTION | ZIP con predizione. |
