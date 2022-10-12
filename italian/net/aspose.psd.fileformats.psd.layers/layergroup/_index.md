---
title: LayerGroup
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Classe livello gruppo
type: docs
weight: 2200
url: /it/net/aspose.psd.fileformats.psd.layers/layergroup/
---
## LayerGroup class

Classe livello gruppo

```csharp
public class LayerGroup : Layer
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions) { get; } | Ottiene le opzioni di fusione. |
| override [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layergroup/blendmodekey) { get; set; } | Ottiene o imposta la chiave della modalità di fusione. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature) { get; } | Ottiene la firma della modalità di fusione. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom) { get; set; } | Ottiene o imposta la posizione del livello inferiore. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation) { get; set; } | Ottiene o imposta le informazioni sul canale. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount) { get; } | Ottiene il conteggio dei canali del livello. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping) { get; set; } | Ottiene o imposta il ritaglio del livello. 0 = base, 1 = non base. |
| [Container](../../aspose.psd/image/container) { get; } | Ottiene il[`Image`](../../aspose.psd/image) contenitore. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname) { get; set; } | Ottiene o imposta il nome visualizzato del livello. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength) { get; } | Ottiene la lunghezza delle informazioni extra del livello in byte. |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | Ottiene un valore di formato file |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler) { get; set; } | Ottiene o imposta il riempimento del livello. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity) { get; set; } | Ottiene o imposta l'opacità del riempimento. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags) { get; set; } | Ottiene o imposta i flag di livello. bit 0 = trasparenza protetta; bit 1 = visibile; bit 2 = obsoleto; bit 3 = 1 per Photoshop 5.0 e versioni successive, indica se il bit 4 ha informazioni utili; bit 4 = dati pixel irrilevanti per l'aspetto del documento. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha) { get; } | Ottiene un valore che indica se questa istanza ha alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layergroup/height) { get; } | Ottiene l'altezza del gruppo di livelli. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo[`RasterImage`](../../aspose.psd/rasterimage) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | Ottiene l'opacità di questa immagine. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsOpen](../../aspose.psd.fileformats.psd.layers/layergroup/isopen) { get; set; } | Ottiene o imposta la cartella aperta se impostata su`VERO` che il gruppo sarà in stato aperto all'avvio, altrimenti in stato ridotto a icona. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | Ottiene un valore che indica se è disponibile il caricamento dei dati grezzi. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible) { get; set; } | Ottiene o imposta un valore che indica se il livello è visibile |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup) { get; } | Ottiene un valore che indica se questa istanza è visibile nel gruppo (se il livello non è nel gruppo significa gruppo radice). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata) { get; set; } | Ottiene o imposta i dati degli intervalli di fusione dei livelli. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime) { get; set; } | Ottiene o imposta la data e l'ora di creazione del livello. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock) { get; set; } | Ottiene o imposta il blocco del livello. Si noti che se è impostato il flag LayerFlags.TransparencyProtected, verrà sovrascritto dal flag del blocco del livello. Per restituire il flag LayerFlags.TransparencyProtected è necessario applicare l'opzione del livello layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata) { get; set; } | Ottiene o imposta i dati della maschera di livello. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions) { get; } | Ottiene le opzioni del livello. |
| [Layers](../../aspose.psd.fileformats.psd.layers/layergroup/layers) { get; } | Ottiene i livelli nel gruppo di livelli |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left) { get; set; } | Ottiene o imposta la posizione del livello sinistro. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length) { get; } | Ottiene la lunghezza complessiva del livello in byte. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name) { get; set; } | Ottiene o imposta il nome del livello. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity) { get; set; } | Ottiene o imposta l'opacità del livello. 0 = trasparente, 255 = opaco. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore personalizzato |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat) { get; } | Ottiene il formato dei dati grezzi. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | Ottiene le impostazioni dei dati grezzi correnti. Nota quando si utilizzano queste impostazioni i dati vengono caricati senza conversione. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore indicizzato |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | Ottiene la dimensione della riga grezza in byte. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources) { get; set; } | Ottiene o imposta le risorse del livello. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right) { get; set; } | Ottiene o imposta la posizione del livello corretta. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight) { get; set; } | Ottiene o imposta l'evidenziazione del colore del foglio decorativo nell'elenco dei livelli |
| [Size](../../aspose.psd/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top) { get; set; } | Ottiene o imposta la posizione del livello superiore. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | Ottiene il colore trasparente dell'immagine. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando è disponibile il caricamento dei dati grezzi. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution) { get; set; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo[`RasterImage`](../../aspose.psd/rasterimage) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layergroup/width) { get; } | Ottiene la larghezza del gruppo di livelli. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata) { get; set; } | Ottiene o imposta i metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.psd.layers/layergroup/addlayer)(Layer) | Aggiunge il livello al gruppo di livelli. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd.layers/layergroup/addlayergroup)(string, int) | Aggiunge il gruppo di livelli. |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask)(LayerMaskData) | Aggiunge la maschera al livello corrente. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness)(int) | Regolazione di una luminosità per l'immagine. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast)(float) | Immagine in contrasto |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma)(float, float, float) | Correzione gamma di un'immagine. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley)(double) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley)(double, int) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu)() | Binarizzazione di un'immagine con soglia Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata)() | Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| override [Crop](../../aspose.psd/rastercachedimage/crop)(Rectangle) | Ritaglio dell'immagine. |
| virtual [Crop](../../aspose.psd/rasterimage/crop)(int, int, int, int) | Ritaglia immagine con spostamenti. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.psd/rasterimage/dither)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.psd/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage)(Point, RasterImage) | Disegna l'immagine sul livello. |
| virtual [Filter](../../aspose.psd/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | Ottiene un'immagine ARGB pixel a 32 bit. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array di pixel predefinito utilizzando il caricatore di pixel parziale. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ottiene l'array di dati grezzi predefinito. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array di dati grezzi predefinito utilizzando il caricatore di pixel parziale. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode)() | Restituisce un codice hash per questa istanza. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine della risorsa. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.psd/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.psd/image/save)metodo come secondo parametro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | Ottiene un pixel dell'immagine. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | Carica pixel ARGB a 32 bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | Carica pixel ARGB a 64 bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | Carica i pixel in formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Carica i pixel ARGB a 32 bit parzialmente per pacchetti. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Carica i pixel parzialmente per pacchetti. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | Carica pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto)(Layer) | Unisce il livello al livello specificato |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)() | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle) e[`Rotate`](../../aspose.psd/rasterimage/rotate) metodi. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)(bool, Color) | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle) e[`Rotate`](../../aspose.psd/rasterimage/rotate) metodi. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(Color, byte, Color) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(int, byte, int) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| [Resize](../../aspose.psd/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate)(float, bool, Color) | Ruota l'immagine attorno al centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.psd/image/save)() | Salva i dati dell'immagine nel flusso sottostante. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Salva i dati dell'oggetto nella posizione del file specificata. |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, ImageOptionsBase) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | Salva i pixel ARGB a 32 bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Salva i pixel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | Salva i pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Salva i dati grezzi. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | Imposta un pixel ARGB a 32 bit dell'immagine per la posizione specificata. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | Imposta un pixel dell'immagine per la posizione specificata. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | Imposta la risoluzione per questo[`RasterImage`](../../aspose.psd/rasterimage) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy)() | Crea una copia superficiale del livello corrente. Per favore[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) per la spiegazione. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | Converte l'immagine raster in bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |

### Esempi

L'esempio seguente mostra come modificare la visibilità LayerGroup in Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// apportare modifiche ai nomi dei livelli e salvarlo
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Disattiva tutto all'interno di un gruppo
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Guarda anche

* class [Layer](../layer)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
