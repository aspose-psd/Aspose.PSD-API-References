---
title: Class LayerMaskDataShort
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort classe. Definisce la classe LayerMaskDataShort che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha solo una maschera raster o vettoriale ma non entrambe. Altrimenti ALayerMaskDataFull viene utilizzato. Se il livello ha solo una maschera raster ImageData contiene i byte di dati della maschera raster. Se il livello ha solo una maschera vettoriale ImageData contiene i byte di dati rasterizzati memorizzati nella cache della maschera vettoriale. IlImageDatala lunghezza dei byte deve essere uguale Larghezza  Altezza diMaskRectangle proprietà.
type: docs
weight: 2260
url: /it/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Definisce la classe LayerMaskDataShort che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha solo una maschera raster o vettoriale ma non entrambe. Altrimenti, A[`LayerMaskDataFull`](../layermaskdatafull/) viene utilizzato. Se il livello ha solo una maschera raster, ImageData contiene i byte di dati della maschera raster. Se il livello ha solo una maschera vettoriale, ImageData contiene i byte di dati rasterizzati (memorizzati nella cache) della maschera vettoriale. Il[`ImageData`](../layermaskdata/imagedata/)la lunghezza dei byte deve essere uguale Larghezza * Altezza di[`MaskRectangle`](../layermaskdata/maskrectangle/) proprietà.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Ottiene o imposta la posizione della maschera di livello inferiore. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Ottiene la dimensione dei dati della maschera di livello. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Ottiene o imposta il colore predefinito. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Ottiene o imposta i flag della maschera di livello. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Ottiene o imposta i dati della maschera di livello (o la maschera combinata/finale se è presente una maschera vettoriale) nel file PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Ottiene o imposta la posizione della maschera di livello sinistra. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Ottiene o imposta la maschera[`Rectangle`](../../aspose.psd/rectangle/)della maschera di livello nel file PSD. Prende le proprietà sinistra, destra, superiore e inferiore e crea[`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Ottiene o imposta il riempimento della maschera di livello. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Ottiene o imposta la posizione corretta della maschera di livello. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Ottiene o imposta la posizione della maschera di livello superiore. |

### Guarda anche

* class [LayerMaskData](../layermaskdata/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assemblea [Aspose.PSD](../../)


