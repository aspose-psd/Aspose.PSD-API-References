---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD per riferimento API .NET
description: Lo spazio dei nomi contiene layer in formato file PSD.
type: docs
weight: 210
url: /it/net/aspose.psd.fileformats.psd.layers/
---
Lo spazio dei nomi contiene layer in formato file PSD.

## Classi

| Classe | Descrizione |
| --- | --- |
| [BlendRange](./blendrange/) | L'intervallo di fusione. |
| [ChannelInformation](./channelinformation/) | Le informazioni sul canale. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | La sezione della maschera di livello globale. |
| [Layer](./layer/) | Il livello psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | La fusione dei livelli varia i dati. |
| [LayerGroup](./layergroup/) | Classe livello di gruppo |
| [LayerHashCalculator](./layerhashcalculator/) | Calcolatrice hash per livelli PSD. Può essere utilizzato per trovare livelli uguali o diversi in diversi file PSD |
| [LayerMaskData](./layermaskdata/) | Definisce la classe LayerMaskData di base che contiene informazioni sui dati della maschera di livello nel file PSD. Può aiutare a modificare i file Adobe® Photoshop® a livello di programmazione e automatizzare la modifica del formato PSD. Se il livello ha solo una maschera raster, ImageData contiene il raster maschera byte di dati. Se il livello ha solo una maschera vettoriale, ImageData contiene i byte di dati rasterizzati (memorizzati nella cache) della maschera vettoriale. Se il livello ha sia maschere di livello che vettoriali, ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. IL[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)la lunghezza dei byte deve essere uguale Larghezza * Altezza di[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Si noti che la semplice rimozione/aggiunta/aggiornamento di LayerMaskData non è sufficiente per il corretto salvataggio perché i canali non vengono aggiornati; sebbene possa fornire un rendering corretto. The[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) metodo dovrebbe essere usato per quello. |
| [LayerMaskDataFull](./layermaskdatafull/) | Definisce la classe LayerMaskDataFull che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha sia maschere di livello che vettoriali. Altrimenti, A[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) viene utilizzato. ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. La lunghezza in byte di ImageData deve essere uguale alle proprietà MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Definisce la classe LayerMaskDataShort che contiene informazioni sui dati della maschera nel file PSD layer quando il livello ha solo una maschera raster o vettoriale ma non entrambe. Altrimenti, A[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) viene utilizzato. Se il livello ha solo una maschera raster, ImageData contiene i byte di dati della maschera raster. Se il livello ha solo una maschera vettoriale, ImageData contiene i byte di dati rasterizzati (memorizzati nella cache) della maschera vettoriale. Il[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)la lunghezza dei byte deve essere uguale Larghezza * Altezza di[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) proprietà. |
| [LayerResource](./layerresource/) | Rappresenta le informazioni sul livello. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Definisce il registro delle risorse del layer per il caricamento dei file PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Classe gestore livelli collegati. |
| [SectionDividerLayer](./sectiondividerlayer/) | Il layer divisore di sezione per contrassegnare i limiti della cartella (gruppo di layer). |
| [TextLayer](./textlayer/) | La classe del livello di testo |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Interfaccia di base per le impostazioni di riempimento |
| [ILayerResourceLoader](./ilayerresourceloader/) | Il caricatore di risorse del livello. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [LayerFlags](./layerflags/) | Il livello segnala |
| [LayerMaskFlags](./layermaskflags/) | La maschera di livello flags |


