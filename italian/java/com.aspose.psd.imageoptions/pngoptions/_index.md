---
title: "PngOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le opzioni di creazione del formato file PNG."
type: docs
weight: 19
url: /it/java/com.aspose.psd.imageoptions/pngoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Le opzioni di creazione del formato file PNG.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PngOptions()](#PngOptions--) | Inizializza una nuova istanza della classe  PngOptions  . |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.psd.imageoptions.PngOptions-) | Inizializza una nuova istanza della classe  JpegOptions . |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Il livello di compressione predefinito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Ottiene la profondità di bit. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Ottiene o imposta il tipo di colore. |
| [getCompressionLevel()](#getCompressionLevel--) | Il livello di compressione dell'immagine png nell'intervallo 0-9, dove 9 è la compressione massima e 0 è modalità di archiviazione. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getFilterType()](#getFilterType--) | Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png. |
| [getFullFrame()](#getFullFrame--) | Ottiene un valore che indica se [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Le opzioni multipagina |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [getProgressive()](#getProgressive--) | Ottiene o imposta un valore che indica se questo  PngOptions  è progressivo. |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene o imposta le impostazioni di risoluzione. |
| [getSource()](#getSource--) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [getXmpData()](#getXmpData--) | Ottiene o imposta il contenitore dei metadati XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Imposta la profondità di bit. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [setColorType(int value)](#setColorType-int-) | Ottiene o imposta il tipo di colore. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Il livello di compressione dell'immagine png nell'intervallo 0-9, dove 9 è la compressione massima e 0 è modalità di archiviazione. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [setFilterType(int value)](#setFilterType-int-) | Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Imposta un valore che indica se [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Le opzioni multipagina |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ottiene o imposta la tavolozza dei colori. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Ottiene o imposta un valore che indica se questo  PngOptions  è progressivo. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ottiene o imposta le impostazioni di risoluzione. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ottiene o imposta il contenitore dei metadati XMP. |
| [toString()](#toString--) |  |
| [validate_internalized()](#validate-internalized--) | La routine di convalida delle opzioni. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Inizializza una nuova istanza della classe  PngOptions  .

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.psd.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Inizializza una nuova istanza della classe  JpegOptions .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.psd.imageoptions/pngoptions) | Le opzioni PNG. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Il livello di compressione predefinito.

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
### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Ottiene la profondità di bit.

**Returns:**
byte - La profondità di bit.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Ottiene o imposta il tipo di colore.

**Returns:**
int - Il tipo di colore.
### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


Il livello di compressione dell'immagine png nell'intervallo 0-9, dove 9 è la compressione massima e 0 è modalità di archiviazione.

**Returns:**
int - il livello di compressione nell'intervallo 0-9, dove 9 è la compressione massima e 0 è modalità di archiviazione.
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
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png.

**Returns:**
int - il tipo di filtro utilizzato durante il processo di salvataggio del file png.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Ottiene un valore che indica se [full frame].

Valore:  true  se [full frame]; altrimenti,  false .

**Returns:**
boolean - un valore che indica se [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione.

Valore:  true  se ignorare l'evento dopo la creazione; altrimenti,  false .

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Le opzioni multipagina

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ottiene o imposta la tavolozza dei colori.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Ottiene o imposta il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Ottiene o imposta un valore che indica se questo  PngOptions  è progressivo.

**Returns:**
boolean -  true  se progressivo; altrimenti,  false .
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ottiene o imposta le impostazioni di risoluzione.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


Ottiene o imposta la sorgente in cui creare l'immagine.

Valore: La sorgente in cui creare l'immagine.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Ottiene o imposta le opzioni di rasterizzazione vettoriale.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ottiene o imposta il contenitore dei metadati XMP.

Valore: Il contenitore dei dati XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Imposta la profondità di bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | La profondità di bit. |

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

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Ottiene o imposta il tipo di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il tipo del colore. |

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


Il livello di compressione dell'immagine png nell'intervallo 0-9, dove 9 è la compressione massima e 0 è modalità di archiviazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il livello di compressione nell'intervallo 0-9, dove 9 è compressione massima e 0 è modalità di archiviazione. |

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

### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il tipo di filtro utilizzato durante il processo di salvataggio del file png. |

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

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Le opzioni multipagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ottiene o imposta la tavolozza dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

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

### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Ottiene o imposta un valore che indica se questo  PngOptions  è progressivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true  se progressivo; altrimenti,  false . |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ottiene o imposta le impostazioni di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

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

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Ottiene o imposta le opzioni di rasterizzazione vettoriale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ottiene o imposta il contenitore dei metadati XMP.

Valore: Il contenitore dei dati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate_internalized() {#validate-internalized--}
```
public void validate_internalized()
```


La routine di convalida delle opzioni.

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

