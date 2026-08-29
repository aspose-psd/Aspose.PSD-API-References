---
title: "Jpeg2000Options"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le opzioni del formato file JPEG2000."
type: docs
weight: 14
url: /it/java/com.aspose.psd.imageoptions/jpeg2000options/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Le opzioni del formato file JPEG2000.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Inizializza una nuova istanza della classe Jpeg2000Options. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-) | Inizializza una nuova istanza della classe Jpeg2000Options. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [getClass()](#getClass--) |  |
| [getCodec()](#getCodec--) | Ottiene o imposta il codec JPEG2000 |
| [getComments()](#getComments--) | Ottiene o imposta i marcatori di commento Jpeg. |
| [getCompressionRatios()](#getCompressionRatios--) | Ottiene o imposta l'array dei rapporti di compressione. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getFullFrame()](#getFullFrame--) | Ottiene un valore che indica se [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [getIrreversible()](#getIrreversible--) | Ottiene un valore che indica se utilizzare la DWT irreversibile 9-7 (true) o la compressione DWT lossless 5-3 (default). |
| [getMultiPageOptions()](#getMultiPageOptions--) | Le opzioni multipagina |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene o imposta le impostazioni di risoluzione. |
| [getSource()](#getSource--) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [getXmpData()](#getXmpData--) | Ottiene o imposta il contenitore dei metadati XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [setCodec(int value)](#setCodec-int-) | Ottiene o imposta il codec JPEG2000 |
| [setComments(String[] value)](#setComments-java.lang.String---) | Ottiene o imposta i marcatori di commento Jpeg. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Ottiene o imposta l'array dei rapporti di compressione. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Imposta un valore che indica se [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Imposta un valore che indica se utilizzare la DWT irreversibile 9-7 (true) o la compressione DWT lossless 5-3 (default). |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Le opzioni multipagina |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ottiene o imposta la tavolozza dei colori. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ottiene o imposta le impostazioni di risoluzione. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ottiene o imposta il contenitore dei metadati XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Inizializza una nuova istanza della classe Jpeg2000Options.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Inizializza una nuova istanza della classe Jpeg2000Options.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.psd.imageoptions/jpeg2000options) | Le opzioni del formato file Jpeg2000 da cui copiare le impostazioni. |

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
### getCodec() {#getCodec--}
```
public int getCodec()
```


Ottiene o imposta il codec JPEG2000

**Returns:**
int - Il codec JPEG2000
### getComments() {#getComments--}
```
public String[] getComments()
```


Ottiene o imposta i marcatori di commento Jpeg.

**Returns:**
java.lang.String[] - I marcatori di commento Jpeg.
### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Ottiene o imposta l'array dei rapporti di compressione. Rapporti di compressione diversi per i livelli successivi. Il tasso specificato per ogni livello di qualità è il fattore di compressione desiderato. Sono richiesti rapporti decrescenti.

**Returns:**
int[] - I rapporti di compressione.
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
### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Ottiene un valore che indica se utilizzare la DWT irreversibile 9-7 (true) o la compressione DWT lossless 5-3 (default).

**Returns:**
boolean - un valore che indica se utilizzare la DWT irreversibile 9-7 (true) o la compressione DWT lossless 5-3
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
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

### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Ottiene o imposta il codec JPEG2000

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il codec JPEG2000 |

### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Ottiene o imposta i marcatori di commento Jpeg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] | I marcatori di commento Jpeg. |

### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Ottiene o imposta l'array dei rapporti di compressione. Rapporti di compressione diversi per i livelli successivi. Il tasso specificato per ogni livello di qualità è il fattore di compressione desiderato. Sono richiesti rapporti decrescenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | I rapporti di compressione. |

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

### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Imposta un valore che indica se utilizzare la DWT irreversibile 9-7 (true) o la compressione DWT lossless 5-3 (default).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se utilizzare la DWT irreversibile 9-7 (true) o la compressione DWT lossless 5-3 |

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

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Il contenitore dati XMP. |

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

