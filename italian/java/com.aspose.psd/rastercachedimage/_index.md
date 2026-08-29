---
title: "RasterCachedImage"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta un'immagine raster che supporta operazioni grafiche raster."
type: docs
weight: 85
url: /it/java/com.aspose.psd/rastercachedimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

Rappresenta un'immagine raster che supporta operazioni grafiche raster. Questa immagine memorizza nella cache i dati dei pixel quando necessario.
## Campi

| Campo | Descrizione |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Si verifica quando l'immagine è stata caricata |
| [OnLoad_internalized](#OnLoad-internalized) | Si verifica quando l'immagine è stata caricata da createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Si verifica quando l'immagine è stata caricata o salvata |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Si verifica quando il credito è stato utilizzato |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Regola la luminosità dell'immagine. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contrasto dell'immagine |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correzione gamma di un'immagine. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correzione gamma di un'immagine. |
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
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtra il rettangolo specificato. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Ottiene un pixel immagine ARGB a 32 bit. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Ottiene un valore che indica se la palette di regolazione automatica è abilitata. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene o imposta un valore per il colore di sfondo. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ottiene il conteggio dei bit per pixel dell'immagine. |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'immagine. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene il suggerimento sulla dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Restituisce il contenitore Image. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Restituisce lo stream di dati dell'oggetto. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Restituisce la tavolozza di regolazione profonda. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Restituisce l'array di pixel ARGB a 32 bit predefinito. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Restituisce le opzioni predefinite. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Restituisce l'array di pixel predefinito usando il caricatore di pixel parziali. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Restituisce l'array di dati grezzi predefinito usando il caricatore di pixel parziali. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Restituisce l'array di dati grezzi predefinito. |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getFileFormat()](#getFileFormat--) | Restituisce un valore del formato file |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Restituisce il formato file. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Restituisce il formato file. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Restituisce il formato file. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Restituisce il rettangolo che si adatta all'immagine corrente. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Restituisce il rettangolo che si adatta all'immagine corrente. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Ottiene la palette da posizioni specifiche del formato |
| [getHeight()](#getHeight--) | Ottiene l'altezza dell'immagine. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo RasterImage. |
| [getImageOpacity()](#getImageOpacity--) | Ottiene l'opacità di questa immagine. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Ottiene il trasformatore interno dei dati. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Ottiene il monitor di interruzione. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Ottiene o imposta l'allocazione massima consentita per il salvataggio di rotazione parziale. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Ottiene il gestore della memoria. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Ottiene la data e l'ora in cui l'immagine di risorsa è stata modificata l'ultima volta. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni basate sulle impostazioni del file originale. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Ottiene l'immagine dipingibile. |
| [getPalette()](#getPalette--) | Ottiene la tavolozza dei colori. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Ottiene un pixel dell'immagine. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Crea la cache privata dei caratteri. |
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
| [getRotateMode()](#getRotateMode--) | Ottiene o imposta la modalità di rotazione. |
| [getSize()](#getSize--) | Ottiene le dimensioni dell'immagine. |
| [getSkewAngle()](#getSkewAngle--) | Ottiene l'angolo di inclinazione. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Ottiene il percorso file dell'immagine sorgente se esiste. |
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
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Ottiene o imposta il valore massimo di avanzamento |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indica il progresso. |
| [isCached()](#isCached--) | Ottiene un valore che indica se i dati dell'immagine sono attualmente nella cache. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Ottiene un valore che indica se il caricamento dei dati grezzi è disponibile. |
| [isUsePalette()](#isUsePalette--) | Ottiene un valore che indica se la tavolozza dell'immagine è utilizzata. |
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
| [normalizeAngle()](#normalizeAngle--) | Normalizza l'angolo. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normalizza l'angolo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoca quando il contenitore di questa [Image](../../com.aspose.psd/image) è stato impostato. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Legge l'intera riga di scansione tramite l'indice di riga di scansione specificato. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Legge l'intera riga di scansione tramite l'indice di riga di scansione specificato. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Ridimensiona l'immagine. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Ridimensiona l'immagine. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona l'immagine. |
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
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Salva i dati dell'oggetto nello stream specificato. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio. |
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
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Imposta un pixel immagine 32-bit ARGB per la posizione specificata. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Imposta un valore che indica se la palette viene regolata automaticamente. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Ottiene o imposta un valore per il colore di sfondo. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Imposta il contenitore Image. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Imposta direttamente il caricatore dei dati. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Imposta lo stream dei dati dell'oggetto. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Imposta la palette nei punti specifici del formato |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo RasterImage. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Imposta un valore che indica se [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Ottiene o imposta un valore che indica se questa istanza dell'immagine è cambiata dopo il caricamento. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Imposta il trasformatore interno dei dati. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Imposta il monitor di interruzione. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Ottiene o imposta l'allocazione massima consentita per il salvataggio di rotazione parziale. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Imposta il gestore della memoria. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Imposta la palette dei colori. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Imposta la palette dell'immagine. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Imposta un pixel immagine per la posizione specificata. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Ottiene o imposta il convertitore di colore personalizzato |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Ottiene o imposta il convertitore di colore indicizzato |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Imposta la risoluzione per questo RasterImage. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Ottiene o imposta la modalità di rotazione. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Ottiene il colore trasparente dell'immagine. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando il caricamento dei dati grezzi è disponibile. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Tutti i prodotti Aspose dovrebbero implementare questo metodo. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo RasterImage. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ottiene o imposta i metadati XMP. |
| [toBitmap()](#toBitmap--) | Converte l'immagine raster in bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Scrive l'intera riga di scansione nell'indice di riga di scansione specificato. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Scrive l'intera riga di scansione nell'indice di riga di scansione specificato. |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
public abstract int getBitsPerPixel()
```


Ottiene il conteggio dei bit per pixel dell'immagine.

**Returns:**
int - Il conteggio dei bit per pixel dell'immagine.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
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
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Ottiene la palette da posizioni specifiche del formato

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Ottiene l'altezza dell'immagine.

**Returns:**
int - L'altezza dell'immagine.
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
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Ottiene o imposta la modalità di rotazione.

**Returns:**
int - La modalità di rotazione.
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
public abstract int getWidth()
```


Ottiene la larghezza dell'immagine.

**Returns:**
int - La larghezza dell'immagine.
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

**Returns:**
boolean -  true  se questa istanza ha alfa; altrimenti,  false .
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
public native int hashCode()
```




**Returns:**
int
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

### isCached() {#isCached--}
```
public boolean isCached()
```


Ottiene un valore che indica se i dati dell'immagine sono attualmente nella cache.

**Returns:**
boolean -  true  se i dati dell'immagine sono memorizzati nella cache; altrimenti,  false .
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


Invoca quando il contenitore di questa [Image](../../com.aspose.psd/image) è stato impostato.

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

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Salva i dati dell'immagine nello stream specificato nel formato file specificato secondo le opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Il flusso in cui salvare i dati dell'immagine. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni di salvataggio. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei limiti dell'immagine di destinazione. Imposta il rettangolo vuoto per utilizzare i limiti di origine. |

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

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Ottiene o imposta la modalità di rotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di rotazione. |

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

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ottiene o imposta i metadati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | I metadati XMP. |

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

