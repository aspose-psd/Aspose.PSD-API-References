---
title: "Classe GradientMapLayer"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.GradientMapLayer. Livello mappa gradiente. Gestisce il rendering della mappa gradiente utilizzando i dati da GrdmResource"
type: docs
weight: 1810
url: /it/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/
---
{{< psd/tize >}}
## GradientMapLayer class

Livello mappa gradiente. Gestisce il rendering della mappa gradiente utilizzando i dati da GrdmResource.

```csharp
public class GradientMapLayer : AdjustmentLayer
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Ottiene il conteggio dei bit per pixel dell'immagine. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | Ottiene o imposta la fusione dell'elemento ritagliato. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Ottiene le opzioni di fusione. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Ottiene o imposta la chiave della modalità di fusione. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Ottiene la firma della modalità di fusione. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Ottiene o imposta la posizione del livello inferiore. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Ottiene o imposta il suggerimento della dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Ottiene o imposta le informazioni del canale. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Ottiene il conteggio dei canali del livello. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Ottiene o imposta il ritaglio del livello. 0 = base, 1 = non-base. |
| [Container](../../aspose.psd/image/container/) { get; } | Ottiene il contenitore [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Ottiene o imposta il nome visualizzato del livello. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Ottiene la lunghezza delle informazioni aggiuntive del livello in byte. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Ottiene un valore del formato file |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Ottiene o imposta il riempitore del livello. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Ottiene o imposta l'opacità del riempimento. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Ottiene o imposta i flag del livello. bit 0 = trasparenza protetta; bit 1 = visibile; bit 2 = obsoleto; bit 3 = 1 per Photoshop 5.0 e versioni successive, indica se il bit 4 contiene informazioni utili; bit 4 = dati pixel irrilevanti per l'aspetto del documento. |
| [GradientSettings](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/gradientsettings/) { get; set; } | Ottiene o imposta l'istanza delle impostazioni Gradient passata dall'istanza GrdmResource. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Ottiene un valore che indica se questa istanza ha alfa. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Ottiene l'altezza dell'immagine. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Ottiene l'opacità di questa immagine. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Restituisce un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Restituisce un valore che indica se il caricamento dei dati grezzi è disponibile. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Ottiene o imposta un valore che indica se il livello è visibile |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Restituisce un valore che indica se questa istanza è visibile nel gruppo (se il livello non è in un gruppo significa gruppo radice). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Ottiene o imposta i dati degli intervalli di fusione del livello. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Ottiene o imposta la data e l'ora di creazione del livello. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Ottiene o imposta il blocco del livello. Nota che se il flag LayerFlags.TransparencyProtected è impostato verrà sovrascritto dal flag di blocco del livello. Per restituire il flag LayerFlags.TransparencyProtected è necessario applicarlo all'opzione del livello layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Ottiene o imposta i dati della maschera del livello. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Restituisce le opzioni del livello. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Ottiene o imposta la posizione sinistra del livello. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Restituisce la lunghezza complessiva del livello in byte. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Ottiene o imposta il nome del livello. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Ottiene o imposta l'opacità del livello. 0 = trasparente, 255 = opaco. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Ottiene o imposta il convertitore di colore personalizzato |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Restituisce il formato dei dati grezzi. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Restituisce le impostazioni attuali dei dati grezzi. Nota che quando si usano queste impostazioni i dati vengono caricati senza conversione. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Ottiene o imposta il convertitore di colore indicizzato |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Restituisce la dimensione della riga grezza in byte. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Ottiene o imposta le risorse del livello. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Ottiene o imposta la posizione destra del livello. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Ottiene o imposta l'evidenziazione del colore del foglio decorativo nell'elenco dei livelli. |
| [Size](../../aspose.psd/image/size/) { get; } | Ottiene le dimensioni dell'immagine. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Ottiene o imposta la posizione del livello superiore. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Ottiene il colore trasparente dell'immagine. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Ottiene un valore che indica se la palette dell'immagine è utilizzata. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ottiene o imposta un valore che indica se utilizzare il caricamento di dati grezzi quando è disponibile. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo [`RasterImage`](../../aspose.psd/rasterimage/). |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Ottiene la larghezza dell'immagine. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Ottiene o imposta i metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Aggiunge la maschera al livello corrente. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Regola la luminosità dell'immagine. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Contrasto dell'immagine |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Correzione gamma di un'immagine. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | Applica la maschera di livello al livello, quindi elimina la maschera. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con sogliatura dell'immagine integrale |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con sogliatura dell'immagine integrale |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarizzazione di un'immagine con sogliatura di Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Memorizza nella cache i dati e garantisce che non vengano effettuati ulteriori caricamenti di dati dal [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) sottostante. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio fornite. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Ritaglio dell'immagine. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Ritaglia l'immagine con spostamenti. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Disegna l'immagine sul livello. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Ottiene un pixel immagine a 32-bit ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Ottiene l'array predefinito di pixel ARGB a 32-bit. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array predefinito di pixel usando il caricatore di pixel parziali. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Ottiene l'array predefinito di dati grezzi. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array predefinito di dati grezzi usando il caricatore di pixel parziali. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Restituisce un codice hash per questa istanza. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine di risorsa. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ottiene le opzioni basate sulle impostazioni del file originale. Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il metodo [`Save`](../../aspose.psd/datastreamsupporter/save/), verrà generata un'immagine PNG di output a 8 bit per pixel. Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al metodo [`Save`](../../aspose.psd/image/save/) come secondo parametro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Ottiene un pixel immagine. Avviso sulle prestazioni: evita di utilizzare questo metodo per iterare su tutti i pixel dell'immagine poiché può causare notevoli problemi di prestazioni. Per una manipolazione dei pixel più efficiente, utilizza il metodo `LoadArgb32Pixels` per recuperare l'intero array di pixel simultaneamente. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Carica pixel ARGB a 32-bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Carica pixel ARGB a 64-bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Carica pixel in formato CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Carica pixel in formato CMYK. Questo metodo è deprecato. Si prega di utilizzare in modo più efficace il metodo [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Carica parzialmente pixel ARGB a 32-bit per pacchetti. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Carica pixel parzialmente per pacchetti. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Carica pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | Unisce il livello al livello specificato |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza i metodi [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) e [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza i metodi [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) e [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Legge l'intera riga di scansione tramite l'indice di riga di scansione specificato. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Legge l'intera riga di scansione tramite l'indice di riga di scansione specificato. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi morbidi. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi morbidi. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi morbidi. Nota: se lo usi su immagini senza trasparenza, tutti i colori saranno sostituiti con uno solo. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi morbidi. Nota: se lo usi su immagini senza trasparenza, tutti i colori saranno sostituiti con uno solo. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ridimensiona l'immagine. Viene utilizzato il NearestNeighbourResample predefinito. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ridimensiona l'altezza proporzionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ridimensiona l'altezza proporzionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ridimensiona l'altezza proporzionalmente. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ridimensiona la larghezza proporzionalmente. Viene utilizzato il NearestNeighbourResample predefinito. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ridimensiona la larghezza proporzionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ridimensiona la larghezza proporzionalmente. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Ruota l'immagine attorno al centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.psd/image/save/)() | Salva i dati dell'immagine nello stream sottostante. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Salva i dati dell'oggetto nello stream specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Salva i dati dell'oggetto nella posizione file specificata. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Salva i dati dell'oggetto nella posizione file specificata. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato secondo le opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato secondo le opzioni di salvataggio. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Salva i pixel ARGB a 32 bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Salva i pixel. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Salva i pixel. Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Salva i pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Salva i dati grezzi. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Imposta un pixel ARGB a 32 bit dell'immagine per la posizione specificata. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Imposta un pixel dell'immagine per la posizione specificata. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Imposta la risoluzione per questo [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Crea una copia superficiale del Layer corrente. Si prega di [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) per spiegazione. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Converte l'immagine raster in bitmap. |
| [Update](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/update/)() | Aggiorna i dati del livello nella risorsa del livello correlata [`GrdmResource`](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/). |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |

## Esempi

Il codice seguente dimostra il supporto del livello mappa gradiente.

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Aggiungi un livello di regolazione mappa gradiente.
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// Verifica le modifiche salvate
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    var gradientSettings = gradientMapLayer.GradientSettings;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;

    AssertAreEqual((short)4096, solidGradient.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual("Custom", solidGradient.GradientName);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Vedi anche

* class [AdjustmentLayer](../adjustmentlayer/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)


