---
title: PsdImage
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Definisce la classe PsdImage che offre la possibilità di caricare modificare salvare file PSD nonché aggiornare le proprietà aggiungere filigrane eseguire operazioni grafiche o convertire un formato file in un altro. Aspose.PSD supporta limportazione come livello e lesportazione in seguenti formati Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb insieme allesportazione in Pdf con testo selezionabile
type: docs
weight: 3530
url: /it/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Definisce la classe PsdImage che offre la possibilità di caricare, modificare, salvare file PSD nonché aggiornare le proprietà, aggiungere filigrane, eseguire operazioni grafiche o convertire un formato file in un altro. Aspose.PSD supporta l'importazione come livello e l'esportazione in seguenti formati: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb insieme all'esportazione in Pdf con testo selezionabile

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PsdImage](psdimage#constructor)(RasterImage) | Inizializza una nuova istanza di[`PsdImage`](../psdimage)classe da immagine raster esistente (non immagine psd) con modalità colore RGB con 4 canali 8 bit/canale e nessuna compressione. |
| [PsdImage](psdimage#constructor_4)(Stream) | Inizializza una nuova istanza di[`PsdImage`](../psdimage) classe dal percorso specificato dall'immagine raster (non immagine psd nel flusso). Utilizzato per inizializzare l'immagine psd con parametri predefiniti - Modalità colore - RGB, 4 canali, 8 bit per canale, Compressione - Raw. |
| [PsdImage](psdimage#constructor_6)(string) | Inizializza una nuova istanza di[`PsdImage`](../psdimage) classe dal percorso specificato dall'immagine raster (non immagine psd nel percorso). Utilizzato per inizializzare l'immagine psd con parametri predefiniti - Modalità colore - RGB, 4 canali, 8 bit per canale, Compressione - Raw. |
| [PsdImage](psdimage#constructor_2)(int, int) | Inizializza una nuova istanza di[`PsdImage`](../psdimage) classe con larghezza e altezza specificate. Utilizzato per inizializzare l'immagine psd vuota. |
| [PsdImage](psdimage#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Inizializza una nuova istanza di[`PsdImage`](../psdimage) classe dall'immagine raster esistente (non immagine psd) con parametri del costruttore. |
| [PsdImage](psdimage#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Inizializza una nuova istanza di[`PsdImage`](../psdimage) classe dal percorso specificato dall'immagine raster (non immagine psd nel flusso) con parametri del costruttore. |
| [PsdImage](psdimage#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Inizializza una nuova istanza di[`PsdImage`](../psdimage) classe dal percorso specificato dall'immagine raster (non immagine psd nel percorso) con parametri del costruttore. |
| [PsdImage](psdimage#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Inizializza una nuova istanza di[`PsdImage`](../psdimage) classe con larghezza, altezza, tavolozza, modalità colore, conteggio canali e lunghezza in bit dei canali specificati e parametri della modalità di compressione specificati. Utilizzato per inizializzare l'immagine psd vuota. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer) { get; set; } | Ottiene o imposta il livello attivo. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel) { get; } | Ottiene i bit per canale. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount) { get; } | Ottiene il conteggio dei canali PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile) { get; set; } | Ottiene o imposta il profilo colore CMYK per le immagini PSD CMYK. Deve essere abbinato a RgbColorProfile per una corretta conversione del colore. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode) { get; set; } | Ottiene o imposta la modalità colore. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression) { get; } | Ottiene il metodo di compressione. |
| [Container](../../aspose.psd/image/container) { get; } | Ottiene il[`Image`](../../aspose.psd/image) contenitore. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat) { get; } | Ottiene un valore di formato file |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle) { get; set; } | Ottiene o imposta l'angolo globale. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo) { get; } | Ottiene le informazioni sulla maschera di livello globale. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources) { get; set; } | Ottiene o imposta le risorse del livello globale. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile) { get; set; } | Ottiene o imposta il profilo colore GRIGIO (monocromatico) per le immagini PSD in scala di grigi. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha) { get; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo[`RasterImage`](../../aspose.psd/rasterimage) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata) { get; set; } | Ottiene o imposta un valore che indica se il primo canale alfa contiene i dati di trasparenza per il risultato unito quando si specificano i dati dei livelli. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height) { get; } | Ottiene l'altezza dell'immagine. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo[`PsdImage`](../psdimage) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | Ottiene l'opacità di questa immagine. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources) { get; set; } | Ottiene o imposta le risorse dell'immagine PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten) { get; } | Ottiene un valore che indica se l'immagine psd è appiattita. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | Ottiene un valore che indica se è disponibile il caricamento dei dati grezzi. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers) { get; set; } | Ottiene o imposta i livelli PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager) { get; } | Ottiene il gestore dei livelli collegati. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore personalizzato |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat) { get; } | Ottiene il formato dei dati grezzi. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | Ottiene le impostazioni dei dati grezzi correnti. Nota quando si utilizzano queste impostazioni i dati vengono caricati senza conversione. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore indicizzato |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | Ottiene la dimensione della riga grezza in byte. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile) { get; set; } | Ottiene o imposta il profilo colore RGB per le immagini PSD CMYK. Deve essere abbinato a CmykColorProfile per una corretta conversione del colore. |
| [Size](../../aspose.psd/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider) { get; } | Ottiene il provider di oggetti intelligenti. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | Ottiene il colore trasparente dell'immagine. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando è disponibile il caricamento dei dati grezzi. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version) { get; set; } | Ottiene o imposta la versione. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution) { get; set; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo[`PsdImage`](../psdimage) . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width) { get; } | Ottiene la larghezza dell'immagine. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata) { get; set; } | Ottiene o imposta i metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer)() | Aggiunge il livello di regolazione del bianco nero. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer)(int, int) | Aggiunge il livello di regolazione della luminosità/contrasto. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer)() | Aggiunge il livello di regolazione del mixer del canale con i parametri predefiniti |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer)() | Aggiunge il livello di regolazione del bilanciamento del colore. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer)() | Aggiunge il livello di regolazione delle curve. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer)(float, float, float) | Aggiunge il livello di regolazione dell'esposizione. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer)() | Aggiunge il livello di regolazione tonalità/saturazione. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer)() | Aggiunge un livello di regolazione dell'inversione. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer)(Layer) | Aggiunge il livello. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup)(string, int, bool) | Aggiunge il gruppo di livelli. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer)() | Aggiunge il livello di regolazione Livelli. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer)(Color) | Aggiunge il livello PhotoFilter. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer)() | Aggiunge un nuovo livello regolare. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer)(string, Rectangle) | Aggiunge un nuovo livello di testo. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer)() | Aggiunge il livello di regolazione Vividezza. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness)(int) | Regolazione di una luminosità per l'immagine. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast)(float) | Immagine in contrasto |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma_1)(float, float, float) | Correzione gamma di un'immagine. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley)(double) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley_1)(double, int) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu)() | Binarizzazione di un'immagine con soglia Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata)() | Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert)(PsdOptions) | Converte questo formato immagine in quello specificato nelle opzioni. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop#crop)(Rectangle) | Ritaglio dell'immagine. |
| virtual [Crop](../../aspose.psd/rasterimage/crop)(int, int, int, int) | Ritaglia immagine con spostamenti. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.psd/rasterimage/dither)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage)() | Appiattisce tutti i livelli. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | Ottiene un'immagine ARGB pixel a 32 bit. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array di pixel predefinito utilizzando il caricatore di pixel parziale. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ottiene l'array di dati grezzi predefinito. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array di dati grezzi predefinito utilizzando il caricatore di pixel parziale. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine della risorsa. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.psd/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.psd/image/save)metodo come secondo parametro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | Ottiene un pixel dell'immagine. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | Carica pixel ARGB a 32 bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | Carica pixel ARGB a 64 bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | Carica i pixel in formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Carica i pixel ARGB a 32 bit parzialmente per pacchetti. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Carica i pixel parzialmente per pacchetti. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | Carica pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers)(Layer, Layer) | Unisce i livelli. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)() | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle) e[`Rotate`](../../aspose.psd/rasterimage/rotate) metodi. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)(bool, Color) | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle) e[`Rotate`](../../aspose.psd/rasterimage/rotate) metodi. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(Color, byte, Color) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor#replacecolor_1)(int, byte, int) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| [Resize](../../aspose.psd/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate_1)(float, bool, Color) | Ruota l'immagine attorno al centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.psd/image/save)() | Salva i dati dell'immagine nel flusso sottostante. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Salva i dati dell'oggetto nella posizione del file specificata. |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.psd/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | Salva i pixel ARGB a 32 bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Salva i pixel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | Salva i pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Salva i dati grezzi. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | Imposta un pixel ARGB a 32 bit dell'immagine per la posizione specificata. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | Imposta un pixel dell'immagine per la posizione specificata. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | Imposta la risoluzione per questo[`RasterImage`](../../aspose.psd/rasterimage) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | Converte l'immagine raster in bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion) | La versione PSD predefinita. |

### Esempi

Il codice seguente mostra la capacità di ruotare l'immagine in base a un valore di angolo specifico.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Immagine intera ruotata
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Strato rotante
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Guarda anche

* class [RasterCachedImage](../../aspose.psd/rastercachedimage)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
