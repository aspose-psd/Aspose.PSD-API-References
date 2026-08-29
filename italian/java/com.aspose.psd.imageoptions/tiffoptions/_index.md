---
title: "TiffOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le opzioni del formato file TIFF."
type: docs
weight: 25
url: /it/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Le opzioni del formato file tiff. Nota che i tag di larghezza e altezza verranno sovrascritti durante la creazione dell'immagine dai parametri di larghezza e altezza, quindi non è necessario specificarli direttamente. Nota che molte opzioni restituiscono un valore predefinito, ma ciò non significa che questa opzione sia impostata esplicitamente come valore di tag. Per verificare la presenza del tag, usa la proprietà Tags o il metodo corrispondente IsTagPresent.

AVVERTENZA! non modificare mai le opzioni tiff durante il salvataggio poiché ciò può causare effetti collaterali e bug difficili da individuare. La riga seguente è stata lasciata commentata appositamente poiché provocava una determinazione errata dell'inizio dei dati. Le opzioni passate non contenevano spp (anche se le opzioni non sono corrette in tal caso, questo scenario genera comunque errori) e la riga successiva aggiungeva i tag +spp e +bpp e, quando le opzioni venivano scritte dopo che i dati erano stati completamente scritti, sovrascrivevano l'inizio dei dati per il codec non compresso!!! Vedi TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Inizializza una nuova istanza della classe  TiffOptions  . |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Inizializza una nuova istanza della classe  TiffOptions  . |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Inizializza una nuova istanza della classe  TiffOptions  . |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Inizializza una nuova istanza della classe  TiffOptions  . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Aggiunge un nuovo tag. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Aggiunge i tag. |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Ottiene o imposta l'opzione di memorizzazione alfa. |
| [getArtist()](#getArtist--) | Ottiene o imposta l'artista. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Ottiene o imposta il colore dello sfondo. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce i bit per pixel. |
| [getBitsPerSample()](#getBitsPerSample--) | Ottiene i bit per campione. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [getByteOrder()](#getByteOrder--) | Ottiene o imposta un valore che indica l'ordine dei byte tiff. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Ottiene la cache. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Ottiene o imposta la mappa dei colori. |
| [getCompressedQuality()](#getCompressedQuality--) | Ottiene la qualità dell'immagine compressa. |
| [getCompression()](#getCompression--) | Ottiene la compressione. |
| [getCopyright()](#getCopyright--) | Ottiene il copyright. |
| [getDateTime()](#getDateTime--) | Ottiene o imposta la data e l'ora. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Ottiene o imposta il limite predefinito di allocazione della memoria. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getDocumentName()](#getDocumentName--) | Ottiene o imposta il nome del documento. |
| [getExifIfd()](#getExifIfd--) | Ottiene o imposta il puntatore a EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Ottiene il conteggio dei campioni extra. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Ottiene i valori dei campioni extra. |
| [getFaxT4Options()](#getFaxT4Options--) | Ottiene o imposta le opzioni fax t4. |
| [getFileStandard()](#getFileStandard--) | Ottiene o imposta lo standard del file TIFF. |
| [getFillOrder()](#getFillOrder--) | Ottiene o imposta l'ordine di riempimento dei bit dei byte. |
| [getFullFrame()](#getFullFrame--) | Ottiene un valore che indica se [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | Ottiene o imposta i suggerimenti di mezzitoni. |
| [getIccProfile()](#getIccProfile--) | Ottiene lo stream del profilo icc. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [getImageDescription()](#getImageDescription--) | Ottiene o imposta la descrizione dell'immagine. |
| [getImageLength()](#getImageLength--) | Ottiene o imposta la lunghezza dell'immagine. |
| [getImageWidth()](#getImageWidth--) | Ottiene o imposta la larghezza dell'immagine. |
| [getInkNames()](#getInkNames--) | Ottiene o imposta i nomi dell'inchiostro. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Ottiene o imposta il valore massimo del campione. |
| [getMinSampleValue()](#getMinSampleValue--) | Ottiene o imposta il valore minimo del campione. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Le opzioni multipagina |
| [getOrientation()](#getOrientation--) | Ottiene o imposta l'orientamento. |
| [getPageName()](#getPageName--) | Ottiene o imposta il nome della pagina. |
| [getPageNumber()](#getPageNumber--) | Ottiene o imposta il tag del numero di pagina. |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori. |
| [getPhotometric()](#getPhotometric--) | Ottiene o imposta il fotometrico. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Ottiene o imposta la configurazione planare. |
| [getPredictor()](#getPredictor--) | Ottiene o imposta il predittore per la compressione LZW. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene o imposta le impostazioni di risoluzione. |
| [getResolutionUnit()](#getResolutionUnit--) | Ottiene o imposta l'unità di risoluzione. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Ottiene o imposta le righe per striscia. |
| [getSampleFormat()](#getSampleFormat--) | Ottiene o imposta il formato del campione. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Ottiene i campioni per pixel. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Ottiene o imposta il produttore dello scanner. |
| [getScannerModel()](#getScannerModel--) | Ottiene o imposta il modello dello scanner. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Ottiene o imposta il valore massimo del campione. |
| [getSminSampleValue()](#getSminSampleValue--) | Ottiene o imposta il valore minimo del campione. |
| [getSoftwareType()](#getSoftwareType--) | Ottiene o imposta il tipo di software. |
| [getSource()](#getSource--) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [getStripByteCounts()](#getStripByteCounts--) | Ottiene o imposta il conteggio dei byte della striscia. |
| [getStripOffsets()](#getStripOffsets--) | Ottiene o imposta gli offset della striscia. |
| [getSubFileType()](#getSubFileType--) | Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo subfile. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Ottiene l'istanza del tag per tipo. |
| [getTags()](#getTags--) | Ottiene o imposta i tag. |
| [getTargetPrinter()](#getTargetPrinter--) | Ottiene o imposta la stampante di destinazione. |
| [getThreshholding()](#getThreshholding--) | Ottiene o imposta la soglia. |
| [getTileByteCounts()](#getTileByteCounts--) | Ottiene o imposta il conteggio dei byte della tile. |
| [getTileLength()](#getTileLength--) | Ottiene ot imposta la lunghezza della tile. |
| [getTileOffsets()](#getTileOffsets--) | Ottiene o imposta gli offset della tile. |
| [getTileWidth()](#getTileWidth--) | Ottiene ot imposta la larghezza della tile. |
| [getTotalPages()](#getTotalPages--) | Ottiene il numero totale di pagine. |
| [getValidTagCount()](#getValidTagCount--) | Ottiene il conteggio valido dei tag. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Restituisce il conteggio dei tag validi. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [getXPAuthor()](#getXPAuthor--) | Ottiene l'autore dell'immagine, utilizzato da Windows Explorer. |
| [getXPComment()](#getXPComment--) | Ottiene il commento sull'immagine, utilizzato da Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Ottiene l'oggetto dell'immagine, utilizzato da Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Ottiene le informazioni sull'immagine, utilizzato da Windows Explorer. |
| [getXPTitle()](#getXPTitle--) | Ottiene le informazioni sull'immagine, utilizzato da Windows Explorer. |
| [getXmpData()](#getXmpData--) | Ottiene o imposta il contenitore dei metadati XMP. |
| [getXposition()](#getXposition--) | Ottiene o imposta la posizione x. |
| [getXresolution()](#getXresolution--) | Ottiene o imposta la risoluzione x. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Ottiene o imposta i coefficienti YCbCr. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr. |
| [getYposition()](#getYposition--) | Ottiene o imposta la posizione y. |
| [getYresolution()](#getYresolution--) | Ottiene o imposta la risoluzione y. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Restituisce un valore che indica se gli extra samples sono presenti. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Determina se il tag è presente nelle opzioni o meno. |
| [isTiled()](#isTiled--) | Restituisce un valore che indica se l'immagine è a tasselli. |
| [isValid()](#isValid--) | Restituisce un valore che indica se le  TiffOptions  sono state configurate correttamente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Rimuove il tag. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Ottiene o imposta l'opzione di memorizzazione alfa. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Ottiene o imposta l'artista. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Ottiene o imposta il colore dello sfondo. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Imposta i bit per campione. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [setByteOrder(int value)](#setByteOrder-int-) | Ottiene o imposta un valore che indica l'ordine dei byte tiff. |
| [setColorMap(int[] value)](#setColorMap-int---) | Ottiene o imposta la mappa dei colori. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Imposta la qualità dell'immagine compressa. |
| [setCompression(int value)](#setCompression-int-) | Imposta la compressione. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Imposta il copyright. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Ottiene o imposta la data e l'ora. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Ottiene o imposta il limite predefinito di allocazione della memoria. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Ottiene o imposta il nome del documento. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Imposta i valori degli extra samples. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Ottiene o imposta le opzioni fax t4. |
| [setFileStandard(int value)](#setFileStandard-int-) | Ottiene o imposta lo standard del file TIFF. |
| [setFillOrder(int value)](#setFillOrder-int-) | Ottiene o imposta l'ordine di riempimento dei bit dei byte. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Imposta un valore che indica se [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Ottiene o imposta i suggerimenti di mezzitoni. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Imposta lo stream del profilo icc. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Ottiene o imposta la descrizione dell'immagine. |
| [setImageLength(long value)](#setImageLength-long-) | Ottiene o imposta la lunghezza dell'immagine. |
| [setImageWidth(long value)](#setImageWidth-long-) | Ottiene o imposta la larghezza dell'immagine. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Ottiene o imposta i nomi dell'inchiostro. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Ottiene o imposta il valore massimo del campione. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Ottiene o imposta il valore minimo del campione. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Le opzioni multipagina |
| [setOrientation(int value)](#setOrientation-int-) | Ottiene o imposta l'orientamento. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Ottiene o imposta il nome della pagina. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Ottiene o imposta il tag del numero di pagina. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ottiene o imposta la tavolozza dei colori. |
| [setPhotometric(int value)](#setPhotometric-int-) | Ottiene o imposta il fotometrico. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Ottiene o imposta la configurazione planare. |
| [setPredictor(int value)](#setPredictor-int-) | Ottiene o imposta il predittore per la compressione LZW. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ottiene o imposta le impostazioni di risoluzione. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Ottiene o imposta l'unità di risoluzione. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Ottiene o imposta le righe per striscia. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Ottiene o imposta il formato del campione. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Ottiene o imposta il produttore dello scanner. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Ottiene o imposta il modello dello scanner. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Ottiene o imposta il valore massimo del campione. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Ottiene o imposta il valore minimo del campione. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Ottiene o imposta il tipo di software. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Ottiene o imposta il conteggio dei byte della striscia. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Ottiene o imposta gli offset della striscia. |
| [setSubFileType(long value)](#setSubFileType-long-) | Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo subfile. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Ottiene o imposta i tag. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Ottiene o imposta la stampante di destinazione. |
| [setThreshholding(int value)](#setThreshholding-int-) | Ottiene o imposta la soglia. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Ottiene o imposta il conteggio dei byte della tile. |
| [setTileLength(long value)](#setTileLength-long-) | Ottiene ot imposta la lunghezza della tile. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Ottiene o imposta gli offset della tile. |
| [setTileWidth(long value)](#setTileWidth-long-) | Ottiene ot imposta la larghezza della tile. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Imposta l'autore dell'immagine, utilizzato da Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Imposta il commento sull'immagine, utilizzato da Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Imposta il subject image, utilizzato da Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Imposta le informazioni sull'immagine, utilizzate da Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Imposta le informazioni sull'immagine, utilizzate da Windows Explorer. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ottiene o imposta il contenitore dei metadati XMP. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la posizione x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione x. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Ottiene o imposta i coefficienti YCbCr. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la posizione y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Ottiene o imposta la risoluzione y. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Convalida se le opzioni hanno una combinazione valida di tag. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Inizializza una nuova istanza della classe  TiffOptions  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expectedFormat | int | Il formato di file tiff previsto. |
| byteOrder | int | L'ordine dei byte del formato file tiff da utilizzare. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Inizializza una nuova istanza della classe  TiffOptions . Per impostazione predefinita viene utilizzata la convenzione little endian.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expectedFormat | int | Il formato di file tiff previsto. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Inizializza una nuova istanza della classe  TiffOptions  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Le opzioni da copiare. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Inizializza una nuova istanza della classe  TiffOptions  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | I tag con cui inizializzare le opzioni. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Aggiunge un nuovo tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Il tag da aggiungere. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Aggiunge i tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | I tag da aggiungere. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clona questa istanza.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Clona questa istanza.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'istanza corrente.

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Restituisce o imposta l'opzione di archiviazione alfa. Le opzioni diverse da  TiffAlphaStorage.Unspecified  sono utilizzate quando sono definiti più di 3  SamplesPerPixel .

**Returns:**
int - L'opzione di memorizzazione alfa.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Ottiene o imposta l'artista.

**Returns:**
java.lang.String - L'artista.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Ottiene o imposta il colore dello sfondo. Utilizzato per scopi interni per memorizzare il colore di sfondo dell'immagine.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce i bit per pixel.

**Returns:**
int - I bit per pixel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Ottiene i bit per campione.

**Returns:**
int[] - Il valore dei bit per campione.

Quando si imposta questo valore, tenere presente che imposterà anche il valore SamplesPerPixel alla lunghezza dell'array. Queste 2 proprietà sono molto strettamente collegate, quindi possono essere impostate solo insieme.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Ottiene o imposta un valore che indica l'ordine dei byte tiff.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Ottiene la cache.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tag | int | Il tag (che è un tipo array). |

**Returns:**
long[] - Il valore del tag.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Ottiene o imposta la mappa dei colori.

**Returns:**
int[] - La mappa dei colori.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Ottiene la qualità dell'immagine compressa. Utilizzato con la compressione JPEG.

**Returns:**
int - qualità dell'immagine compressa.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Ottiene la compressione.

**Returns:**
int - La compressione.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Ottiene il copyright.

**Returns:**
java.lang.String - Il copyright.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Ottiene o imposta la data e l'ora.

**Returns:**
java.lang.String - La data e l'ora.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Ottiene o imposta il limite predefinito di allocazione della memoria.

**Returns:**
int - Il limite predefinito di allocazione della memoria.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). Per ottenere il nome corretto del font predefinito è possibile utilizzare il seguente frammento di codice: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valore: Il font di sostituzione predefinito.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Ottiene o imposta il nome del documento.

**Returns:**
java.lang.String - Il nome del documento.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Ottiene o imposta il puntatore a EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Ottiene il conteggio dei campioni extra.

Valore: Il conteggio dei campioni extra.

**Returns:**
long - il conteggio dei campioni extra.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Ottiene i valori dei campioni extra.

Valore: Il valore dei campioni extra.

**Returns:**
int[] - i valori dei campioni extra.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Ottiene o imposta le opzioni fax t4.

**Returns:**
long - Le opzioni fax t4.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Ottiene o imposta lo standard del file TIFF.

**Returns:**
int - Lo standard del file TIFF.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Ottiene o imposta l'ordine di riempimento dei bit dei byte.

**Returns:**
int - L'ordine di riempimento dei bit dei byte.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Ottiene un valore che indica se [full frame].

Valore:  true  se [full frame]; altrimenti,  false .

**Returns:**
boolean - un valore che indica se [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Ottiene o imposta i suggerimenti di mezzitoni.

**Returns:**
int[] - I suggerimenti per l'halftone.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Ottiene lo stream del profilo icc.

**Returns:**
byte[] - Il profilo ICC.
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione.

Valore:  true  se ignorare l'evento dopo la creazione; altrimenti,  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Ottiene o imposta la descrizione dell'immagine.

**Returns:**
java.lang.String - La descrizione dell'immagine.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Ottiene o imposta la lunghezza dell'immagine.

**Returns:**
long - La lunghezza dell'immagine.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Ottiene o imposta la larghezza dell'immagine.

**Returns:**
long - La larghezza dell'immagine.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Ottiene o imposta i nomi dell'inchiostro.

**Returns:**
java.lang.String - I nomi dell'inchiostro.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Ottiene o imposta il valore massimo del campione.

**Returns:**
int[] - Il valore massimo del campione.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Ottiene o imposta il valore minimo del campione.

**Returns:**
int[] - Il valore minimo del campione.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Le opzioni multipagina

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Ottiene o imposta l'orientamento.

**Returns:**
int - L'orientamento.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Ottiene o imposta il nome della pagina.

**Returns:**
java.lang.String - Il nome della pagina.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Ottiene o imposta il tag del numero di pagina.

**Returns:**
int[] - Il tag del numero di pagina.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ottiene o imposta la tavolozza dei colori.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Ottiene o imposta il fotometrico.

**Returns:**
int - Il fotometrico.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Ottiene o imposta la configurazione planare.

**Returns:**
int - La configurazione planare.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Ottiene o imposta il predittore per la compressione LZW.

**Returns:**
int - Il tipo di predittore.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati.

**Returns:**
boolean -  true  se i componenti devono essere premoltiplicati; altrimenti,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Ottiene o imposta il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ottiene o imposta le impostazioni di risoluzione.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Ottiene o imposta l'unità di risoluzione.

**Returns:**
int - L'unità di risoluzione.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Ottiene o imposta le righe per striscia.

**Returns:**
long - Le righe per striscia.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Ottiene o imposta il formato del campione.

**Returns:**
int[] - Il formato del campione.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Ottiene i campioni per pixel. Per modificare il valore di questa proprietà usa il setter della proprietà  BitsPerSample  .

**Returns:**
int - I campioni per pixel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Ottiene o imposta il produttore dello scanner.

**Returns:**
java.lang.String - Il produttore dello scanner.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Ottiene o imposta il modello dello scanner.

**Returns:**
java.lang.String - Il modello dello scanner.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Ottiene o imposta il valore massimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long).

**Returns:**
long[] - Il valore massimo del campione.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Ottiene o imposta il valore minimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long).

**Returns:**
long[] - Il valore minimo del campione.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Ottiene o imposta il tipo di software.

**Returns:**
java.lang.String - Il tipo di software.
### getSource() {#getSource--}
```
public final Source getSource()
```


Ottiene o imposta la sorgente in cui creare l'immagine.

Valore: La sorgente in cui creare l'immagine.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Ottiene o imposta il conteggio dei byte della striscia.

**Returns:**
long[] - I conteggi dei byte della striscia.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Ottiene o imposta gli offset della striscia.

**Returns:**
long[] - Gli offset delle strisce.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo subfile.

**Returns:**
long - L'indicazione generale del tipo di dati contenuti in questo sottofile.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Ottiene l'istanza del tag per tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagKey | int | La chiave del tag. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Ottiene o imposta i tag.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - I tag.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Ottiene o imposta la stampante di destinazione.

**Returns:**
java.lang.String - La stampante di destinazione.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Ottiene o imposta la soglia.

**Returns:**
int - La soglia.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Ottiene o imposta il conteggio dei byte della tile.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Ottiene ot imposta la lunghezza della tile.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Ottiene o imposta gli offset della tile.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Ottiene ot imposta la larghezza della tile.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Ottiene il numero totale di pagine.

**Returns:**
int - Il numero totale di pagine.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Restituisce il conteggio dei tag validi. Non è il conteggio totale dei tag, ma il numero di tag che possono essere conservati.

**Returns:**
int - Il conteggio dei tag validi.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Restituisce il conteggio dei tag validi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | I tag da convalidare. |

**Returns:**
int - Il conteggio dei tag validi.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Ottiene o imposta le opzioni di rasterizzazione vettoriale.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Ottiene l'autore dell'immagine, utilizzato da Windows Explorer.

Valore: Autore dell'immagine, usato da Windows Explorer. L'XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) è ignorato da Windows Explorer se esiste il tag Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)).

**Returns:**
java.lang.String - autore dell'immagine, usato da Windows Explorer.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Ottiene il commento sull'immagine, utilizzato da Windows Explorer.

Valore: Commento sull'immagine, usato da Windows Explorer.

**Returns:**
java.lang.String - commento sull'immagine, usato da Windows Explorer.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Ottiene l'oggetto dell'immagine, utilizzato da Windows Explorer.

Valore: Soggetto dell'immagine, usato da Windows Explorer.

**Returns:**
java.lang.String - soggetto dell'immagine, usato da Windows Explorer.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Ottiene le informazioni sull'immagine, utilizzato da Windows Explorer.

Valore: Informazioni sull'immagine, usate da Windows Explorer.

**Returns:**
java.lang.String - informazioni sull'immagine, usate da Windows Explorer.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Ottiene le informazioni sull'immagine, utilizzato da Windows Explorer.

Valore: Informazioni sull'immagine, usate da Windows Explorer. L'XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) è ignorato da Windows Explorer se esiste il tag ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)).

**Returns:**
java.lang.String - informazioni sull'immagine, usate da Windows Explorer.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ottiene o imposta il contenitore dei metadati XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Ottiene o imposta la posizione x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Ottiene o imposta la risoluzione x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Ottiene o imposta i coefficienti YCbCr.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - I coefficienti YCbCr.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr.

**Returns:**
int[] - I fattori di sottocampionamento per la fotometria YCbCr.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Ottiene o imposta la posizione y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Ottiene o imposta la risoluzione y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Restituisce un valore che indica se gli extra samples sono presenti.

**Returns:**
boolean -  true  se i campioni extra sono presenti; altrimenti,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Determina se il tag è presente nelle opzioni o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tag | int | L'ID del tag da verificare. |

**Returns:**
boolean -  true  se il tag è presente; altrimenti,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Restituisce un valore che indica se l'immagine è a tasselli.

**Returns:**
boolean -  true  se l'immagine è a tasselli; altrimenti,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Restituisce un valore che indica se le TiffOptions sono state configurate correttamente. Usa il metodo Validate per trovare il motivo dell'errore.

**Returns:**
boolean -  true  se le TiffOptions sono configurate correttamente; altrimenti,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Rimuove il tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tag | int | Il tag da rimuovere. |

**Returns:**
boolean - true se rimosso con successo
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Restituisce o imposta l'opzione di archiviazione alfa. Le opzioni diverse da  TiffAlphaStorage.Unspecified  sono utilizzate quando sono definiti più di 3  SamplesPerPixel .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'opzione di memorizzazione alfa. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Ottiene o imposta l'artista.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | L'artista. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Ottiene o imposta il colore dello sfondo. Utilizzato per scopi interni per memorizzare il colore di sfondo dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Il colore dello sfondo. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Imposta i bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int[] | Il valore dei bit per campione. |

Quando imposti questo valore, tieni presente che imposterà anche il valore SamplesPerPixel alla lunghezza dell'array. Queste 2 proprietà sono molto strettamente collegate, quindi possono essere impostate solo insieme. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Ottiene o imposta un valore che indica l'ordine dei byte tiff.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Ottiene o imposta la mappa dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | La mappa dei colori. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Imposta la qualità dell'immagine compressa. Usato con la compressione Jpeg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | qualità dell'immagine compressa. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Imposta la compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La compressione. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Imposta il copyright.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il copyright. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Ottiene o imposta la data e l'ora.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La data e l'ora. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Ottiene o imposta il limite predefinito di allocazione della memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il limite predefinito di allocazione della memoria. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). Per ottenere il nome corretto del font predefinito è possibile utilizzare il seguente frammento di codice: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valore: Il font di sostituzione predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Ottiene o imposta il nome del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il nome del documento. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Imposta i valori degli extra samples.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il valore dei campioni extra. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Ottiene o imposta le opzioni fax t4.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Le opzioni fax t4. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Ottiene o imposta lo standard del file TIFF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Lo standard del file TIFF. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Ottiene o imposta l'ordine di riempimento dei bit dei byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'ordine di riempimento dei bit byte. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Imposta un valore che indica se [full frame].

Valore:  true  se [full frame]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [full frame]. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Ottiene o imposta i suggerimenti di mezzitoni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | I suggerimenti per la mezzitonalità. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Imposta lo stream del profilo icc.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] | Il profilo icc. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione.

Valore:  true  se ignorare l'evento dopo la creazione; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Ottiene o imposta la descrizione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La descrizione dell'immagine. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Ottiene o imposta la lunghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | La lunghezza dell'immagine. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Ottiene o imposta la larghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | La larghezza dell'immagine. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Ottiene o imposta i nomi dell'inchiostro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | I nomi dell'inchiostro. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Ottiene o imposta il valore massimo del campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il valore massimo del campione. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Ottiene o imposta il valore minimo del campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il valore minimo del campione. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Le opzioni multipagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Ottiene o imposta l'orientamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'orientamento. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Ottiene o imposta il nome della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il nome della pagina. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Ottiene o imposta il tag del numero di pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il tag del numero di pagina. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ottiene o imposta la tavolozza dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza dei colori. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Ottiene o imposta il fotometrico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il fotometrico. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Ottiene o imposta la configurazione planare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La configurazione planare. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Ottiene o imposta il predittore per la compressione LZW.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il tipo di predittore. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true se i componenti devono essere premoltiplicati; altrimenti, false. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Ottiene o imposta il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ottiene o imposta le impostazioni di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Ottiene o imposta l'unità di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'unità di risoluzione. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Ottiene o imposta le righe per striscia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Le righe per striscia. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Ottiene o imposta il formato del campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | Il formato del campione. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Ottiene o imposta il produttore dello scanner.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il produttore dello scanner. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Ottiene o imposta il modello dello scanner.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il modello dello scanner. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Ottiene o imposta il valore massimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | Il valore massimo del campione. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Ottiene o imposta il valore minimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | Il valore minimo del campione. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Ottiene o imposta il tipo di software.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il tipo di software. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Ottiene o imposta la sorgente in cui creare l'immagine.

Valore: La sorgente in cui creare l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Ottiene o imposta il conteggio dei byte della striscia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | Il conteggio dei byte della striscia. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Ottiene o imposta gli offset della striscia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] | Gli offset della striscia. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo subfile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | L'indicazione generale del tipo di dati contenuti in questo sottofile. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Ottiene o imposta i tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | I tag. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Ottiene o imposta la stampante di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | La stampante di destinazione. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Ottiene o imposta la soglia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il thresholding. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Ottiene o imposta il conteggio dei byte della tile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Ottiene ot imposta la lunghezza della tile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Ottiene o imposta gli offset della tile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Ottiene ot imposta la larghezza della tile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Ottiene o imposta le opzioni di rasterizzazione vettoriale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Imposta l'autore dell'immagine, utilizzato da Windows Explorer.

Valore: Image Author, usato da Windows Explorer. Il XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) è ignorato da Windows Explorer se esiste il tag Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | autore dell'immagine, usato da Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Imposta il commento sull'immagine, utilizzato da Windows Explorer.

Valore: Commento sull'immagine, usato da Windows Explorer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | commento sull'immagine, usato da Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Imposta il subject image, utilizzato da Windows Explorer.

Valore: Soggetto dell'immagine, usato da Windows Explorer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | immagine soggetto, usata da Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Imposta le informazioni sull'immagine, utilizzate da Windows Explorer.

Valore: Informazioni sull'immagine, usate da Windows Explorer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | informazioni sull'immagine, usate da Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Imposta le informazioni sull'immagine, utilizzate da Windows Explorer.

Valore: Informazioni sull'immagine, usate da Windows Explorer. Il XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) è ignorato da Windows Explorer se esiste il tag ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | informazioni sull'immagine, usate da Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ottiene o imposta il contenitore dei metadati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Il contenitore dati XMP. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Ottiene o imposta la posizione x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La posizione x. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Ottiene o imposta la risoluzione x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La risoluzione x. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Ottiene o imposta i coefficienti YCbCr.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | I coefficienti YCbCr. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | I fattori di sottocampionamento per la fotometria YCbCr. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Ottiene o imposta la posizione y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La posizione y. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Ottiene o imposta la risoluzione y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La risoluzione y. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


Convalida se le opzioni hanno una combinazione valida di tag.

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

