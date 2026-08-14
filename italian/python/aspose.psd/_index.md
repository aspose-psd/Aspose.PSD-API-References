---
title: "aspose.psd"
type: docs
weight: 10
url: /it/python-net/aspose.psd/
---


Il modulo è il nucleo per i moduli nidificati e gli oggetti più basilari utilizzati per l'elaborazione di Aspose.PSD.

## **Classes**
| **Classe** | **Description** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | Definisce un modello di fusione. Questa classe non può essere ereditata. |
| [Brush](/psd/python-net/aspose.psd/brush/) | La classe base del pennello. |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | Contiene le informazioni sulla versione corrente della build. |
| [Cache](/psd/python-net/aspose.psd/cache/) | Contiene le impostazioni della cache. |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | Il colore CMYK del pixel. |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | Metodi di supporto per lavorare con il colore CMYK presentato come valore intero a 32 bit con segno.<br/>            Fornisce un'API simile a quella della struct [CmykColor](/psd/python-net/aspose.psd/cmykcolor/).<br/>            È più leggero perché il colore CMYK è presentato semplicemente come Int32 anziché come una struttura con campi interni.<br/>            Si consiglia di utilizzare i metodi statici di questa classe quando possibile invece della struct deprecata<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |
| [Color](/psd/python-net/aspose.psd/color/) | Il colore del pixel. |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | Definisce array di colori e posizioni usati per l'interpolazione della fusione dei colori in un gradiente multicolore. Questa classe non può essere ereditata. |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | Definisce una mappa per la conversione dei colori. Diversi metodi della classe [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) regolano i colori dell'immagine utilizzando una tabella di rimappatura dei colori, che è un array di strutture [ColorMap](/psd/python-net/aspose.psd/colormap/). Non ereditabile. |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | Definisce una matrice 5 x 5 che contiene le coordinate per lo spazio RGBA. Diversi metodi della classe [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) regolano i colori dell'immagine utilizzando una matrice dei colori. Questa classe non può essere ereditata. |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | Definisce un array di colori che compongono una tavolozza di colori. I colori sono ARGB a 32 bit. Non ereditabile. |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | Classe di supporto per la manipolazione delle tavolozze di colori. |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | Traduce i colori da e verso le strutture GDI+ Color. Questa classe non può essere ereditata. |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | Incapsula un'estremità di linea personalizzata definita dall'utente. |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | Il contenitore del flusso di dati. |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | Rappresenta un oggetto eliminabile. |
| [Figure](/psd/python-net/aspose.psd/figure/) | La figura. Un contenitore per forme. |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | Supporto per l'elaborazione di flussi di file. |
| [Font](/psd/python-net/aspose.psd/font/) | Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile. Questa classe non può essere ereditata. |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | Impostazioni del carattere del renderer per i formati vettoriali PSD generali. |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | Rappresenta la grafica secondo il motore grafico utilizzato nell'assembly corrente. |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | Rappresenta una serie di linee e curve collegate. Questa classe non può essere ereditata. |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | Il processore avanzato di buffer. |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | Il processore di buffer. |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | Il convertitore di colore. |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | L'interfaccia della tavolozza di colori. |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | Il creatore di immagini. |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | Il descrittore del creatore di immagine che specifica le proprietà del creatore. Il descrittore del creatore è usato per superare<br/>            la necessità di contenere ogni istanza del creatore di immagine in memoria e i problemi di multithreading. |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | Il descrittore di immagine. Contiene le proprietà di base e i metodi per tutti gli altri tipi di descrittore di immagine. |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | L'esportatore di immagini. Può esportare dati dal formato interno Aspose.PSD a un formato di dati specificato. |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | Rappresenta il descrittore dell'esportatore di immagini. Il descrittore dell'esportatore è usato per superare la necessità di contenere ogni istanza dell'esportatore<br/>            in memoria e i problemi di multithreading. |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | Il caricatore di immagini. |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | Il descrittore del caricatore di immagini che specifica le proprietà del caricatore. Il descrittore del caricatore è usato per superare<br/>            la necessità di contenere ogni istanza del caricatore di immagini in memoria e i problemi di multithreading. |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | Il convertitore di colore per formati di immagine indicizzati. |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | Rappresenta l'interfaccia per oggetti con chiavi. |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | Rappresenta un oggetto con limiti. |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | Rappresenta una forma ordinata. Una forma ordinata è un insieme continuo di punti con un punto di inizio e un punto di fine.<br/>            L'insieme continuo di punti collegati usando una regola specifica. |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | Conforma ai pixel ARGB a 32 bit caricati parzialmente. |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | Il caricatore di pixel ARGB a 64 bit. |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | Conforma ai pixel caricati parzialmente. |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | Il caricatore di dati parziali. |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | La tavolozza dei colori pasd |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | Il caricatore di pixel ARGB a 32 bit per immagini raster. |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | Il caricatore di pixel per immagini raster. |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | Il caricatore di dati grezzi per immagini raster. |
| [Image](/psd/python-net/aspose.psd/image/) | L'immagine è la classe base per tutti i tipi di immagini. |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | Un oggetto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) contiene informazioni su come i colori bitmap e metafile vengono manipolati durante il rendering. Un oggetto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) mantiene diverse impostazioni di correzione del colore, incluse matrici di correzione del colore, matrici di correzione in scala di grigi, valori di correzione gamma, tabelle di mappatura dei colori e valori di soglia del colore. Durante il rendering, i colori possono essere corretti, scuriti, schiariti e rimossi. Per applicare tali manipolazioni, inizializza un oggetto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) e passa il percorso di quell'oggetto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) (insieme al percorso di un oggetto [Image](/psd/python-net/aspose.psd/image/)) al metodo DrawImage. |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | Rappresenta il registro dei creatori di immagini. |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | Rappresenta il registro degli esportatori di immagini. |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | Rappresenta il registro dei caricatori di immagini. |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | Le opzioni base dell'immagine. |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | Classe delle impostazioni di ridimensionamento dell'immagine |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | Classe per rappresentare una sequenza di elementi |
| [License](/psd/python-net/aspose.psd/license/) | Fornisce metodi per licenziare il componente. |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | Rappresenta le opzioni di caricamento. |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | Sostituisce la matrice GDI+. |
| [Metered](/psd/python-net/aspose.psd/metered/) | Fornisce metodi per impostare la chiave misurata. |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | Rappresenta un dizionario non generico. |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | Elenco non generico di oggetti |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | L'oggetto con i limiti. |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | Cache per i font OpenType installati nel sistema. |
| [Pen](/psd/python-net/aspose.psd/pen/) | Definisce un oggetto usato per disegnare linee, curve e figure. |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | Il formato dei dati pixel. Questo è un oggetto immutabile. |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | La classe per memorizzare i dati dei pixel dell'immagine e i suoi limiti. |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | Eccezione per licenza del plugin |
| [Point](/psd/python-net/aspose.psd/point/) | Rappresenta una coppia ordinata di coordinate intere x e y che definisce un punto in un piano bidimensionale. |
| [PointF](/psd/python-net/aspose.psd/pointf/) | Rappresenta una coppia ordinata di coordinate in virgola mobile x e y che definisce un punto in un piano bidimensionale. |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | Rappresenta un'immagine raster che supporta operazioni grafiche raster. Questa immagine memorizza nella cache i dati pixel quando necessario. |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | Rappresenta un'immagine raster che supporta operazioni grafiche raster. |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | Le impostazioni dei dati grezzi |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo. |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | Memorizza un insieme di quattro numeri in virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo. |
| [Region](/psd/python-net/aspose.psd/region/) | Descrive l'interno di una forma grafica composta da rettangoli e percorsi. Questa classe non può essere ereditata. |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | L'impostazione della risoluzione per le opzioni di salvataggio dell'immagine. |
| [Shape](/psd/python-net/aspose.psd/shape/) | La forma. Un insieme continuo di punti collegati mediante una regola specifica. |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | Rappresenta un segmento di forma. Un segmento è una linea o curva che collega due punti. |
| [Size](/psd/python-net/aspose.psd/size/) | Rappresenta la dimensione. |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | Memorizza una coppia ordinata di numeri a virgola mobile, tipicamente la larghezza e l'altezza di un rettangolo. |
| [Source](/psd/python-net/aspose.psd/source/) | La sorgente è usata per contenere tutte le informazioni rilevanti per una pipe di oggetti. |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | Rappresenta un contenitore di flusso diviso che contiene il flusso e fornisce routine di elaborazione del flusso. |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | Rappresenta un contenitore di flusso che contiene il flusso e fornisce routine di elaborazione del flusso. |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | Incapsula informazioni di layout del testo (come allineamento, orientamento e tabulazioni), manipolazioni di visualizzazione (come inserimento di ellissi e sostituzione di cifre nazionali) e funzionalità OpenType. Questa classe non può essere ereditata. |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | L'oggetto che supporta la trasparenza. |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | L'immagine vettoriale è la classe base per tutti i tipi di immagini vettoriali. |
## **Enumerations**
| **Enumerazione** | **Description** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | Specifica il tipo di cache da utilizzare. |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | Rappresenta il set di caratteri utilizzato. |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | Specifica quali oggetti usano le informazioni di regolazione del colore. |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | Specifica i canali individuali nello spazio colore CMYK (ciano, magenta, giallo, nero). Questa enumerazione è usata dai metodi SetOutputChannel. |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | Metodo di confronto del colore per regolare al vicino più prossimo |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | Specifica i tipi di immagini e colori che saranno influenzati dalle impostazioni di regolazione del colore e della scala di grigi di un [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | Metodi di quantizzazione dei colori |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | Specifica il livello di qualità da utilizzare durante il compositing. |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | Specifica il tipo di forma grafica da usare su entrambe le estremità di ogni trattino in una linea tratteggiata. |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | Specifica lo stile delle linee tratteggiate disegnate con un oggetto [Pen](/psd/python-net/aspose.psd/pen/). |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | La modalità di recupero dati. |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | Metodo di dithering. |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | I metodi di dithering usati per controllare la conversione del colore. |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | Uno dei formati di file PSD supportati. |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | Specifica come viene riempito l'interno di un percorso chiuso. |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | Specifica le informazioni di stile applicate al testo. |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | Specifica l'unità di misura per i dati forniti. |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | Specifica i diversi pattern disponibili per gli oggetti [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/). |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | Specifica il tipo di visualizzazione per i prefissi dei tasti di scelta rapida relativi al testo. |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | Filtri immagine da utilizzare |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | L'enumerazione [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) specifica l'algoritmo utilizzato quando le immagini vengono scalate o ruotate. |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | Specifica i colori di sistema noti. |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | Specifica gli stili di estremità disponibili con cui un oggetto [Pen](/psd/python-net/aspose.psd/pen/) può terminare una linea. |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | Specifica come unire segmenti consecutivi di linee o curve in una figura (sottotraccia) contenuta in un oggetto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | Specifica l'ordine per le operazioni di trasformazione della matrice. |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | Specifica il livello di conformità PDF per il file di output. |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | Specifica l'allineamento di un oggetto [Pen](/psd/python-net/aspose.psd/pen/) rispetto alla linea teorica a larghezza zero. |
| [PenType](/psd/python-net/aspose.psd/pentype/) | Specifica il tipo di riempimento che un oggetto [Pen](/psd/python-net/aspose.psd/pen/) utilizza per riempire le linee. |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | Il significato reale del formato dei dati pixel. |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | Specifica il tipo di ridimensionamento. |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | Enumerazione dell'unità di risoluzione. |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | Specifica di quanto un'immagine è ruotata e l'asse utilizzato per capovolgere l'immagine. |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | Fornisce i campi che rappresentano i punti di riferimento in [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) per la ricerca. |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | Specifica se l'anti-aliasing (smussatura) è applicato a linee e curve e ai bordi delle aree riempite. |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | Specifica l'allineamento di una stringa di testo rispetto al suo rettangolo di layout. |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | L'enumerazione specifica come sostituire le cifre in una stringa in base alla locale o alla lingua dell'utente. |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | Specifica le informazioni di visualizzazione e layout per le stringhe di testo. |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | Specifica come tagliare i caratteri da una stringa che non si adatta completamente a una forma di layout. |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | Specifica la qualità del rendering del testo. |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | Specifica il tipo di trasformazione di deformazione applicata. |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | Specifica come una texture o un gradiente viene ripetuto quando è più piccolo dell'area da riempire. |
