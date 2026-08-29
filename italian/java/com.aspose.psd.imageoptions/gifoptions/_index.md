---
title: "GifOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le opzioni di creazione del formato file GIF."
type: docs
weight: 12
url: /it/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

Le opzioni di creazione del formato file GIF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inizializza una nuova istanza della classe  GifOptions  . |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | Inizializza una nuova istanza della classe  GifOptions  . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | Ottiene o imposta la risoluzione colore GIF. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Ottiene o imposta un valore che indica se la correzione della palette è applicata. |
| [getFullFrame()](#getFullFrame--) | Ottiene un valore che indica se [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [getInterlaced()](#getInterlaced--) | Vero se l'immagine deve essere interlacciata. |
| [getMaxDiff()](#getMaxDiff--) | Ottiene o imposta la differenza massima consentita tra pixel. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Le opzioni multipagina |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Ottiene o imposta il rapporto d'aspetto dei pixel GIF. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene o imposta le impostazioni di risoluzione. |
| [getSource()](#getSource--) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [getXmpData()](#getXmpData--) | Ottiene o imposta il contenitore dei metadati XMP. |
| [hasTrailer()](#hasTrailer--) | Ottiene o imposta un valore che indica se il GIF ha un trailer. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | Ottiene o imposta un valore che indica se le voci della palette sono ordinate. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Ottiene o imposta la risoluzione colore GIF. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Ottiene o imposta un valore che indica se la correzione della palette è applicata. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Imposta un valore che indica se [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Vero se l'immagine deve essere interlacciata. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Ottiene o imposta la differenza massima consentita tra pixel. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Le opzioni multipagina |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ottiene o imposta la tavolozza dei colori. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Ottiene o imposta un valore che indica se le voci della palette sono ordinate. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Ottiene o imposta il rapporto d'aspetto dei pixel GIF. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ottiene o imposta le impostazioni di risoluzione. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Ottiene o imposta un valore che indica se il GIF ha un trailer. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ottiene o imposta il contenitore dei metadati XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inizializza una nuova istanza della classe  GifOptions  .

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Inizializza una nuova istanza della classe  GifOptions  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | Le opzioni GIF. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Ottiene o imposta l'indice del colore di sfondo GIF.

**Returns:**
byte - L'indice del colore di sfondo GIF.
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Ottiene o imposta la risoluzione colore GIF.

**Returns:**
byte - La risoluzione del colore.

Color Resolution - Numero di bit per colore primario disponibili nell'immagine originale, meno 1. Questo valore rappresenta la dimensione dell'intera tavolozza da cui sono stati selezionati i colori nella grafica, non il numero di colori effettivamente usati nella grafica. Per esempio, se il valore in questo campo è 3, allora la tavolozza dell'immagine originale aveva 4 bit per colore primario disponibili per creare l'immagine. Questo valore dovrebbe essere impostato per indicare la ricchezza della tavolozza originale, anche se non tutti i colori dell'intera tavolozza sono disponibili sulla macchina di origine.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Ottiene o imposta un valore che indica se la correzione della palette è applicata.

**Returns:**
boolean -  true  se la correzione della tavolozza è applicata; altrimenti,  false .

Palette correction significa che ogni volta che l'immagine viene esportata in GIF i colori dell'immagine di origine verranno analizzati per costruire la tavolozza più corrispondente (nel caso in cui la tavolozza dell'immagine non esista o non sia specificata nelle opzioni). Il processo di analisi richiede del tempo, tuttavia l'immagine risultante avrà la tavolozza di colori più adatta e il risultato sarà visivamente migliore.
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
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Vero se l'immagine deve essere interlacciata.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Ottiene o imposta la differenza massima consentita tra pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita. Il valore consigliato per una compressione con perdita ottimale è 80. 30 è una compressione molto leggera, 200 è pesante. Funziona al meglio quando viene introdotta solo una piccola perdita, e a causa delle limitazioni dell'algoritmo di compressione livelli di perdita molto alti non forniscono tanto guadagno. L'intervallo di valori consentiti è [0, 1000].

**Returns:**
int - L'intervallo dei valori consentiti.
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Ottiene o imposta il rapporto d'aspetto dei pixel GIF.

Pixel Aspect Ratio - Fattore usato per calcolare un'approssimazione del rapporto d'aspetto del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione del rapporto d'aspetto è calcolata sulla base della formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Il Pixel Aspect Ratio è definito come il quoziente tra la larghezza del pixel e la sua altezza. L'intervallo di valori in questo campo consente di specificare il pixel più largo da 4:1 al pixel più alto da 1:4 in incrementi di 1/64. Valori: 0 - Nessuna informazione sul rapporto d'aspetto fornita. 1..255 - Valore usato nel calcolo.

**Returns:**
byte - Il rapporto d'aspetto del pixel GIF.
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
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Ottiene o imposta un valore che indica se il GIF ha un trailer.

**Returns:**
boolean -  true  se il GIF ha trailer; altrimenti,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Ottiene o imposta un valore che indica se le voci della palette sono ordinate.

**Returns:**
boolean -  true  se le voci della tavolozza sono ordinate; altrimenti,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Ottiene o imposta l'indice del colore di sfondo GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | L'indice del colore di sfondo GIF. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Ottiene o imposta la risoluzione colore GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte | La risoluzione del colore. |

Color Resolution - Numero di bit per colore primario disponibili nell'immagine originale, meno 1. Questo valore rappresenta la dimensione dell'intera tavolozza da cui sono stati selezionati i colori nella grafica, non il numero di colori effettivamente usati nella grafica. Per esempio, se il valore in questo campo è 3, allora la tavolozza dell'immagine originale aveva 4 bit per colore primario disponibili per creare l'immagine. Questo valore dovrebbe essere impostato per indicare la ricchezza della tavolozza originale, anche se non tutti i colori dell'intera tavolozza sono disponibili sulla macchina di origine. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Ottiene o imposta un valore che indica se la correzione della palette è applicata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  se la correzione della tavolozza è applicata; altrimenti,  false . |

Palette correction significa che ogni volta che l'immagine viene esportata in GIF i colori dell'immagine di origine verranno analizzati per costruire la tavolozza più corrispondente (nel caso in cui la tavolozza dell'immagine non esista o non sia specificata nelle opzioni). Il processo di analisi richiede del tempo, tuttavia l'immagine risultante avrà la tavolozza di colori più adatta e il risultato sarà visivamente migliore. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Vero se l'immagine deve essere interlacciata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Ottiene o imposta la differenza massima consentita tra pixel. Se maggiore di zero, verrà utilizzata la compressione con perdita. Il valore consigliato per una compressione con perdita ottimale è 80. 30 è una compressione molto leggera, 200 è pesante. Funziona al meglio quando viene introdotta solo una piccola perdita, e a causa delle limitazioni dell'algoritmo di compressione livelli di perdita molto alti non forniscono tanto guadagno. L'intervallo di valori consentiti è [0, 1000].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'intervallo dei valori consentiti. |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Ottiene o imposta un valore che indica se le voci della palette sono ordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true  se le voci della tavolozza sono ordinate; altrimenti,  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Ottiene o imposta il rapporto d'aspetto dei pixel GIF.

Pixel Aspect Ratio - Fattore usato per calcolare un'approssimazione del rapporto d'aspetto del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione del rapporto d'aspetto è calcolata sulla base della formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Il Pixel Aspect Ratio è definito come il quoziente tra la larghezza del pixel e la sua altezza. L'intervallo di valori in questo campo consente di specificare il pixel più largo da 4:1 al pixel più alto da 1:4 in incrementi di 1/64. Valori: 0 - Nessuna informazione sul rapporto d'aspetto fornita. 1..255 - Valore usato nel calcolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | Il rapporto d'aspetto del pixel GIF. |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Ottiene o imposta un valore che indica se il GIF ha un trailer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true  se il GIF ha trailer; altrimenti,  false . |

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

