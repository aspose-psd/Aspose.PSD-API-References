---
title: Class SmartObjectLayer
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer classe. Definisce la classe SmartObjectLayer che contiene loggetto incorporato nel file PSD o collegato nel file esterno. Con gli oggetti avanzati puoi Eseguire trasformazioni non distruttive. Puoi ridimensionare ruotare inclinare distorcere trasformare la prospettiva o deformare un livello senza perdere i dati o la qualità dellimmagine originale perché le trasformazioni non influiscono sui dati originali. Lavora con dati vettoriali come la grafica vettoriale di Illustrator che altrimenti verrebbe rasterizzato. Esegui filtraggio non distruttivo. Puoi modificare i filtri applicati agli oggetti avanzati in qualsiasi momento. Modifica un oggetto avanzato e aggiorna automaticamente tutte le sue istanze collegate. Applica una maschera di livello collegata o non collegata al livello delloggetto avanzato. Prova vari design con basso immagini segnaposto di risoluzione che in seguito sostituirai con le versioni finali. In Adobe Photoshop puoi incorporare il contenuto di unimmagine in un documento PSD. Ulteriori informazioni sono disponibili quihttps//helpx.adobe.com/photoshop/using/createsmartobjects.html Un livello con un oggetto avanzato incorporato contiene risorse posizionate PlLd e SoLd con proprietà delloggetto avanzato. La risorsa PlLd può essere isolata per le versioni PSD precedenti alla 10. Queste risorse contengono lUniqueId di LiFdDataSource nella Lnk2Resource globale con loggetto avanzato incorporato filename e altri parametri incluso il contenuto del file incorporato nel formato originale come array di byte.
type: docs
weight: 3490
url: /it/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
## SmartObjectLayer class

Definisce la classe SmartObjectLayer che contiene l'oggetto incorporato nel file PSD o collegato nel file esterno. Con gli oggetti avanzati, puoi: Eseguire trasformazioni non distruttive. Puoi ridimensionare, ruotare, inclinare, distorcere, trasformare la prospettiva o deformare un livello senza perdere i dati o la qualità dell'immagine originale perché le trasformazioni non influiscono sui dati originali. Lavora con dati vettoriali, come la grafica vettoriale di Illustrator, che altrimenti verrebbe rasterizzato. Esegui filtraggio non distruttivo. Puoi modificare i filtri applicati agli oggetti avanzati in qualsiasi momento. Modifica un oggetto avanzato e aggiorna automaticamente tutte le sue istanze collegate. Applica una maschera di livello collegata o non collegata al livello dell'oggetto avanzato. Prova vari design con basso- immagini segnaposto di risoluzione che in seguito sostituirai con le versioni finali. In Adobe� Photoshop�, puoi incorporare il contenuto di un'immagine in un documento PSD. Ulteriori informazioni sono disponibili qui:[https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) Un livello con un oggetto avanzato incorporato contiene risorse posizionate (PlLd) e SoLd con proprietà dell'oggetto avanzato. La risorsa PlLd può essere isolata per le versioni PSD precedenti alla 10. Queste risorse contengono l'UniqueId di LiFdDataSource nella Lnk2Resource globale con l'oggetto avanzato incorporato filename e altri parametri, incluso il contenuto del file incorporato nel formato originale come array di byte.

```csharp
public class SmartObjectLayer : Layer
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Ottiene o imposta un valore che indica se la regolazione automatica della tavolozza. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Ottiene i bit dell'immagine per numero di pixel. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Ottiene le opzioni di fusione. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Ottiene o imposta la chiave della modalità di fusione. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Ottiene la firma della modalità di fusione. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Ottiene o imposta la posizione del livello inferiore. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Ottiene o imposta l'hint della dimensione del buffer che è definita dimensione massima consentita per tutti i buffer interni. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Ottiene o imposta le informazioni sul canale. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Ottiene il conteggio dei canali del livello. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Ottiene o imposta il ritaglio del livello. 0 = base, 1 = non base. |
| [Container](../../aspose.psd/image/container/) { get; } | Ottiene il[`Image`](../../aspose.psd/image/) contenitore. |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | Ottiene o imposta i contenuti del livello dell'oggetto avanzato. Il contenuto dell'oggetto avanzato incorporato è il file di immagine raw incorporato:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) e le sue proprietà. Il contenuto dell'oggetto intelligente collegato è il contenuto non elaborato del file immagine collegato se disponibile e le sue proprietà:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Non supportiamo il caricamento dalla libreria grafica di Adobe� Photoshop� �� quando[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) è vero. Per i normali file di collegamento, all'inizio, usiamo[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) per cercare il file relativamente nel percorso dell'immagine di origineSourceImagePath , se non è disponibile guardiamo[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , in caso contrario, cerchiamo il file di collegamento nella stessa directory in cui si trova la nostra immagine:SourceImagePath . |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | Ottiene o imposta i limiti del contenuto dell'oggetto avanzato. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | Ottiene o imposta l'origine del contenuto dell'oggetto avanzato. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | Ottiene il tipo di contenuto del livello dell'oggetto avanzato. Il contenuto dell'oggetto avanzato incorporato è il file di immagine raw incorporato:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) . Il contenuto dell'oggetto intelligente collegato è il contenuto non elaborato del file immagine collegato, se disponibile:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Non supportiamo il caricamento dalla libreria grafica di Adobe� Photoshop� �� quando[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) è vero. Per i normali file di collegamento, all'inizio, usiamo[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) per cercare il file relativamente nel percorso dell'immagine di origineSourceImagePath , se non è disponibile guardiamo[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , in caso contrario, cerchiamo il file di collegamento nella stessa directory in cui si trova la nostra immagine:SourceImagePath . |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Ottiene o imposta il nome visualizzato del layer. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Ottiene la lunghezza in byte delle informazioni extra sul layer. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Ottiene un valore di file format |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Ottiene o imposta il riempimento del livello. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Ottiene o imposta l'opacità del riempimento. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Ottiene o imposta i flag del livello. bit 0 = trasparenza protetta; bit 1 = visibile; bit 2 = obsoleto; bit 3 = 1 per Photoshop 5.0 e versioni successive, indica se il bit 4 contiene informazioni utili; bit 4 = dati pixel irrilevanti per l'aspetto del documento. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Ottiene un valore che indica se questa istanza ha alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Ottiene l'altezza dell'immagine. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di this[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Ottiene l'opacità di questa immagine. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Ottiene o imposta il monitor di interrupt. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Ottiene un valore che indica se è disponibile il caricamento dei dati non elaborati. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Ottiene o imposta un valore che indica se il livello è visibile |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Ottiene un valore che indica se questa istanza è visibile nel gruppo (se il layer non è nel gruppo significa gruppo radice). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Ottiene o imposta i dati degli intervalli di fusione dei livelli. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Ottiene o imposta la data e l'ora di creazione del layer. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Ottiene o imposta il blocco del livello. Si noti che se il flag LayerFlags.TransparencyProtected è impostato, verrà sovrascritto dal flag di blocco del livello. Per restituire il flag LayerFlags.TransparencyProtected è necessario applicare l'opzione layer layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Ottiene o imposta i dati della maschera di livello. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Ottiene le opzioni del livello. |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Ottiene o imposta la posizione del livello sinistro. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Ottiene la lunghezza complessiva del livello in byte. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Ottiene o imposta il nome del livello. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Ottiene o imposta l'opacità del livello. 0 = trasparente, 255 = opaco. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Ottiene o imposta il convertitore di colore personalizzato |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Ottiene il formato dei dati grezzi. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Ottiene le impostazioni dei dati non elaborati correnti. Nota quando si utilizzano queste impostazioni i dati vengono caricati senza conversione. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori limite |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Ottiene o imposta il convertitore di colore indicizzato |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Ottiene la dimensione della riga non elaborata in byte. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Ottiene o imposta le risorse del livello. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Ottiene o imposta la giusta posizione del livello. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Ottiene o imposta l'evidenziazione del colore del foglio decorativo nell'elenco dei layer |
| [Size](../../aspose.psd/image/size/) { get; } | Ottiene la dimensione dell'immagine. |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | Ottiene i filtri intelligenti. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | Ottiene il fornitore di oggetti intelligenti. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Ottiene o imposta la posizione del livello superiore. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Ottiene il colore trasparente dell'immagine. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati non elaborati quando è disponibile il caricamento dei dati non elaborati. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di this[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Ottiene la larghezza dell'immagine. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Ottiene o imposta i metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Aggiunge la maschera al livello corrente. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Regola la luminosità dell'immagine. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Contrasto immagine |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Correzione gamma di un'immagine. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattiva di Bradley utilizzando la soglia integrale dell'immagine |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattiva di Bradley utilizzando la soglia integrale dell'immagine |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarizzazione di un'immagine con Otsu thresholding |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Memorizza i dati nella cache e garantisce che non venga eseguito alcun caricamento di dati aggiuntivi dal sottostante[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato di file specificato rappresentato dalle opzioni di salvataggio passate. |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | Converte questo oggetto smart incorporato in un oggetto smart collegato. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Ritaglio dell'immagine. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Ritaglia l'immagine con spostamenti. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Disegna l'immagine sul livello. |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | Crea un nuovo livello oggetto avanzato copiando questo. Nota che per gli oggetti avanzati incorporati l'immagine incorporata è condivisa. Se vuoi copiare l'immagine incorporata usa[`NewSmartObjectViaCopy`](./newsmartobjectviacopy/) metodo. |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | Incorpora l'oggetto intelligente collegato in questo livello. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | Esporta i contenuti incorporati o collegati in un file. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Ottiene un pixel ARGB a 32 bit dell'immagine. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array di pixel predefinito utilizzando il caricatore parziale di pixel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Ottiene l'array di dati non elaborati predefinito. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array di dati non elaborati predefinito utilizzando il caricamento parziale dei pixel. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Restituisce un codice hash per questa istanza. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine della risorsa. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e poi salvalo usando the [`Save`](../../aspose.psd/datastreamsupporter/save/) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.psd/image/save/)metodo come secondo parametro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Ottiene un pixel dell'immagine. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Carica pixel ARGB a 32 bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Carica pixel ARGB a 64 bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Carica pixel in formato CMYK. |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | Ottiene il contenuto dell'immagine incorporata o collegata del livello degli oggetti avanzati. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Carica i pixel ARGB a 32 bit parzialmente per pacchetti. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Carica i pixel parzialmente per pacchetti. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Carica i pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica i dati grezzi. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica i dati grezzi. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Unisce il livello al livello specificato |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | Crea un nuovo livello oggetto avanzato copiando questo. Riproduce `Livello -&gt; Oggetti avanzati -&gt; Nuovo oggetto avanzato tramite la funzionalità Copia` di Adobe� Photoshop�. Si noti che è abilitato solo per gli oggetti avanzati incorporati perché l'immagine incorporata viene anche copiato. Se si desidera condividere l'immagine incorporata, utilizzare[`DuplicateLayer`](./duplicatelayer/) metodo. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) E[`Rotate`](../../aspose.psd/rasterimage/rotate/) metodi. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) E[`Rotate`](../../aspose.psd/rasterimage/rotate/) metodi. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | Ricollega l'oggetto smart collegato a un nuovo file. Non è necessario chiamare successivamente il metodo UpdateModifiedContent. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | Sostituisce i contenuti degli oggetti intelligenti incorporati nel livello degli oggetti intelligenti. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | Sostituisce il contenuto con un file. Non è necessario chiamare successivamente il metodo UpdateModifiedContent. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | Sostituisce i contenuti degli oggetti intelligenti incorporati nel livello degli oggetti intelligenti. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | Sostituisce il contenuto con un file. Non è necessario chiamare successivamente il metodo UpdateModifiedContent. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Ruota l'immagine attorno al centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.psd/image/save/)() | Salva i dati dell'immagine nel flusso sottostante. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Salva i dati dell'oggetto nella posizione file specificata. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato di file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Salva i dati dell'oggetto nella posizione file specificata. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato di file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato in base alle opzioni di salvataggio. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Salva i pixel ARGB a 32 bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Salva i pixel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Salva i pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Salva i dati grezzi. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Imposta un pixel ARGB a 32 bit dell'immagine per la posizione specificata. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Imposta un pixel dell'immagine per la posizione specificata. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Imposta la risoluzione per questo[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Crea una copia superficiale del livello corrente. Per favore[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) per spiegazioni. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Converte l'immagine raster in bitmap. |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | Aggiorna la cache dell'immagine del livello degli oggetti intelligenti con il contenuto modificato. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |

### Esempi

Il codice seguente illustra il supporto degli oggetti Embedded Smart.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Questo esempio mostra come modificare il livello degli oggetti avanzati nel file PSD ed esportare/aggiornare i contenuti incorporati originali degli oggetti avanzati.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Esportiamo l'immagine dell'oggetto avanzato incorporato dal livello dell'oggetto avanzato PSD
        smartObjectLayer.ExportContents(exportPath);

        // Controlliamo se l'immagine originale è stata salvata correttamente
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Invertiamo l'immagine dell'oggetto intelligente originale
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Sostituiamo l'immagine dell'oggetto smart incorporata nel livello PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Controlliamo se l'immagine aggiornata è stata salvata correttamente
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Guarda anche

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assemblea [Aspose.PSD](../../)


