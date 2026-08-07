---
title: "PsdOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le opzioni di creazione del formato file PSD."
type: docs
weight: 21
url: /it/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Le opzioni di creazione del formato file PSD.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Inizializza una nuova istanza della classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | Inizializza una nuova istanza della classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | Inizializza una nuova istanza della classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Ottiene o imposta il colore dello sfondo. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Ottiene o imposta il conteggio dei bit per canale di colore. |
| [getChannelsCount()](#getChannelsCount--) | Ottiene o imposta il numero di canali di colore. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Ottiene o imposta la modalità colore psd. |
| [getCompressionMethod()](#getCompressionMethod--) | Ottiene o imposta il metodo di compressione psd. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getFullFrame()](#getFullFrame--) | Ottiene un valore che indica se [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Le opzioni multipagina |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene o imposta la versione del formato file. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Ottiene o imposta un valore che indica se [refresh image preview data] - opzione usata per massimizzare la compatibilità con altri visualizzatori di immagini PSD. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | Ottiene o imposta un valore che indica se - Rimuovere la risorsa globale del motore di testo - Utilizzato per alcuni file psd con livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per livelli di testo con font mancanti). |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene o imposta le impostazioni di risoluzione. |
| [getResources()](#getResources--) | Ottiene o imposta le risorse psd. |
| [getSource()](#getSource--) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [getUpdateMetadata()](#getUpdateMetadata--) | Ottiene o imposta un valore che indica se [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione del file psd. |
| [getXmpData()](#getXmpData--) | Ottieni o imposta il contenitore dei dati XMP |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | Mostra se la proprietà ColorMode è stata assegnata. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Ottiene o imposta il colore dello sfondo. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Ottiene o imposta il conteggio dei bit per canale di colore. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Ottiene o imposta il numero di canali di colore. |
| [setColorMode(short value)](#setColorMode-short-) | Ottiene o imposta la modalità colore psd. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Ottiene o imposta il metodo di compressione psd. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Imposta un valore che indica se [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Le opzioni multipagina |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ottiene o imposta la tavolozza dei colori. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Ottiene o imposta la versione del formato file. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Ottiene o imposta un valore che indica se [refresh image preview data] - opzione usata per massimizzare la compatibilità con altri visualizzatori di immagini PSD. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Ottiene o imposta un valore che indica se - Rimuovere la risorsa globale del motore di testo - Utilizzato per alcuni file psd con livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per livelli di testo con font mancanti). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ottiene o imposta le impostazioni di risoluzione. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Ottiene o imposta le risorse psd. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | Ottiene o imposta un valore che indica se [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta la versione del file psd. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ottieni o imposta il contenitore dei dati XMP |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Inizializza una nuova istanza della classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Inizializza una nuova istanza della classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Le opzioni. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


Inizializza una nuova istanza della classe [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | L'immagine. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Ottiene o imposta il colore di sfondo. Può essere visto sotto gli oggetti trasparenti.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Ottiene o imposta il conteggio dei bit per canale di colore.

Valore: Il conteggio dei bit per canale di colore.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Ottiene o imposta il numero di canali di colore.

Valore: Il numero di canali di colore.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Ottiene o imposta la modalità colore psd.

Valore: La modalità colore.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Ottiene o imposta il metodo di compressione psd.

Valore: Il metodo di compressione.

**Returns:**
short
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
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Ottiene o imposta la versione del formato file. Può essere PSD o PSB.

Valore: La versione del formato file.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


Ottiene o imposta un valore che indica se [refresh image preview data] - opzione usata per massimizzare la compatibilità con altri visualizzatori di immagini PSD. Si prega di notare che il disegno dei livelli di testo nel layout finale non è supportato sulla piattaforma Compact Framework.

Valore:  true  se [refresh image preview data]; altrimenti,  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


Ottiene o imposta un valore che indica se - Rimuovere la risorsa globale del motore di testo - Utilizzato per alcuni file psd con livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per livelli di testo con font mancanti). Dopo aver usato questa opzione, l'utente deve eseguire quanto segue nel file aperto in Photoshop: Menu \"Text\" -> \"Process absent fonts\". Dopo tale operazione tutto il testo riapparirà. Si prega di notare che questa operazione può causare alcune modifiche al layout finale.

Valore:  true  se [remove global text engine resource]; altrimenti,  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ottiene o imposta le impostazioni di risoluzione.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


Ottiene o imposta le risorse psd. Se valore: NULL - allora salva le ImageResources originali (comportamento predefinito) Non vuoto - allora salva le risorse passate a questa proprietà + [required resources] Vuoto - allora verranno salvate solo le [required resources]. Risorse richieste: ResolutionInfoResource, XmpResource

Valore: Le risorse psd.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Ottiene o imposta la sorgente in cui creare l'immagine.

Valore: La sorgente in cui creare l'immagine.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


Ottiene o imposta un valore che indica se [update metadata]. Se il valore è true, i metadati saranno aggiornati durante il salvataggio dell'immagine.

Valore:  true  se [update metadata]; altrimenti,  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Ottiene o imposta le opzioni di rasterizzazione vettoriale.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Ottiene o imposta la versione del file psd.

Valore: La versione del file psd.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ottieni o imposta il contenitore dei dati XMP

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


Mostra se la proprietà ColorMode è stata assegnata.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
```


Ottiene o imposta il colore di sfondo. Può essere visto sotto gli oggetti trasparenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Ottiene o imposta il conteggio dei bit per canale di colore.

Valore: Il conteggio dei bit per canale di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Ottiene o imposta il numero di canali di colore.

Valore: Il numero di canali di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Ottiene o imposta la modalità colore psd.

Valore: La modalità colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Ottiene o imposta il metodo di compressione psd.

Valore: Il metodo di compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Ottiene o imposta la versione del formato file. Può essere PSD o PSB.

Valore: La versione del formato file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


Ottiene o imposta un valore che indica se [refresh image preview data] - opzione usata per massimizzare la compatibilità con altri visualizzatori di immagini PSD. Si prega di notare che il disegno dei livelli di testo nel layout finale non è supportato sulla piattaforma Compact Framework.

Valore:  true  se [refresh image preview data]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


Ottiene o imposta un valore che indica se - Rimuovere la risorsa globale del motore di testo - Utilizzato per alcuni file psd con livelli di testo, solo nel caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per livelli di testo con font mancanti). Dopo aver usato questa opzione, l'utente deve eseguire quanto segue nel file aperto in Photoshop: Menu \"Text\" -> \"Process absent fonts\". Dopo tale operazione tutto il testo riapparirà. Si prega di notare che questa operazione può causare alcune modifiche al layout finale.

Valore:  true  se [remove global text engine resource]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ottiene o imposta le impostazioni di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


Ottiene o imposta le risorse psd. Se valore: NULL - allora salva le ImageResources originali (comportamento predefinito) Non vuoto - allora salva le risorse passate a questa proprietà + [required resources] Vuoto - allora verranno salvate solo le [required resources]. Risorse richieste: ResolutionInfoResource, XmpResource

Valore: Le risorse psd.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


Ottiene o imposta un valore che indica se [update metadata]. Se il valore è true, i metadati saranno aggiornati durante il salvataggio dell'immagine.

Valore:  true  se [update metadata]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Ottiene o imposta le opzioni di rasterizzazione vettoriale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Ottiene o imposta la versione del file psd.

Valore: La versione del file psd.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ottieni o imposta il contenitore dei dati XMP

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

