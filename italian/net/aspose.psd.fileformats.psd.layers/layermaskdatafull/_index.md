---
title: Class LayerMaskDataFull
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull classe. Definisce la classe LayerMaskDataFull che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha sia maschere di livello che vettoriali. Altrimenti ALayerMaskDataShort viene utilizzato. ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. La lunghezza in byte di ImageData deve essere uguale alle proprietà MaskRectangle.Width  MaskRectangle.Height.
type: docs
weight: 2250
url: /it/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Definisce la classe LayerMaskDataFull che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha sia maschere di livello che vettoriali. Altrimenti, A[`LayerMaskDataShort`](../layermaskdatashort/) viene utilizzato. ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. La lunghezza in byte di ImageData deve essere uguale alle proprietà MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Ottiene o imposta il colore di sfondo. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Ottiene o imposta la posizione della maschera di livello inferiore. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Ottiene la dimensione dei dati della maschera di livello. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Ottiene o imposta il colore predefinito. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Ottiene o imposta la posizione della maschera raster inferiore di inclusione nel livello dell'immagine PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Ottiene o imposta la posizione della maschera raster sinistra di inclusione nel livello del file PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Ottiene o imposta la posizione della maschera raster destra di inclusione nel livello del file PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Ottiene o imposta la posizione superiore di chiusura della maschera raster nel livello dell'immagine PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Ottiene o imposta i flag della maschera di livello. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Ottiene o imposta i dati della maschera di livello (o la maschera combinata/finale se è presente una maschera vettoriale) nel file PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Ottiene o imposta la posizione della maschera di livello sinistra. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Ottiene o imposta la maschera[`Rectangle`](../../aspose.psd/rectangle/)della maschera di livello nel file PSD. Prende le proprietà sinistra, destra, superiore e inferiore e crea[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Ottiene o imposta i flag della maschera di livello utilizzati per la maschera utente/raster. Per la maschera vettoriale viene utilizzata la proprietà Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Ottiene o imposta la posizione corretta della maschera di livello. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Ottiene o imposta la posizione della maschera di livello superiore. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Ottiene o imposta i dati della maschera utente (raster) di un livello nel file PSD. (C'è una maschera vettoriale rateizzata nella proprietà MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Ottiene o imposta il rettangolo della maschera utente (che racchiude) nel livello dell'immagine PSD.. |

### Guarda anche

* class [LayerMaskData](../layermaskdata/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assemblea [Aspose.PSD](../../)


