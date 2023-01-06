---
title: LayerMaskDataShort
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Definisce la classe LayerMaskDataShort che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha solo una maschera raster o vettoriale ma non entrambi. In caso contrario unLayerMaskDataFull./layermaskdatafull viene utilizzato. Se il livello ha solo una maschera raster ImageData contiene i byte di dati della maschera raster. Se il livello ha solo una maschera vettoriale ImageData contiene i byte di dati rasterizzati cache della maschera vettoriale. ImageData./layermaskdata/imagedatala lunghezza dei byte dovrebbe essere uguale Larghezza  Altezza diMaskRectangle./layermaskdata/maskrectangle proprietà.
type: docs
weight: 2240
url: /it/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Definisce la classe LayerMaskDataShort che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha solo una maschera raster o vettoriale ma non entrambi. In caso contrario, un[`LayerMaskDataFull`](../layermaskdatafull) viene utilizzato. Se il livello ha solo una maschera raster, ImageData contiene i byte di dati della maschera raster. Se il livello ha solo una maschera vettoriale, ImageData contiene i byte di dati rasterizzati (cache) della maschera vettoriale. [`ImageData`](../layermaskdata/imagedata)la lunghezza dei byte dovrebbe essere uguale Larghezza * Altezza di[`MaskRectangle`](../layermaskdata/maskrectangle) proprietà.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom) { get; set; } | Ottiene o imposta la posizione della maschera di livello inferiore. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize) { get; } | Ottiene la dimensione dei dati della maschera della maschera di livello. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor) { get; set; } | Ottiene o imposta il colore predefinito. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags) { get; set; } | Ottiene o imposta i flag della maschera di livello. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata) { get; set; } | Ottiene o imposta i dati della maschera di livello (o la maschera combinata/finale se è presente una maschera vettoriale) nel file PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left) { get; set; } | Ottiene o imposta la posizione della maschera di livello sinistra. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle) { get; set; } | Ottiene o imposta la maschera[`Rectangle`](../../aspose.psd/rectangle)della maschera di livello nel file PSD. Prende le proprietà sinistra, destra, alto e basso e crea[`Rectangle`](../../aspose.psd/rectangle) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding) { get; set; } | Ottiene o imposta il riempimento della maschera di livello. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right) { get; set; } | Ottiene o imposta la posizione corretta della maschera di livello. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top) { get; set; } | Ottiene o imposta la posizione della maschera di livello superiore. |

### Guarda anche

* class [LayerMaskData](../layermaskdata)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->