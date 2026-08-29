---
title: "ThresholdLayer"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Livello di regolazione Soglia."
type: docs
weight: 29
url: /it/java/com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer), [com.aspose.psd.fileformats.psd.layers.adjustmentlayers.AdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer)
```
public class ThresholdLayer extends AdjustmentLayer
```

Livello di regolazione Soglia.
## Campi

| Campo | Descrizione |
| --- | --- |
| [BlendSignature](#BlendSignature) | Rappresenta la firma della modalità di fusione. |
| [LayerHeaderSize](#LayerHeaderSize) | La dimensione dell'intestazione del livello. |
| [OnCreate_internalized](#OnCreate-internalized) | Si verifica quando l'immagine è stata caricata |
| [OnLoad_internalized](#OnLoad-internalized) | Si verifica quando l'immagine è stata caricata da createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Si verifica quando l'immagine è stata caricata o salvata |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Si verifica quando il credito è stato utilizzato |
| [resources_internalized](#resources-internalized) | Le risorse |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Ottiene la risorsa associata al tipo specificato. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Aggiunge la maschera al livello corrente. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Aggiunge la risorsa. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Regola la luminosità dell'immagine. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contrasto dell'immagine |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correzione gamma di un'immagine. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correzione gamma di un'immagine. |
| [applyLayerMask()](#applyLayerMask--) | Applica la maschera del livello al livello, quindi elimina la maschera. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Applica l'impostazione dello stile del livello dall'input [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) al [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) corrente. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Avvia il processo di ridimensionamento. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con sogliatura basata sull'immagine integrale. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con sogliatura basata sull'immagine integrale. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarizzazione di un'immagine con soglia predefinita. |
| [binarizeOtsu()](#binarizeOtsu--) | Binarizzazione di un'immagine con sogliatura di Otsu. |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati e garantisce che non vengano caricati dati aggiuntivi dal sottostante DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Determina se l'immagine può essere caricata dallo stream specificato. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Determina se l'immagine può essere caricata dallo stream specificato e, facoltativamente, usando le loadOptions specificate. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Determina se l'immagine può essere caricata dal percorso file specificato. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Determina se l'immagine può essere caricata dal percorso file specificato e, facoltativamente, usando le opzioni di apertura specificate. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio fornite. |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Converte in aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Crea una nuova immagine usando le opzioni di creazione specificate. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Crea una nuova immagine usando le immagini specificate come pagine. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Crea una nuova immagine con le immagini specificate come pagine. |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | Crea la nuova istanza della classe [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createLayerState_internalized()](#createLayerState-internalized--) | Crea la nuova istanza di [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) basata sui valori correnti di [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader psdHeader, LayerResource[] resources)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Ritaglio dell'immagine. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Ritaglia l'immagine con spostamenti. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Esegue il dithering sull'immagine corrente. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Esegue il dithering sull'immagine corrente. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Ritaglio dell'immagine. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Ridimensiona l'immagine. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Disegna l'immagine sul livello. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'Object specificato è uguale a questa istanza. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtra il rettangolo specificato. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Trova la risorsa assegnabile. |
| [findPattResource_internalized()](#findPattResource-internalized--) | Trova il PattResource |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Trova la risorsa per chiave unica. |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Ottiene o imposta i limiti assoluti. |
| [getAdjustmentLayerType_internalized()](#getAdjustmentLayerType-internalized--) | Ottiene il tipo del livello di regolazione. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Ottiene un pixel immagine ARGB a 32 bit. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Ottiene un valore che indica se la palette di regolazione automatica è abilitata. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene o imposta un valore per il colore di sfondo. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ottiene il conteggio dei bit per pixel dell'immagine. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Ottiene o imposta la fusione dell'elemento ritagliato. |
| [getBlendModeKey()](#getBlendModeKey--) | Ottiene o imposta la chiave della modalità di fusione. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Ottiene la firma della modalità di fusione. |
| [getBlendingOptions()](#getBlendingOptions--) | Ottiene le opzioni di fusione. |
| [getBottom()](#getBottom--) | Ottiene o imposta la posizione del livello inferiore. |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'immagine. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene il suggerimento sulla dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Restituisce i byte per riga per la modalità maschera completa. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Restituisce i byte per riga. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Restituisce i byte per riga. |
| [getChannelInformation()](#getChannelInformation--) | Ottiene o imposta le informazioni del canale. |
| [getChannelsCount()](#getChannelsCount--) | Restituisce il conteggio dei canali del livello. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Ottiene o imposta il ritaglio del livello. |
| [getContainer()](#getContainer--) | Restituisce il contenitore Image. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Restituisce lo stream di dati dell'oggetto. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Restituisce la tavolozza di regolazione profonda. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Restituisce l'array di pixel ARGB a 32 bit predefinito. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Restituisce le opzioni predefinite. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Restituisce l'array di pixel predefinito usando il caricatore di pixel parziali. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Restituisce l'array di dati grezzi predefinito usando il caricatore di pixel parziali. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Restituisce l'array di dati grezzi predefinito. |
| [getDisplayName()](#getDisplayName--) | Restituisce il nome visualizzato del livello. |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getExtraLength()](#getExtraLength--) | Restituisce la lunghezza delle informazioni extra del livello in byte. |
| [getFileFormat()](#getFileFormat--) | Restituisce un valore del formato file |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Restituisce il formato file. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Restituisce il formato file. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Restituisce il formato file. |
| [getFillOpacity()](#getFillOpacity--) | Ottiene o imposta l'opacità del riempimento. |
| [getFiller()](#getFiller--) | Ottiene o imposta il riempitore del livello. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Restituisce il rettangolo che si adatta all'immagine corrente. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Restituisce il rettangolo che si adatta all'immagine corrente. |
| [getFlags()](#getFlags--) | Ottiene o imposta i flag del livello. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Ottiene l'elenco della gerarchia delle cartelle [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) del livello corrente. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Ottiene la palette da posizioni specifiche del formato |
| [getGUID_internalized()](#getGUID-internalized--) | Ottiene l'identificatore univoco di questa istanza di Layer. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getHeight()](#getHeight--) | Ottiene l'altezza dell'immagine. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo RasterImage. |
| [getImageOpacity()](#getImageOpacity--) | Ottiene l'opacità di questa immagine. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Ottiene il trasformatore interno dei dati. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Ottiene il monitor di interruzione. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Ottiene o imposta i dati degli intervalli di fusione del livello. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Ottiene o imposta la data e ora di creazione del livello. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Ottiene o imposta il blocco del livello. |
| [getLayerMaskData()](#getLayerMaskData--) | Ottiene o imposta i dati della maschera del livello. |
| [getLayerOptions()](#getLayerOptions--) | Ottiene le opzioni del livello. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Ottiene o imposta la palette del livello. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Ottiene il tipo del livello. |
| [getLeft()](#getLeft--) | Ottiene o imposta la posizione sinistra del livello. |
| [getLength()](#getLength--) | Ottiene la lunghezza complessiva del livello in byte. |
| [getLevel()](#getLevel--) | Ottiene e imposta il livello di soglia. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Ottiene o imposta l'allocazione massima consentita per il salvataggio di rotazione parziale. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Ottiene il gestore della memoria. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Ottiene la data e l'ora in cui l'immagine di risorsa è stata modificata l'ultima volta. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Ottiene o imposta il nome del livello. |
| [getOpacity()](#getOpacity--) | Ottiene o imposta l'opacità del livello. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Ottiene l'opacità totale. |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni basate sulle impostazioni del file originale. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Ottiene l'immagine dipingibile. |
| [getPalette()](#getPalette--) | Ottiene la tavolozza dei colori. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Ottiene un pixel dell'immagine. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Crea la cache privata dei caratteri. |
| [getProcessor_internalized()](#getProcessor-internalized--) | Ottiene il processore. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene le informazioni del gestore dell'evento di avanzamento. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Ottiene le informazioni del gestore dell'evento di avanzamento. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Ottiene un'altezza proporzionale. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Ottiene una larghezza proporzionale. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Ottiene o imposta il convertitore di colore personalizzato |
| [getRawDataFormat()](#getRawDataFormat--) | Ottiene il formato dei dati grezzi. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Ottiene o imposta il convertitore di colore indicizzato |
| [getRawLineSize()](#getRawLineSize--) | Ottiene la dimensione grezza della riga in byte. |
| [getResources()](#getResources--) | Ottiene o imposta le risorse del livello. |
| [getRight()](#getRight--) | Ottiene o imposta la posizione destra del livello. |
| [getRotateMode()](#getRotateMode--) | Ottiene o imposta la modalità di rotazione. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Ottiene o imposta l'evidenziazione del colore del foglio decorativo nell'elenco dei livelli |
| [getSize()](#getSize--) | Ottiene le dimensioni dell'immagine. |
| [getSkewAngle()](#getSkewAngle--) | Ottiene l'angolo di inclinazione. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Ottiene il percorso file dell'immagine sorgente se esiste. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Ottiene la radice di sincronizzazione. |
| [getTop()](#getTop--) | Ottiene o imposta la posizione superiore del livello. |
| [getTransparentColor()](#getTransparentColor--) | Ottiene il colore trasparente dell'immagine. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Ottiene un valore che indica se l'oggetto utilizza una strategia di ottimizzazione della memoria |
| [getUseRawData()](#getUseRawData--) | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando il caricamento dei dati grezzi è disponibile. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Ottiene la tavolozza utilizzata. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Ottiene la licenza venture. |
| [getVerticalResolution()](#getVerticalResolution--) | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo RasterImage. |
| [getWidth()](#getWidth--) | Ottiene la larghezza dell'immagine. |
| [getXmpData()](#getXmpData--) | Ottiene o imposta i metadati XMP. |
| [grayscale()](#grayscale--) | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [hasAlpha()](#hasAlpha--) | Ottiene un valore che indica se questa istanza ha alfa. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Ottiene un valore che indica se l'immagine ha un colore di sfondo. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Ottiene o imposta un valore che indica se questa istanza dell'immagine è cambiata dopo il caricamento. |
| [hasTransparentColor()](#hasTransparentColor--) | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Ottiene o imposta il valore massimo di avanzamento |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indica il progresso. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Inserisci una risorsa nella collezione Resources. |
| [isCached()](#isCached--) | Ottiene un valore che indica se i dati dell'immagine sono attualmente nella cache. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | Rileva se il livello è valido per il salvataggio su un file. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Ottiene un valore che indica se il caricamento dei dati grezzi è disponibile. |
| [isUsePalette()](#isUsePalette--) | Ottiene un valore che indica se la tavolozza dell'immagine è utilizzata. |
| [isVisible()](#isVisible--) | Ottiene o imposta un valore che indica se il livello è visibile |
| [isVisibleInGroup()](#isVisibleInGroup--) | Ottiene un valore che indica se questa istanza è visibile nel gruppo (se il livello non è in un gruppo significa gruppo radice). |
| [load(InputStream stream)](#load-java.io.InputStream-) | Carica una nuova immagine dallo stream specificato. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Carica una nuova immagine dallo stream specificato. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Carica una nuova immagine dallo stream specificato. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Carica una nuova immagine dallo stream specificato. |
| [load(String filePath)](#load-java.lang.String-) | Carica una nuova immagine dal file specificato. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Carica una nuova immagine dal file specificato. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Carica pixel ARGB a 32 bit. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Carica pixel ARGB a 64 bit. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Carica pixel in formato CMYK. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Carica pixel in formato CMYK. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Carica parzialmente pixel ARGB a 32 bit per pacchetti. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Carica pixel parzialmente per pacchetti. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Carica pixel. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Carica i dati dell'immagine grezzi utilizzando il meccanismo di elaborazione parziale. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Carica dati grezzi. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Carica una nuova immagine dallo stream specificato. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Carica una nuova immagine dallo stream specificato. |
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Unisce il livello al livello specificato |
| [normalizeAngle()](#normalizeAngle--) | Normalizza l'angolo. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normalizza l'angolo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoca quando il contenitore di questa  Image  è stato impostato. |
| [processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Elabora lo strato di soglia. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Legge l'intera riga di scansione tramite l'indice di riga di scansione specificato. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Legge l'intera riga di scansione tramite l'indice di riga di scansione specificato. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Rimuove la risorsa. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Ridimensiona l'immagine. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Ridimensiona l'immagine. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona l'immagine. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Unisce i dati. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Ridimensiona l'altezza proporzionalmente. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ridimensiona l'altezza proporzionalmente. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ridimensiona l'altezza proporzionalmente. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Ridimensiona la larghezza proporzionalmente. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ridimensiona la larghezza proporzionalmente. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ridimensiona la larghezza proporzionalmente. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Ridimensiona il livello con la scala inversa specificata. |
| [rotate(float angle)](#rotate-float-) | Ruota l'immagine attorno al centro. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Ruota l'immagine attorno al centro. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Salva i dati dell'immagine nello stream sottostante. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Salva i dati dell'oggetto nello stream specificato. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Salva i dati dell'oggetto nello stream specificato. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato secondo le opzioni di salvataggio. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio. |
| [save(String filePath)](#save-java.lang.String-) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato secondo le opzioni di salvataggio. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato secondo le opzioni di salvataggio. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Salva i pixel ARGB a 32 bit. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Salva i pixel. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Salva i pixel. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Salva i pixel. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Salva i dati grezzi. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Salva i dati nel contenitore stream specificato. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Ottiene o imposta i limiti assoluti. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Imposta un pixel immagine 32-bit ARGB per la posizione specificata. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Imposta un valore che indica se la palette viene regolata automaticamente. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Ottiene o imposta un valore per il colore di sfondo. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Ottiene o imposta la fusione dell'elemento ritagliato. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Ottiene o imposta la chiave della modalità di fusione. |
| [setBottom(int value)](#setBottom-int-) | Ottiene o imposta la posizione del livello inferiore. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Ottiene o imposta le informazioni del canale. |
| [setClipping(byte value)](#setClipping-byte-) | Ottiene o imposta il ritaglio del livello. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Imposta il contenitore Image. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Imposta direttamente il caricatore dei dati. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Imposta lo stream dei dati dell'oggetto. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Ottiene o imposta il nome visualizzato del livello. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Ottiene l'opacità di riempimento. |
| [setFiller(byte value)](#setFiller-byte-) | Ottiene o imposta il riempitore del livello. |
| [setFlags(byte value)](#setFlags-byte-) | Ottiene o imposta i flag del livello. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Imposta la palette nei punti specifici del formato |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo RasterImage. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Imposta un valore che indica se [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Ottiene o imposta un valore che indica se questa istanza dell'immagine è cambiata dopo il caricamento. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Imposta il trasformatore interno dei dati. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Imposta il monitor di interruzione. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Ottiene o imposta i dati degli intervalli di fusione del livello. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Ottiene o imposta la data e ora di creazione del livello. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Ottiene o imposta il blocco del livello (Nota che se il flag LayerFlags.TransparencyProtected è impostato verrà sovrascritto dal flag di blocco del livello. |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Ottiene o imposta i dati della maschera del livello. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Ottiene o imposta la palette del livello. |
| [setLeft(int value)](#setLeft-int-) | Ottiene o imposta la posizione sinistra del livello. |
| [setLevel(short value)](#setLevel-short-) | Ottiene e imposta il livello di soglia. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Ottiene o imposta l'allocazione massima consentita per il salvataggio di rotazione parziale. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Imposta il gestore della memoria. |
| [setName(String name)](#setName-java.lang.String-) | Imposta il nome del livello. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Ottiene o imposta il nome del livello. |
| [setOpacity(byte value)](#setOpacity-byte-) | Ottiene o imposta l'opacità del livello. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Imposta la palette dei colori. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Imposta la palette dell'immagine. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Imposta un pixel immagine per la posizione specificata. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Ottiene o imposta il convertitore di colore personalizzato |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Ottiene o imposta il convertitore di colore indicizzato |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Imposta la risoluzione per questo RasterImage. |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Ottiene o imposta le risorse del livello. |
| [setRight(int value)](#setRight-int-) | Ottiene o imposta la posizione destra del livello. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Ottiene o imposta la modalità di rotazione. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Ottiene o imposta l'evidenziazione del colore del foglio decorativo nell'elenco dei livelli |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta la posizione superiore del livello. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Ottiene il colore trasparente dell'immagine. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando il caricamento dei dati grezzi è disponibile. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Tutti i prodotti Aspose dovrebbero implementare questo metodo. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo RasterImage. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta un valore che indica se il livello è visibile |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ottiene o imposta i metadati XMP. |
| [shallowCopy()](#shallowCopy--) | Crea una copia superficiale del Layer corrente. |
| [toBitmap()](#toBitmap--) | Converte l'immagine raster in bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Aggiorna le opzioni di fusione dopo la modifica del livello o delle risorse globali. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Scrive l'intera riga di scansione nell'indice di riga di scansione specificato. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Scrive l'intera riga di scansione nell'indice di riga di scansione specificato. |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Rappresenta la firma della modalità di fusione.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


La dimensione dell'intestazione del livello.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Si verifica quando l'immagine è stata caricata

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Si verifica quando l'immagine è stata caricata da createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Si verifica quando l'immagine è stata caricata o salvata

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Si verifica quando il credito è stato utilizzato

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


Le risorse

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Ottiene la risorsa associata al tipo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | risorsa | T[] | Al termine dell'esecuzione di questo metodo, contiene la risorsa associata al tipo di chiave specificato, se la chiave viene trovata; altrimenti, restituisce null. |

T : Il tipo di chiave del valore da ottenere. |

**Returns:**
boolean -   se contiene una risorsa con il tipo specificato; altrimenti,  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Aggiunge la maschera al livello corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Maschera del livello. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Aggiunge la risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | La risorsa. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Regola la luminosità dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| luminosità | int | Valore di luminosità. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Contrasto dell'immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrasto | float | Valore di contrasto (nell'intervallo [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Correzione gamma di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Correzione gamma di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Coefficiente gamma per il canale rosso |
| gammaGreen | float | Coefficiente gamma per il canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


Applica la maschera del livello al livello, quindi elimina la maschera.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Applica l'impostazione dello stile del livello dall'input [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) al [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | Lo stato del livello con il nuovo stile. |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Avvia il processo di ridimensionamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza dell'immagine. |
| newHeight | int | La nuova altezza dell'immagine. |

**Returns:**
com.aspose.internal.IResizeController - Il controller di ridimensionamento.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con sogliatura basata sull'immagine integrale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con sogliatura basata sull'immagine integrale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| windowSize | int | La dimensione della finestra s x s di pixel centrata su questo pixel |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarizzazione di un'immagine con soglia predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore di grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato a esso il valore 255, altrimenti 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarizzazione di un'immagine con sogliatura di Otsu.

### cacheData() {#cacheData--}
```
public void cacheData()
```


Memorizza nella cache i dati e garantisce che non vengano caricati dati aggiuntivi dal sottostante DataStreamSupporter.DataStreamContainer.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Determina se l'immagine può essere caricata dallo stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso da cui caricare. |

**Returns:**
boolean -  true  se l'immagine può essere caricata dal flusso specificato; altrimenti,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Determina se l'immagine può essere caricata dallo stream specificato e, facoltativamente, usando le loadOptions specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso da cui caricare. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns:**
boolean -  true  se l'immagine può essere caricata dal flusso specificato; altrimenti,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Determina se l'immagine può essere caricata dal percorso file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |

**Returns:**
boolean -  true  se l'immagine può essere caricata dal file specificato; altrimenti,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Determina se l'immagine può essere caricata dal percorso file specificato e, facoltativamente, usando le opzioni di apertura specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns:**
boolean -  true  se l'immagine può essere caricata dal file specificato; altrimenti,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio fornite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni di salvataggio da utilizzare. |

**Returns:**
boolean -  true  se l'immagine può essere salvata nel formato di file specificato rappresentato dalle opzioni di salvataggio passate; altrimenti,  false .
### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Converte in aps.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni. |
| mode | int | La modalità. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di ritaglio. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - La pagina APS.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Crea una nuova immagine usando le opzioni di creazione specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni immagine. |
| larghezza | int | La larghezza. |
| altezza | int | L'altezza. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Crea una nuova immagine usando le immagini specificate come pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Le immagini. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Crea una nuova immagine con le immagini specificate come pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Le immagini. |
| disposeImages | boolean | se impostato su  true  [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


Crea la nuova istanza della classe [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader | L'header. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | Il LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Crea la nuova istanza di [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) basata sui valori correnti di [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| larghezza | int |  |
| altezza | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(PsdHeader psdHeader, LayerResource[] resources) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public static ThresholdLayer create_internalized(PsdHeader psdHeader, LayerResource[] resources)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Ritaglio dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Ritaglia l'immagine con spostamenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | int | Lo spostamento a sinistra. |
| rightShift | int | Lo spostamento a destra. |
| topShift | int | Lo spostamento verso l'alto. |
| bottomShift | int | Lo spostamento verso il basso. |

### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'istanza corrente.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Esegue il dithering sull'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Esegue il dithering sull'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette personalizzata per il dithering. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Ritaglio dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Le impostazioni di ridimensionamento. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Ruota, capovolge o ruota e capovolge l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Il tipo di rotazione e capovolgimento. |

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Disegna l'immagine sul livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | La posizione. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'Object specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare con questa istanza. |

**Returns:**
boolean -  true  se l'oggetto specificato è uguale a questa istanza; altrimenti,  false .
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtra il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Le opzioni. |

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Trova la risorsa assegnabile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | Il tipo. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


Trova il PattResource

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Trova la risorsa per chiave unica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeToolKey | int | La chiave dello strumento tipo. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Ottiene o imposta i limiti assoluti.

Valore: i limiti assoluti.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getAdjustmentLayerType_internalized() {#getAdjustmentLayerType-internalized--}
```
public byte getAdjustmentLayerType_internalized()
```


Ottiene il tipo del livello di regolazione.

Valore: Il tipo del livello di regolazione.

**Returns:**
byte
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Ottiene un pixel immagine ARGB a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |

**Returns:**
int - Il pixel ARGB a 32 bit per la posizione specificata.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Ottiene un valore che indica se la palette di regolazione automatica è abilitata.

**Returns:**
boolean -  true  se abilita la regolazione automatica della palette; altrimenti,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ottiene o imposta un valore per il colore di sfondo.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ottiene il conteggio dei bit per pixel dell'immagine.

Valore: il conteggio dei bit per pixel dell'immagine.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Ottiene o imposta la fusione dell'elemento ritagliato.

Valore: la fusione dell'elemento ritagliato.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Ottiene o imposta la chiave della modalità di fusione.

Valore: la chiave della modalità di fusione.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Ottiene la firma della modalità di fusione.

Valore: la firma della modalità di fusione.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Ottiene le opzioni di fusione.

Valore: le opzioni di fusione.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


Ottiene o imposta la posizione del livello inferiore.

Valore: la posizione del livello inferiore.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene i limiti dell'immagine.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Ottiene il suggerimento sulla dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int - il suggerimento della dimensione del buffer che definisce la dimensione massima consentita per tutti i buffer interni.
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Restituisce i byte per riga per la modalità maschera completa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitDepth | int | La profondità di bit. |

**Returns:**
int - Byte necessari per memorizzare 1 riga
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Restituisce i byte per riga.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitDepth | int | La profondità di bit. |

**Returns:**
int - Byte necessari per memorizzare 1 riga
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Restituisce i byte per riga.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitDepth | int | La profondità di bit. |

**Returns:**
int - Byte necessari per memorizzare 1 riga
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Ottiene o imposta le informazioni del canale.

Valore: le informazioni del canale.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Restituisce il conteggio dei canali del livello.

Valore: il conteggio dei canali del livello.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


Ottiene o imposta il ritaglio del livello. 0 = base, 1 = non-base.

Valore: il ritaglio del livello.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Restituisce il contenitore Image.

Valore: Il contenitore Image.

Se questa proprietà non è null indica che l'immagine è contenuta all'interno di un'altra immagine.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Restituisce lo stream di dati dell'oggetto.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Restituisce la tavolozza di regolazione profonda.

**Returns:**
boolean - La palette di regolazione profonda.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Restituisce l'array di pixel ARGB a 32 bit predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo per cui ottenere i pixel. |

**Returns:**
int[] - L'array di pixel predefinito.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Restituisce le opzioni predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | java.lang.Object[] | Gli argomenti. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Restituisce l'array di pixel predefinito usando il caricatore di pixel parziali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo per cui ottenere i pixel. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Il caricatore parziale di pixel. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Restituisce l'array di dati grezzi predefinito usando il caricatore di pixel parziali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo per cui ottenere i pixel. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Il caricatore parziale di dati grezzi. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Le impostazioni dei dati grezzi. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Restituisce l'array di dati grezzi predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo per cui ottenere i dati grezzi. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Le impostazioni dei dati grezzi. |

**Returns:**
byte[] - L'array di dati grezzi predefinito.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Restituisce il nome visualizzato del livello.

Valore: Il nome visualizzato del livello.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Restituisce la lunghezza delle informazioni extra del livello in byte.

Valore: La lunghezza extra del livello.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Restituisce un valore del formato file

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Restituisce il formato file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Il flusso. |

--------------------

Il formato file determinato non significa che l'immagine specificata possa essere caricata. Utilizza una delle sovraccariche del metodo CanLoad per determinare se il flusso possa essere caricato. |

**Returns:**
long - Il formato file determinato.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Restituisce il formato file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Il flusso. |

Il formato file determinato non significa che l'immagine specificata possa essere caricata. Utilizza una delle sovraccariche del metodo CanLoad per determinare se il flusso possa essere caricato. |

**Returns:**
long - Il formato file determinato.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Restituisce il formato file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file. |

Il formato file determinato non significa che l'immagine specificata possa essere caricata. Utilizza una delle sovraccariche del metodo CanLoad per determinare se il file possa essere caricato. |

**Returns:**
long - Il formato file determinato.
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Ottiene o imposta l'opacità del riempimento.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Ottiene o imposta il riempitore del livello.

Valore: Il riempitore del livello.

**Returns:**
byte
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Restituisce il rettangolo che si adatta all'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo per cui ottenere un rettangolo di adattamento. |
| larghezza | int | La larghezza dell'oggetto. |
| altezza | int | L'altezza dell'oggetto. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Restituisce il rettangolo che si adatta all'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo per cui ottenere un rettangolo di adattamento. |
| pixel | int[] | I pixel ARGB a 32 bit. |
| larghezza | int | La larghezza dell'oggetto. |
| altezza | int | L'altezza dell'oggetto. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Ottiene o imposta i flag del livello. bit 0 = trasparenza protetta; bit 1 = visibile; bit 2 = obsoleto; bit 3 = 1 per Photoshop 5.0 e successive, indica se il bit 4 contiene informazioni utili; bit 4 = dati pixel irrilevanti per l'aspetto del documento.

Valore: I flag del livello.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Ottiene l'elenco della gerarchia delle cartelle [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) del livello corrente.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Restituisce l'elenco della gerarchia delle cartelle [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) del livello corrente.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Ottiene la palette da posizioni specifiche del formato

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Ottiene l'identificatore univoco di questa istanza di Layer.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ottiene o imposta l'intestazione.

Valore: L'intestazione.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene l'altezza dell'immagine.

Valore: L'altezza dell'immagine.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo RasterImage.

**Returns:**
double - La risoluzione orizzontale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Ottiene l'opacità di questa immagine.

**Returns:**
float - Il valore di opacità compreso tra 0.0 (completamente trasparente) e 1.0 (completamente opaco).
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Ottiene il trasformatore interno dei dati.

Valore: Il trasformatore interno dei dati.

**Returns:**
com.aspose.internal.IInnerDataTransformer - il trasformatore interno dei dati.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Ottiene il monitor di interruzione.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Ottiene o imposta i dati degli intervalli di fusione del livello.

Valore: I dati degli intervalli di fusione del livello.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Ottiene o imposta la data e ora di creazione del livello.

Valore: La data e ora di creazione del livello. Se non ci sono dati sulla DataOra di creazione, restituisce il primo epoch del tempo Unix.

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


Ottiene o imposta il blocco del livello. Nota che se il flag LayerFlags.TransparencyProtected è impostato verrà sovrascritto dal flag di blocco del livello. Per restituire il flag LayerFlags.TransparencyProtected è necessario applicare l'opzione del livello layer.Flags |= LayerFlags.TransparencyProtected.

Valore: Il blocco del livello.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Ottiene o imposta i dati della maschera del livello.

Valore: I dati della maschera del livello.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Ottiene le opzioni del livello.

Valore: Le opzioni del livello.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Ottiene o imposta la palette del livello.

Valore: La tavolozza del livello.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Ottiene il tipo del livello.

Valore: Il tipo del livello.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


Ottiene o imposta la posizione sinistra del livello.

Valore: La posizione sinistra del livello.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


Ottiene la lunghezza complessiva del livello in byte.

**Returns:**
long
### getLevel() {#getLevel--}
```
public final short getLevel()
```


Ottiene e imposta il livello di soglia.

Valore: Il livello.

**Returns:**
short
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Ottiene o imposta l'allocazione massima consentita per il salvataggio di rotazione parziale.

**Returns:**
int - La massima allocazione consentita per il salvataggio di rotazione parziale.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Ottiene il gestore della memoria.

Valore: Il gestore della memoria.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - il gestore della memoria.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Ottiene la data e l'ora in cui l'immagine di risorsa è stata modificata l'ultima volta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| useDefault | boolean | se impostato su  true  utilizza le informazioni da FileInfo come valore predefinito. |

**Returns:**
java.util.Date - La data e l'ora in cui l'immagine di risorsa è stata modificata l'ultima volta.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getName() {#getName--}
```
public final String getName()
```


Ottiene o imposta il nome del livello.

Valore: Il nome del livello.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Ottiene o imposta l'opacità del livello. 0 = trasparente, 255 = opaco.

Valore: L'opacità del livello.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Ottiene l'opacità totale. L'opacità totale è il prodotto dell'Opacità del Livello e dell'Opacità di Riempimento del Livello. Viene usata per la fusione dei livelli.

Valore: L'opacità totale.

**Returns:**
byte
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ottiene le opzioni basate sulle impostazioni del file originale. Questo può essere utile per mantenere inalterata la profondità di colore e altri parametri dell'immagine originale. Per esempio, se carichiamo un'immagine PNG in bianco‑nero con 1 bit per pixel e poi la salviamo usando il  DataStreamSupporter.Save(string)  metodo, verrà prodotta un'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, usa questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al  Image.Save(string, ImageOptionsBase)  metodo come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Ottiene l'immagine dipingibile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ottiene la tavolozza dei colori. La tavolozza dei colori non è usata quando i pixel sono rappresentati direttamente.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Ottiene un pixel dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati.

**Returns:**
boolean -  true  se i componenti dell'immagine devono essere premoltiplicati; altrimenti,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Crea la cache privata dei caratteri.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - La cache dei font privati.
### getProcessor_internalized() {#getProcessor-internalized--}
```
public final IPartialArgb32PixelLoader getProcessor_internalized()
```


Ottiene il processore.

Valore: il processore.

**Returns:**
[IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Ottiene le informazioni del gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Ottiene le informazioni del gestore dell'evento di avanzamento.

Valore: Le informazioni del gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Ottiene un'altezza proporzionale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza | int | La larghezza. |
| altezza | int | L'altezza. |
| newWidth | int | La nuova larghezza. |

**Returns:**
int - L'altezza proporzionale.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Ottiene una larghezza proporzionale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza | int | La larghezza. |
| altezza | int | L'altezza. |
| newHeight | int | La nuova altezza. |

**Returns:**
int - La larghezza proporzionale.
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Ottiene o imposta il convertitore di colore personalizzato

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Ottiene il formato dei dati grezzi.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Ottiene le impostazioni attuali dei dati grezzi. Nota che quando si usano queste impostazioni i dati vengono caricati senza conversione.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti

**Returns:**
int - L'indice di fallback da usare quando l'indice della tavolozza è fuori dai limiti
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Ottiene o imposta il convertitore di colore indicizzato

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Ottiene la dimensione grezza della riga in byte.

**Returns:**
int - La dimensione grezza della linea in byte.
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Ottiene o imposta le risorse del livello.

Valore: Le risorse del livello.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


Ottiene o imposta la posizione destra del livello.

Valore: La posizione del livello destro.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Ottiene o imposta la modalità di rotazione.

**Returns:**
int - La modalità di rotazione.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Ottiene o imposta l'evidenziazione del colore del foglio decorativo nell'elenco dei livelli

Valore: L'evidenziazione del colore del foglio.

**Returns:**
short
### getSize() {#getSize--}
```
public Size getSize()
```


Ottiene le dimensioni dell'immagine.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Restituisce l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione.

**Returns:**
float - L'angolo di inclinazione, in gradi.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Restituisce il percorso del file dell'immagine sorgente se esiste. Restituisce una stringa vuota se non è possibile trovare il percorso sorgente.

**Returns:**
java.lang.String - Il percorso del file dell'immagine sorgente.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Ottiene la radice di sincronizzazione.

Valore: La radice di sincronizzazione.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


Ottiene o imposta la posizione superiore del livello.

Valore: La posizione del livello superiore.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Ottiene il colore trasparente dell'immagine.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Ottiene o imposta un valore che indica se aggiornare i metadati XMP.

**Returns:**
boolean -  true  se aggiorna i metadati XMP; altrimenti,  false .
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Ottiene un valore che indica se l'oggetto utilizza una strategia di ottimizzazione della memoria

Valore:  true  se l'oggetto utilizza la strategia di ottimizzazione della memoria; altrimenti,  false .

**Returns:**
boolean - un valore che indica se l'oggetto utilizza la strategia di ottimizzazione della memoria
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando il caricamento dei dati grezzi è disponibile.

**Returns:**
boolean -  true  se utilizza il caricamento dei dati grezzi quando è disponibile; altrimenti,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Ottiene la tavolozza utilizzata.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Ottiene la licenza venture.

**Returns:**
java.lang.Object - La licenza venture come oggetto.
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo RasterImage.

**Returns:**
double - La risoluzione verticale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene la larghezza dell'immagine.

Valore: La larghezza dell'immagine.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ottiene o imposta i metadati XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Trasformazione di un'immagine nella sua rappresentazione in scala di grigi

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Ottiene un valore che indica se questa istanza ha alfa.

Valore:  true  se questa istanza ha alfa; altrimenti,  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Ottiene un valore che indica se l'immagine ha un colore di sfondo.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Ottiene o imposta un valore che indica se questa istanza dell'immagine è cambiata dopo il caricamento.

**Returns:**
boolean -  true  se questa istanza ha l'immagine modificata; altrimenti,  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Ottiene un valore che indica se l'immagine ha un colore trasparente.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Ottiene o imposta il valore massimo di avanzamento

Valore: Il valore massimo di progresso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Indica il progresso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


Inserisci una risorsa nella collezione Resources.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice della risorsa da inserire. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | La risorsa da inserire. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Ottiene un valore che indica se i dati dell'immagine sono attualmente nella cache.

**Returns:**
boolean -  true  se i dati dell'immagine sono memorizzati nella cache; altrimenti,  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


Rileva se il livello è valido per il salvataggio su un file.

**Returns:**
boolean -
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Ottiene un valore che indica se il caricamento dei dati grezzi è disponibile.

**Returns:**
boolean -  true  se questo caricamento dei dati grezzi è disponibile; altrimenti,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Ottiene un valore che indica se la tavolozza dell'immagine è utilizzata.

Valore:  true  se la tavolozza è usata nell'immagine; altrimenti,  false .

**Returns:**
boolean - un valore che indica se la tavolozza dell'immagine è usata.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Ottiene o imposta un valore che indica se il livello è visibile

Valore:  true  se questa istanza è visibile; altrimenti,  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Ottiene un valore che indica se questa istanza è visibile nel gruppo (se il livello non è in un gruppo significa gruppo radice).

Valore:  true  se questa istanza è visibile nel gruppo; altrimenti,  false .

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Carica una nuova immagine dallo stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso da cui caricare l'immagine. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Carica una nuova immagine dallo stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso da cui caricare l'immagine. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Carica una nuova immagine dallo stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Il file da cui caricare l'immagine. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Carica una nuova immagine dallo stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Il file da cui caricare l'immagine. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Carica una nuova immagine dal file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file da cui caricare l'immagine. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Carica una nuova immagine dal file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file da cui caricare l'immagine. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Carica pixel ARGB a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
int[] - L'array di pixel ARGB a 32 bit caricato.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Carica pixel ARGB a 64 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
long[] - L'array di pixel ARGB a 64 bit caricato.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Carica pixel in formato CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
int[] - L'array di pixel CMYK caricato presentato come valori interi a 32 bit.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Carica pixel in formato CMYK. Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace  loadCmyk32Pixels(Rectangle) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
com.aspose.psd.CmykColor[] - L'array di pixel CMYK caricato.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Carica parzialmente pixel ARGB a 32 bit per pacchetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo desiderato. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Il caricatore di pixel ARGB a 32 bit. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Carica pixel parzialmente per pacchetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo desiderato. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Il caricatore di pixel. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Carica pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
com.aspose.psd.Color[] - L'array di pixel caricato.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carica i dati dell'immagine grezzi utilizzando il meccanismo di elaborazione parziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | L'area rettangolare desiderata dell'immagine da cui caricare i dati. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Le impostazioni dei dati grezzi. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Il caricatore di dati grezzi. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carica dati grezzi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da cui caricare i dati grezzi. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dell'immagine di destinazione. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Le impostazioni dei dati grezzi da utilizzare per i dati caricati. Nota: se i dati non sono nel formato specificato, verrà eseguita la conversione dei dati. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Il caricatore di dati grezzi. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Carica una nuova immagine dallo stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Il flusso da cui caricare l'immagine. |
| startPosition | long | La posizione di partenza da cui caricare l'immagine. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Carica una nuova immagine dallo stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Il flusso da cui caricare l'immagine. |
| startPosition | long | La posizione di partenza da cui caricare l'immagine. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Unisce il livello al livello specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Il livello in cui unire. |

### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza [.getSkewAngle](../../null/\#getSkewAngle) e [.rotate(float)](../../null/\#rotate-float-) metodi.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza [.getSkewAngle](../../null/\#getSkewAngle) e [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) metodi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizeProportionally | boolean | se impostato su true la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Colore dello sfondo. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Invoca quando il contenitore di questa  Image  è stato impostato.

### processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public Tuple<int[],Rectangle> processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Elabora lo strato di soglia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei pixel. |
| pixel | int[] | L'array di pixel. |
| start | [Point](../../com.aspose.psd/point) | La posizione in alto a sinistra dei pixel. |
| end | [Point](../../com.aspose.psd/point) | La posizione in basso a destra dei pixel. |

**Returns:**
com.aspose.internal.fileformats.psd.common.Tuple<int[],com.aspose.psd.Rectangle> - Il rettangolo dei pixel e i pixel elaborati.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Legge l'intera riga di scansione tramite l'indice di riga di scansione specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scanLineIndex | int | Indice basato su zero della linea di scansione. |

**Returns:**
int[] - L'array dei valori di colore ARGB a 32 bit della linea di scansione.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Legge l'intera riga di scansione tramite l'indice di riga di scansione specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scanLineIndex | int | Indice basato su zero della linea di scansione. |

**Returns:**
com.aspose.psd.Color[] - L'array dei valori di colore dei pixel della linea di scansione.
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Rimuove la risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | La risorsa. |

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Colore vecchio da sostituire. |
| oldColorDiff | byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| newColor | [Color](../../com.aspose.psd/color) | Nuovo colore con cui sostituire il colore vecchio. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldColorArgb | int | Valore ARGB del colore vecchio da sostituire. |
| oldColorDiff | byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| newColorArgb | int | Valore ARGB del nuovo colore con cui sostituire il colore vecchio. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Sostituisce tutti i colori non trasparenti con il nuovo colore e preserva il valore alfa originale per mantenere bordi morbidi. Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Nuovo colore con cui sostituire i colori non trasparenti. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Sostituisce tutti i colori non trasparenti con il nuovo colore e preserva il valore alfa originale per mantenere bordi morbidi. Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorArgb | int | Valore ARGB del nuovo colore con cui sostituire i colori non trasparenti. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Ridimensiona l'immagine. Viene utilizzato il valore predefinito ResizeType.LeftTopToLeftTop.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Le impostazioni di ridimensionamento. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ridimensiona l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| resizeType | int | Il tipo di ridimensionamento. |

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Unisce i dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Ridimensiona l'altezza proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | int | La nuova altezza. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'altezza proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Le impostazioni di ridimensionamento dell'immagine. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ridimensiona l'altezza proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | int | La nuova altezza. |
| resizeType | int | Tipo di ridimensionamento. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Ridimensiona la larghezza proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Ridimensiona la larghezza proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Le impostazioni di ridimensionamento dell'immagine. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ridimensiona la larghezza proporzionalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| resizeType | int | Tipo di ridimensionamento. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Ridimensiona il livello con la scala inversa specificata. (nuova larghezza = larghezza vecchia / scala; nuova altezza = altezza vecchia / scala)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | double | La scala X. |
| scaleY | double | La scala Y. |
| resizeType | int | Tipo di ridimensionamento. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Ruota l'immagine attorno al centro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Ruota l'immagine attorno al centro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | se impostato su true la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Colore dello sfondo. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Ruota, capovolge o ruota e capovolge l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Salva i dati dell'immagine nello stream sottostante.

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Salva i dati dell'oggetto nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Il flusso in cui salvare i dati dell'oggetto. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Il flusso in cui salvare i dati dell'immagine. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni di salvataggio. |

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Il flusso in cui salvare i dati dell'immagine. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni di salvataggio. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei limiti dell'immagine di destinazione. Impostare il rettangolo vuoto per utilizzare i limiti della sorgente. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Salva i dati dell'oggetto nello stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Il flusso in cui salvare i dati dell'oggetto. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Il file in cui salvare i dati dell'immagine. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Il file in cui salvare i dati dell'immagine. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni di salvataggio. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei limiti dell'immagine di destinazione. Impostare il rettangolo vuoto per utilizzare i limiti della sorgente. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dell'oggetto. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file in cui salvare i dati dell'oggetto. |
| overWrite | boolean | se impostato su true sovrascrive il contenuto del file, altrimenti verrà aggiunto. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei limiti dell'immagine di destinazione. Impostare il rettangolo vuoto per utilizzare i limiti della sorgente. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Salva i pixel ARGB a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | L'array di pixel ARGB a 32 bit. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Salva i pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | I pixel CMYK presentati come valori interi a 32 bit. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Salva i pixel. Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace saveCmyk32Pixels(Rectangle, int[]).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo in cui salvare i pixel. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | L'array di pixel CMYK. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Salva i pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo in cui salvare i pixel. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | L'array di pixel. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Salva i dati grezzi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati grezzi. |
| dataOffset | int | L'offset iniziale dei dati grezzi. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei dati grezzi. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Le impostazioni dei dati grezzi in cui si trovano i dati. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Il flusso in cui salvare i dati dell'immagine. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni di salvataggio. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei limiti dell'immagine di destinazione. Imposta il rettangolo vuoto per utilizzare i limiti di origine. |

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Salva i dati nel contenitore stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |
| psdVersion | int | La versione PSD. |
| bitDepth | int | La profondità di bit. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Ottiene o imposta i limiti assoluti.

Valore: i limiti assoluti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Imposta un pixel immagine 32-bit ARGB per la posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |
| argb32Color | int | Il pixel ARGB a 32 bit per la posizione specificata. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Imposta un valore che indica se la palette viene regolata automaticamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true se abilita la regolazione automatica della tavolozza; altrimenti, false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Ottiene o imposta un valore per il colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Ottiene o imposta la fusione dell'elemento ritagliato.

Valore: la fusione dell'elemento ritagliato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Ottiene o imposta la chiave della modalità di fusione.

Valore: la chiave della modalità di fusione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Ottiene o imposta la posizione del livello inferiore.

Valore: la posizione del livello inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il suggerimento della dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Ottiene o imposta le informazioni del canale.

Valore: le informazioni del canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Ottiene o imposta il ritaglio del livello. 0 = base, 1 = non-base.

Valore: il ritaglio del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Imposta il contenitore Image.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Il contenitore Image. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Imposta direttamente il caricatore dei dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | Il caricatore di dati. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Imposta lo stream dei dati dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il flusso di dati dell'oggetto. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Ottiene o imposta il nome visualizzato del livello.

Valore: Il nome visualizzato del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Ottiene l'opacità di riempimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Ottiene o imposta il riempitore del livello.

Valore: Il riempitore del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Ottiene o imposta i flag del livello. bit 0 = trasparenza protetta; bit 1 = visibile; bit 2 = obsoleto; bit 3 = 1 per Photoshop 5.0 e successive, indica se il bit 4 contiene informazioni utili; bit 4 = dati pixel irrilevanti per l'aspetto del documento.

Valore: I flag del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Imposta la palette nei punti specifici del formato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Nuova tavolozza ARGB a 32 bit. |

**Returns:**
boolean
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Ottiene o imposta l'intestazione.

Valore: L'intestazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo RasterImage.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione orizzontale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare di utilizzare il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Imposta un valore che indica se [ignore after save].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true se [ignore after save]; altrimenti, false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza dell'immagine è cambiata dopo il caricamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true se questa istanza ha l'immagine modificata; altrimenti, false. |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Imposta il trasformatore interno dei dati.

Valore: Il trasformatore interno dei dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.IInnerDataTransformer | Il trasformatore interno dei dati. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Imposta il monitor di interruzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | Il monitor di interruzione. |

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Ottiene o imposta i dati degli intervalli di fusione del livello.

Valore: I dati degli intervalli di fusione del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Ottiene o imposta la data e ora di creazione del livello.

Valore: La data e ora di creazione del livello. Se non ci sono dati sulla DataOra di creazione, restituisce il primo epoch del tempo Unix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Ottiene o imposta il blocco del livello (Nota che se il flag LayerFlags.TransparencyProtected è impostato verrà sovrascritto dal flag di blocco del livello. Per restituire il flag LayerFlags.TransparencyProtected è necessario applicarlo all'opzione del livello layer.Flags |= LayerFlags.TransparencyProtected

Valore: Il blocco del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Ottiene o imposta i dati della maschera del livello.

Valore: I dati della maschera del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Ottiene o imposta la palette del livello.

Valore: La tavolozza del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Ottiene o imposta la posizione sinistra del livello.

Valore: La posizione sinistra del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLevel(short value) {#setLevel-short-}
```
public final void setLevel(short value)
```


Ottiene e imposta il livello di soglia.

Valore: Il livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Ottiene o imposta l'allocazione massima consentita per il salvataggio di rotazione parziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'allocazione massima consentita per il salvataggio di rotazione parziale. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Imposta il gestore della memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Il gestore della memoria. |
| needDispose | boolean | se impostato su  true  [need dispose]. |

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Imposta il nome del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome del livello. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Ottiene o imposta il nome del livello.

Valore: Il nome del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Ottiene o imposta l'opacità del livello. 0 = trasparente, 255 = opaco.

Valore: L'opacità del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Imposta la tavolozza dei colori. La tavolozza dei colori non è utilizzata quando i pixel sono rappresentati direttamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza dei colori. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Imposta la palette dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su  true  i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine al caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Imposta un pixel immagine per la posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |
| color | [Color](../../com.aspose.psd/color) | Il colore del pixel per la posizione specificata. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true  se i componenti dell'immagine devono essere premoltiplicati; altrimenti,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Ottiene o imposta il convertitore di colore personalizzato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | Il convertitore di colore personalizzato |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Ottiene o imposta il convertitore di colore indicizzato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | Il convertitore di colore indicizzato |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Imposta la risoluzione per questo RasterImage.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpiX | double | La risoluzione orizzontale, in punti per pollice, del  RasterImage . |
| dpiY | double | La risoluzione verticale, in punti per pollice, del  RasterImage . |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Ottiene o imposta le risorse del livello.

Valore: Le risorse del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Ottiene o imposta la posizione destra del livello.

Valore: La posizione del livello destro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Ottiene o imposta la modalità di rotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di rotazione. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Ottiene o imposta l'evidenziazione del colore del foglio decorativo nell'elenco dei livelli

Valore: L'evidenziazione del colore del foglio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Ottiene o imposta la posizione superiore del livello.

Valore: La posizione del livello superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Ottiene un valore che indica se l'immagine ha un colore trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Ottiene il colore trasparente dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Ottiene o imposta un valore che indica se aggiornare i metadati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true  se aggiorna i metadati XMP; altrimenti,  false . |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando il caricamento dei dati grezzi è disponibile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true  se utilizza il caricamento di dati grezzi quando il caricamento di dati grezzi è disponibile.; altrimenti,  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Tutti i prodotti Aspose dovrebbero implementare questo metodo. Viene chiamato da un prodotto GroupDocs per indicare se GroupDocs stesso è licenziato o meno e specificare una filigrana personalizzata. Quando GroupDocs è licenziato, questa istanza di documento dovrebbe comportarsi come licenziata anche se il prodotto Aspose non è licenziato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo RasterImage.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione verticale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare di utilizzare il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Ottiene o imposta un valore che indica se il livello è visibile

Valore:  true  se questa istanza è visibile; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ottiene o imposta i metadati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | I metadati XMP. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Crea una copia superficiale del livello corrente. Per favore   per spiegazione.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Converte l'immagine raster in bitmap.

**Returns:**
java.awt.image.BufferedImage - Il bitmap
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Aggiorna le opzioni di fusione dopo la modifica del livello o delle risorse globali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Scrive l'intera riga di scansione nell'indice di riga di scansione specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scanLineIndex | int | Indice basato su zero della linea di scansione. |
| argb32Pixels | int[] | L'array di colori ARGB a 32 bit da scrivere. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Scrive l'intera riga di scansione nell'indice di riga di scansione specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scanLineIndex | int | Indice basato su zero della linea di scansione. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | L'array di colori dei pixel da scrivere. |

