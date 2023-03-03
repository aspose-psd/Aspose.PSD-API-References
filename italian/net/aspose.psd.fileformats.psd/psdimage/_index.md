---
title: Class PsdImage
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.PsdImage classe. Definisce la classe PsdImage che offre la possibilità di caricare modificare salvare file PSD nonché aggiornare le proprietà aggiungere filigrane eseguire operazioni grafiche o convertire un formato di file in un altro. Aspose.PSD supporta limportazione come livello e lesportazione in seguenti formati Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb insieme allesportazione in Pdf con testo selezionabile
type: docs
weight: 3590
url: /it/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Definisce la classe PsdImage che offre la possibilità di caricare, modificare, salvare file PSD nonché aggiornare le proprietà, aggiungere filigrane, eseguire operazioni grafiche o convertire un formato di file in un altro. Aspose.PSD supporta l'importazione come livello e l'esportazione in seguenti formati: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb insieme all'esportazione in Pdf con testo selezionabile

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Inizializza una nuova istanza di`PsdImage`classe dall'immagine raster esistente (non immagine psd) con modalità colore RGB con 4 canali 8 bit/canale e nessuna compressione. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Inizializza una nuova istanza di`PsdImage` class dal percorso specificato dall'immagine raster (non l'immagine psd nel flusso). Utilizzato per inizializzare l'immagine psd con parametri predefiniti - Modalità colore - rgb, 4 canali, 8 bit per canale, Compressione - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Inizializza una nuova istanza di`PsdImage` class dal percorso specificato dall'immagine raster (non l'immagine psd nel percorso). Utilizzato per inizializzare l'immagine psd con parametri predefiniti - Modalità colore - rgb, 4 canali, 8 bit per canale, Compressione - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Inizializza una nuova istanza di`PsdImage` classe con larghezza e altezza specificate. Utilizzato per inizializzare un'immagine psd vuota. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Inizializza una nuova istanza di`PsdImage` class dall'immagine raster esistente (non immagine psd) con i parametri del costruttore. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Inizializza una nuova istanza di`PsdImage` class dal percorso specificato dall'immagine raster (non l'immagine psd nel flusso) con i parametri del costruttore. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Inizializza una nuova istanza di`PsdImage` class dal percorso specificato dall'immagine raster (non l'immagine psd nel percorso) con i parametri del costruttore. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Inizializza una nuova istanza di`PsdImage` classe con larghezza, altezza, tavolozza, modalità colore, numero di canali e lunghezza di bit dei canali specificati e parametri della modalità di compressione specificati. Utilizzato per inizializzare un'immagine psd vuota. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Ottiene o imposta il layer attivo. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Ottiene o imposta un valore che indica se la regolazione automatica della tavolozza. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Ottiene i bit per canale. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Ottiene i bit dell'immagine per numero di pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Ottiene o imposta l'hint della dimensione del buffer che è definita dimensione massima consentita per tutti i buffer interni. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Ottiene il conteggio dei canali PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Ottiene o imposta il profilo colore CMYK per le immagini PSD CMYK. Deve essere abbinato a RgbColorProfile per una corretta conversione del colore. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Ottiene o imposta la modalità colore. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Ottiene il metodo di compressione. |
| [Container](../../aspose.psd/image/container/) { get; } | Ottiene il[`Image`](../../aspose.psd/image/) contenitore. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Ottiene un valore di file format |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Ottiene o imposta l'angolo globale. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Ottiene le informazioni sulla maschera di livello globale. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Ottiene o imposta le risorse del livello globale. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Ottiene o imposta il profilo colore GRAY (monocromatico) per le immagini PSD in scala di grigi. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di this[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Ottiene o imposta un valore che indica se il primo canale alfa contiene i dati di trasparenza per il risultato unito quando si specificano i dati dei layer. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Ottiene l'altezza dell'immagine. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di this`PsdImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Ottiene l'opacità di questa immagine. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Ottiene o imposta le risorse dell'immagine PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Ottiene o imposta il monitor di interrupt. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Ottiene un valore che indica se l'immagine psd è appiattita. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Ottiene un valore che indica se è disponibile il caricamento dei dati non elaborati. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Ottiene o imposta i livelli PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Ottiene il gestore dei layer collegati. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Ottiene o imposta il convertitore di colore personalizzato |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Ottiene il formato dei dati grezzi. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Ottiene le impostazioni dei dati non elaborati correnti. Nota quando si utilizzano queste impostazioni i dati vengono caricati senza conversione. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori limite |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Ottiene o imposta il convertitore di colore indicizzato |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Ottiene la dimensione della riga non elaborata in byte. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Ottiene o imposta il profilo colore RGB per le immagini PSD CMYK. Deve essere abbinato a CmykColorProfile per una corretta conversione del colore. |
| [Size](../../aspose.psd/image/size/) { get; } | Ottiene la dimensione dell'immagine. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Ottiene il fornitore di oggetti intelligenti. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Ottiene il colore trasparente dell'immagine. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati non elaborati quando è disponibile il caricamento dei dati non elaborati. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Ottiene o imposta la versione. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di this`PsdImage` . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Ottiene la larghezza dell'immagine. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Ottiene o imposta i metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Aggiunge il livello di regolazione bianco nero. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Aggiunge il livello di regolazione della luminosità/contrasto. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Aggiunge il livello di regolazione del mixer del canale con parametri predefiniti |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Aggiunge il livello di regolazione del bilanciamento del colore. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Aggiunge il livello di regolazione delle curve. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Aggiunge il livello di regolazione dell'esposizione. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Aggiunge il livello di regolazione tonalità/saturazione. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Aggiunge un livello di regolazione invertito. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Aggiunge il livello. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Aggiunge il gruppo di livelli. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Aggiunge il livello di regolazione Livelli. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Aggiunge il livello PhotoFilter. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Aggiunge un nuovo livello normale. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Aggiunge un nuovo livello di testo. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Aggiunge il livello di regolazione Vividezza. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Regola la luminosità dell'immagine. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Contrasto immagine |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Correzione gamma di un'immagine. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattiva di Bradley utilizzando la soglia integrale dell'immagine |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattiva di Bradley utilizzando la soglia integrale dell'immagine |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarizzazione di un'immagine con Otsu thresholding |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Memorizza i dati nella cache e garantisce che non venga eseguito alcun caricamento di dati aggiuntivi dal sottostante[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato di file specificato rappresentato dalle opzioni di salvataggio passate. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Converte questo formato immagine in quello specificato nelle opzioni. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Ritaglio dell'immagine. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Ritaglia l'immagine con spostamenti. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Appiattisce tutti i livelli. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Ottiene un pixel ARGB a 32 bit dell'immagine. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array di pixel predefinito utilizzando il caricatore parziale di pixel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Ottiene l'array di dati non elaborati predefinito. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array di dati non elaborati predefinito utilizzando il caricamento parziale dei pixel. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine della risorsa. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e poi salvalo usando the [`Save`](../../aspose.psd/datastreamsupporter/save/) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.psd/image/save/)metodo come secondo parametro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Ottiene un pixel dell'immagine. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Carica pixel ARGB a 32 bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Carica pixel ARGB a 64 bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Carica pixel in formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Carica i pixel ARGB a 32 bit parzialmente per pacchetti. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Carica i pixel parzialmente per pacchetti. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Carica i pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica i dati grezzi. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica i dati grezzi. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Unisce i livelli. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) E[`Rotate`](../../aspose.psd/rasterimage/rotate/) metodi. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) E[`Rotate`](../../aspose.psd/rasterimage/rotate/) metodi. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ridimensiona proporzionalmente l'altezza. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ridimensiona proporzionalmente la larghezza. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Ruota l'immagine attorno al centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.psd/image/save/)() | Salva i dati dell'immagine nel flusso sottostante. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Salva i dati dell'oggetto nella posizione file specificata. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato di file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Salva i dati dell'oggetto nella posizione file specificata. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato di file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato in base alle opzioni di salvataggio. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Salva i pixel ARGB a 32 bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Salva i pixel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Salva i pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Salva i dati grezzi. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Imposta un pixel ARGB a 32 bit dell'immagine per la posizione specificata. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Imposta un pixel dell'immagine per la posizione specificata. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Imposta la risoluzione per questo[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Converte l'immagine raster in bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | La versione PSD predefinita. |

### Esempi

Il codice seguente dimostra la possibilità di ruotare l'immagine in base a un valore di angolo specifico.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotazione dell'intera immagine
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

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assemblea [Aspose.PSD](../../)


