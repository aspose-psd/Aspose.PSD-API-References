---
title: Class LayerMaskData
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData classe. Definisce la classe LayerMaskData di base che contiene informazioni sui dati della maschera di livello nel file PSD. Può aiutare a modificare i file Adobe Photoshop a livello di programmazione e automatizzare la modifica del formato PSD. Se il livello ha solo una maschera raster ImageData contiene il raster maschera byte di dati. Se il livello ha solo una maschera vettoriale ImageData contiene i byte di dati rasterizzati memorizzati nella cache della maschera vettoriale. Se il livello ha sia maschere di livello che vettoriali ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. ILImageDatala lunghezza dei byte deve essere uguale Larghezza  Altezza diMaskRectangle properties. Si noti che la semplice rimozione/aggiunta/aggiornamento di LayerMaskData non è sufficiente per il corretto salvataggio perché i canali non vengono aggiornati sebbene possa fornire un rendering corretto. TheAddLayerMask metodo dovrebbe essere usato per quello.
type: docs
weight: 2240
url: /it/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

Definisce la classe LayerMaskData di base che contiene informazioni sui dati della maschera di livello nel file PSD. Può aiutare a modificare i file Adobe® Photoshop® a livello di programmazione e automatizzare la modifica del formato PSD. Se il livello ha solo una maschera raster, ImageData contiene il raster maschera byte di dati. Se il livello ha solo una maschera vettoriale, ImageData contiene i byte di dati rasterizzati (memorizzati nella cache) della maschera vettoriale. Se il livello ha sia maschere di livello che vettoriali, ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. IL[`ImageData`](./imagedata/)la lunghezza dei byte deve essere uguale Larghezza * Altezza di[`MaskRectangle`](./maskrectangle/) properties. Si noti che la semplice rimozione/aggiunta/aggiornamento di LayerMaskData non è sufficiente per il corretto salvataggio perché i canali non vengono aggiornati; sebbene possa fornire un rendering corretto. The[`AddLayerMask`](../layer/addlayermask/) metodo dovrebbe essere usato per quello.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Ottiene o imposta la posizione corretta della maschera di livello. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Ottiene o imposta la posizione della maschera di livello superiore. |

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assemblea [Aspose.PSD](../../)


