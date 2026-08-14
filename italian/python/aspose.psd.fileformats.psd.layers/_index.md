---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /it/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Classe** | **Description** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | La classe del livello artboard. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | L'intervallo di fusione. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | Le informazioni del canale. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | La sezione della maschera di livello globale. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Interfaccia di base per le impostazioni di riempimento |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | Il caricatore delle risorse del livello. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Descrive le proprietà del livello Shape. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Il livello psd. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | I dati degli intervalli di fusione del livello. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Classe del livello di gruppo |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Calcolatore di hash per i livelli PSD. Può essere usato per trovare livelli uguali o diversi in diversi file PSD |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Definisce la classe base LayerMaskData che contiene informazioni sui dati della maschera di livello nel file PSD.<br/>            Può aiutare a modificare i file Adobe® Photoshop® programmaticamente e automatizzare la modifica del formato PSD.<br/>            Se il livello ha solo una maschera raster, ImageData contiene i byte dei dati della maschera raster.<br/>            Se il livello ha solo una maschera vettoriale, ImageData contiene i byte dei dati della maschera vettoriale rasterizzata (memorizzata nella cache).<br/>            Se il livello ha sia maschere di livello che vettoriali, ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate.<br/>            La lunghezza in byte di [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) dovrebbe essere uguale a Larghezza * Altezza delle proprietà [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/).<br/>            Nota che rimuovere / aggiungere / aggiornare semplicemente il LayerMaskData non è sufficiente per un salvataggio corretto<br/>            perché i canali non vengono aggiornati; tuttavia può fornire un rendering corretto.<br/>            Il metodo [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) dovrebbe essere usato per questo. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Definisce la classe LayerMaskDataFull che contiene informazioni sui dati della maschera nel livello del file PSD<br/>            quando il livello ha sia maschere di livello che vettoriali. Altrimenti, viene usata una [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/).<br/>            ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate.<br/>            La lunghezza in byte di ImageData dovrebbe essere uguale alle proprietà MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Definisce la classe LayerMaskDataShort che contiene informazioni sui dati della maschera nel livello del file PSD<br/>            quando il livello ha solo una maschera raster o vettoriale ma non entrambe. Altrimenti, viene usata una [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/).<br/>            Se il livello ha solo una maschera raster, ImageData contiene i byte dei dati della maschera raster.<br/>            Se il livello ha solo una maschera vettoriale, ImageData contiene i byte dei dati della maschera vettoriale rasterizzata (memorizzata nella cache).<br/>            La lunghezza in byte di [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) dovrebbe essere uguale a Larghezza * Altezza delle proprietà [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/). |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Rappresenta le informazioni del livello. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Definisci il registro delle risorse del livello per il caricamento dei file PSD. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Classe del gestore dei livelli collegati. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | Il livello divisore di sezione per segnare i limiti della cartella (gruppo di livelli). |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Livello Shape. Incapsula la logica di lavoro con il livello Shape e le risorse correlate. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | La classe del livello di testo |
## **Enumerations**
| **Enumerazione** | **Description** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | I flag del livello |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | I flag della maschera del livello |
