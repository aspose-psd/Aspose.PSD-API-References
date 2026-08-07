---
title: "AiImage"
second_title: "Riferimento API Aspose.PSD per Java"
description: "L'immagine AI di Adobe Illustrator"
type: docs
weight: 14
url: /it/java/com.aspose.psd.fileformats.ai/aiimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)
```
public final class AiImage extends Image
```

L'immagine Adobe Illustrator (AI)
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AiImage()](#AiImage--) | Inizializza una nuova istanza della classe [AiImage](../../com.aspose.psd.fileformats.ai/aiimage). |
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
| [addLayer(AiLayerSection layer)](#addLayer-com.aspose.psd.fileformats.ai.AiLayerSection-) | Aggiunge la sezione del livello AI. |
| [cacheData()](#cacheData--) | Memorizza nella cache i dati e garantisce che non venga effettuato alcun ulteriore caricamento dei dati dal sottostante P:Aspose.PSD.DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Determina se l'immagine può essere caricata dallo stream specificato. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Determina se l'immagine può essere caricata dallo stream specificato e, facoltativamente, usando le loadOptions specificate. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Determina se l'immagine può essere caricata dal percorso file specificato. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Determina se l'immagine può essere caricata dal percorso file specificato e, facoltativamente, usando le opzioni di apertura specificate. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio fornite. |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Converte in aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Crea una nuova immagine usando le opzioni di creazione specificate. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Crea una nuova immagine usando le immagini specificate come pagine. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Crea una nuova immagine con le immagini specificate come pagine. |
| [create_internalized(AiContentSource contentSource)](#create-internalized-com.aspose.internal.fileformats.ai.AiContentSource-) |  |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActivePageIndex()](#getActivePageIndex--) | Ottiene o imposta l'indice della pagina attiva. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Ottiene un valore che indica se la palette di regolazione automatica è abilitata. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene o imposta un valore per il colore di sfondo. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ottiene il conteggio dei bit per pixel dell'immagine. |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'immagine. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene il suggerimento sulla dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Restituisce il contenitore Image. |
| [getDataSection()](#getDataSection--) | Ottiene la sezione dei dati. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Restituisce lo stream di dati dell'oggetto. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Restituisce la tavolozza di regolazione profonda. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Restituisce le opzioni predefinite. |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getFileFormat()](#getFileFormat--) | Ottiene un valore del formato file. |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Restituisce il formato file. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Restituisce il formato file. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Restituisce il formato file. |
| [getFinalizeSection()](#getFinalizeSection--) | Ottiene la sezione di finalizzazione. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Restituisce il rettangolo che si adatta all'immagine corrente. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Restituisce il rettangolo che si adatta all'immagine corrente. |
| [getHeader()](#getHeader--) | Ottiene l'intestazione. |
| [getHeight()](#getHeight--) | Ottiene l'altezza dell'immagine. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Ottiene il monitor di interruzione. |
| [getLayers()](#getLayers--) | Ottiene le sezioni dei livelli. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Ottiene il gestore della memoria. |
| [getOriginalOptions()](#getOriginalOptions--) | Ottiene le opzioni basate sulle impostazioni del file originale. |
| [getPageCount()](#getPageCount--) | Il numero di pagine. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Ottiene l'immagine dipingibile. |
| [getPalette()](#getPalette--) | Ottiene la tavolozza dei colori. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Crea la cache privata dei caratteri. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene le informazioni del gestore dell'evento di avanzamento. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Ottiene le informazioni del gestore dell'evento di avanzamento. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Ottiene un'altezza proporzionale. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Ottiene una larghezza proporzionale. |
| [getSetupSection()](#getSetupSection--) | Ottiene la sezione di configurazione. |
| [getSize()](#getSize--) | Ottiene le dimensioni dell'immagine. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Ottiene il percorso file dell'immagine sorgente se esiste. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Ottiene un valore che indica se l'oggetto utilizza una strategia di ottimizzazione della memoria |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Ottiene la licenza venture. |
| [getVersion()](#getVersion--) | Ottiene la versione del formato Adobe Illustrator. |
| [getWidth()](#getWidth--) | Ottiene la larghezza dell'immagine. |
| [getXmpData()](#getXmpData--) | Ottiene i metadati XMP. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Ottiene un valore che indica se l'immagine ha un colore di sfondo. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Ottiene o imposta un valore che indica se questa istanza dell'immagine è cambiata dopo il caricamento. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Ottiene o imposta il valore massimo di avanzamento |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indica il progresso. |
| [isCached()](#isCached--) | Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati. |
| [isUsePalette()](#isUsePalette--) | Ottiene un valore che indica se la tavolozza dell'immagine è utilizzata. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Carica una nuova immagine dallo stream specificato. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Carica una nuova immagine dallo stream specificato. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Carica una nuova immagine dallo stream specificato. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Carica una nuova immagine dallo stream specificato. |
| [load(String filePath)](#load-java.lang.String-) | Carica una nuova immagine dal file specificato. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Carica una nuova immagine dal file specificato. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Carica una nuova immagine dallo stream specificato. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Carica una nuova immagine dallo stream specificato. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoca quando il contenitore di questa [Image](../../com.aspose.psd/image) è stato impostato. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Ridimensiona l'immagine. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Ridimensiona l'immagine. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ridimensiona l'immagine. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Ridimensiona l'altezza proporzionalmente. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ridimensiona l'altezza proporzionalmente. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ridimensiona l'altezza proporzionalmente. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Ridimensiona la larghezza proporzionalmente. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ridimensiona la larghezza proporzionalmente. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ridimensiona la larghezza proporzionalmente. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Ruota, capovolge o ruota e capovolge l'immagine. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setActivePageIndex(int value)](#setActivePageIndex-int-) | Ottiene o imposta l'indice della pagina attiva. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Imposta un valore che indica se la palette viene regolata automaticamente. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Ottiene o imposta un valore per il colore di sfondo. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Imposta il contenitore Image. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Imposta lo stream dei dati dell'oggetto. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Imposta un valore che indica se [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Ottiene o imposta un valore che indica se questa istanza dell'immagine è cambiata dopo il caricamento. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Imposta il monitor di interruzione. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Imposta il gestore della memoria. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Imposta la palette dei colori. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Imposta la palette dell'immagine. |
| [setRenderedImage_internalized(RasterImage value)](#setRenderedImage-internalized-com.aspose.psd.RasterImage-) | Ottiene l'immagine renderizzata. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Tutti i prodotti Aspose dovrebbero implementare questo metodo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AiImage() {#AiImage--}
```
public AiImage()
```


Inizializza una nuova istanza della classe [AiImage](../../com.aspose.psd.fileformats.ai/aiimage).

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

### addLayer(AiLayerSection layer) {#addLayer-com.aspose.psd.fileformats.ai.AiLayerSection-}
```
public final void addLayer(AiLayerSection layer)
```


Aggiunge la sezione del livello AI.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layer | [AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection) | La sezione del livello AI. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Memorizza nella cache i dati e garantisce che non venga effettuato alcun ulteriore caricamento dei dati dal sottostante P:Aspose.PSD.DataStreamSupporter.DataStreamContainer.

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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Converte in aps.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni immagine. |
| mode | int | La modalità. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo di ritaglio. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - istanza di ApsPage.
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
### create_internalized(AiContentSource contentSource) {#create-internalized-com.aspose.internal.fileformats.ai.AiContentSource-}
```
public static AiImage create_internalized(AiContentSource contentSource)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contentSource | com.aspose.internal.fileformats.ai.AiContentSource |  |

**Returns:**
[AiImage](../../com.aspose.psd.fileformats.ai/aiimage)
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'istanza corrente.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getActivePageIndex() {#getActivePageIndex--}
```
public final int getActivePageIndex()
```


Ottiene o imposta l'indice della pagina attiva.

Valore: Questa proprietà è valida solo per le immagini AI in formato PDF. Se l'immagine non è in formato PDF o non ci sono pagine, la proprietà sarà -1. Questa proprietà indica quale pagina dell'immagine AI sarà la base per il rendering.

**Returns:**
int
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
### getDataSection() {#getDataSection--}
```
public final AiDataSection getDataSection()
```


Ottiene la sezione dei dati.

Valore: La sezione dei dati.

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
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


Ottiene un valore del formato file.

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
### getFinalizeSection() {#getFinalizeSection--}
```
public final AiFinalizeSection getFinalizeSection()
```


Ottiene la sezione di finalizzazione.

Valore: La sezione di finalizzazione.

**Returns:**
[AiFinalizeSection](../../com.aspose.psd.fileformats.ai/aifinalizesection)
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
### getHeader() {#getHeader--}
```
public final AiHeader getHeader()
```


Ottiene l'intestazione.

Valore: L'intestazione.

**Returns:**
[AiHeader](../../com.aspose.psd.fileformats.ai/aiheader)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene l'altezza dell'immagine.

Valore: L'altezza dell'immagine.

**Returns:**
int
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Ottiene il monitor di interruzione.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayers() {#getLayers--}
```
public final AiLayerSection[] getLayers()
```


Ottiene le sezioni dei livelli.

Valore: Le sezioni dei livelli.

**Returns:**
com.aspose.psd.fileformats.ai.AiLayerSection[]
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Ottiene il gestore della memoria.

Valore: Il gestore della memoria.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - il gestore della memoria.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ottiene le opzioni basate sulle impostazioni del file originale. Questo può essere utile per mantenere inalterata la profondità di colore e altri parametri dell'immagine originale. Per esempio, se carichiamo un'immagine PNG in bianco‑nero con 1 bit per pixel e poi la salviamo usando il  DataStreamSupporter.Save(string)  metodo, verrà prodotta un'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, usa questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale al  Image.Save(string, ImageOptionsBase)  metodo come secondo parametro.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Il numero di pagine. Per il vecchio formato AI le immagini sono sempre pari a 0.

Valore: Il numero di pagine.

**Returns:**
int
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
### getSetupSection() {#getSetupSection--}
```
public final AiSetupSection getSetupSection()
```


Ottiene la sezione di configurazione.

Valore: La sezione di configurazione.

**Returns:**
[AiSetupSection](../../com.aspose.psd.fileformats.ai/aisetupsection)
### getSize() {#getSize--}
```
public Size getSize()
```


Ottiene le dimensioni dell'immagine.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Restituisce il percorso del file dell'immagine sorgente se esiste. Restituisce una stringa vuota se non è possibile trovare il percorso sorgente.

**Returns:**
java.lang.String - Il percorso del file dell'immagine sorgente.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Ottiene un valore che indica se l'oggetto utilizza una strategia di ottimizzazione della memoria

Valore:  true  se l'oggetto utilizza la strategia di ottimizzazione della memoria; altrimenti,  false .

**Returns:**
boolean - un valore che indica se l'oggetto utilizza la strategia di ottimizzazione della memoria
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Ottiene la licenza venture.

**Returns:**
java.lang.Object - La licenza venture come oggetto.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Ottiene la versione del formato Adobe Illustrator.

Valore: La versione.

**Returns:**
int
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
public final XmpPacketWrapper getXmpData()
```


Ottiene i metadati XMP.

Valore: I dati XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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


Restituisce un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è necessaria alcuna lettura dei dati.

Valore:  true  se i dati dell'oggetto sono nella cache; altrimenti,  false .

**Returns:**
boolean
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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Ruota, capovolge o ruota e capovolge l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | int | Tipo della rotazione e del capovolgimento. |

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




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setActivePageIndex(int value) {#setActivePageIndex-int-}
```
public final void setActivePageIndex(int value)
```


Ottiene o imposta l'indice della pagina attiva.

Valore: Questa proprietà è valida solo per le immagini AI in formato PDF. Se l'immagine non è in formato PDF o non ci sono pagine, la proprietà sarà -1. Questa proprietà indica quale pagina dell'immagine AI sarà la base per il rendering.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Imposta lo stream dei dati dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il flusso di dati dell'oggetto. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Imposta il monitor di interruzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | Il monitor di interruzione. |

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

### setRenderedImage_internalized(RasterImage value) {#setRenderedImage-internalized-com.aspose.psd.RasterImage-}
```
public final void setRenderedImage_internalized(RasterImage value)
```


Ottiene l'immagine renderizzata.

Valore: L'immagine renderizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Tutti i prodotti Aspose dovrebbero implementare questo metodo. Viene chiamato da un prodotto GroupDocs per indicare se GroupDocs stesso è licenziato o meno e specificare una filigrana personalizzata. Quando GroupDocs è licenziato, questa istanza di documento dovrebbe comportarsi come licenziata anche se il prodotto Aspose non è licenziato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Oggetto licenza Venture. |

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

