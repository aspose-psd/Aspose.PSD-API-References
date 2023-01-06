---
title: LayerMaskDataFull
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Definisce la classe LayerMaskDataFull che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha sia maschere di livello che vettoriali. In caso contrario unLayerMaskDataShort./layermaskdatashort è utilizzato. ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. La lunghezza dei byte di ImageData deve essere uguale MaskRectangle.Width  MaskRectangle.Height properties.
type: docs
weight: 2230
url: /it/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Definisce la classe LayerMaskDataFull che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha sia maschere di livello che vettoriali. In caso contrario, un[`LayerMaskDataShort`](../layermaskdatashort) è utilizzato. ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. La lunghezza dei byte di ImageData deve essere uguale MaskRectangle.Width * MaskRectangle.Height properties.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom) { get; set; } | Ottiene o imposta la posizione della maschera di livello inferiore. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize) { get; } | Ottiene la dimensione dei dati della maschera della maschera di livello. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor) { get; set; } | Ottiene o imposta il colore predefinito. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom) { get; set; } | Ottiene o imposta la posizione della maschera raster inferiore che racchiude nel livello dell'immagine PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft) { get; set; } | Ottiene o imposta la posizione della maschera raster sinistra che racchiude nel livello del file PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright) { get; set; } | Ottiene o imposta la posizione della maschera raster destra che racchiude nel livello del file PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop) { get; set; } | Ottiene o imposta la posizione superiore che racchiude la maschera raster nel livello immagine PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags) { get; set; } | Ottiene o imposta i flag della maschera di livello. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata) { get; set; } | Ottiene o imposta i dati della maschera di livello (o la maschera combinata/finale se è presente una maschera vettoriale) nel file PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left) { get; set; } | Ottiene o imposta la posizione della maschera di livello sinistra. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle) { get; set; } | Ottiene o imposta la maschera[`Rectangle`](../../aspose.psd/rectangle)della maschera di livello nel file PSD. Prende le proprietà sinistra, destra, alto e basso e crea[`Rectangle`](../../aspose.psd/rectangle) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags) { get; set; } | Ottiene o imposta i flag della maschera di livello utilizzati per la maschera utente/raster. Per la maschera vettoriale viene utilizzata la proprietà Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right) { get; set; } | Ottiene o imposta la posizione corretta della maschera di livello. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top) { get; set; } | Ottiene o imposta la posizione della maschera di livello superiore. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata) { get; set; } | Ottiene o imposta i dati della maschera utente (raster) di un livello nel file PSD. (Esiste una maschera vettoriale classificata nella proprietà MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle) { get; set; } | Ottiene o imposta il rettangolo della maschera utente (che racchiude) nel livello dell'immagine PSD.. |

### Guarda anche

* class [LayerMaskData](../layermaskdata)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->