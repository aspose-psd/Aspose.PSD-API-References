---
title: "VectorRasterizationOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le opzioni di rasterizzazione vettoriale."
type: docs
weight: 29
url: /it/java/com.aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class VectorRasterizationOptions extends ImageOptionsBase
```

Le opzioni di rasterizzazione vettoriale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Copia su. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene un colore di sfondo. |
| [getBorderX()](#getBorderX--) | Ottiene o imposta il bordo X. |
| [getBorderY()](#getBorderY--) | Ottiene o imposta il bordo Y. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [getCenterDrawing()](#getCenterDrawing--) | Ottiene un valore che indica se il disegno è centrato. |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getDrawColor()](#getDrawColor--) | Ottiene un colore di primo piano. |
| [getFullFrame()](#getFullFrame--) | Ottiene un valore che indica se [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Le opzioni multipagina |
| [getPageHeight()](#getPageHeight--) | Ottiene l'altezza della pagina. |
| [getPageSize()](#getPageSize--) | Ottiene le dimensioni della pagina. |
| [getPageWidth()](#getPageWidth--) | Ottiene la larghezza della pagina. |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori. |
| [getPositioning()](#getPositioning--) | Ottiene il posizionamento. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene o imposta le impostazioni di risoluzione. |
| [getSmoothingMode()](#getSmoothingMode--) | Ottiene la modalità di smoothing. |
| [getSource()](#getSource--) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Ottiene il suggerimento di rendering del testo. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [getXmpData()](#getXmpData--) | Ottiene o imposta il contenitore dei metadati XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Imposta un colore di sfondo. |
| [setBorderX(float value)](#setBorderX-float-) | Ottiene o imposta il bordo X. |
| [setBorderY(float value)](#setBorderY-float-) | Ottiene o imposta il bordo Y. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Imposta un valore che indica se il disegno è centrato. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | Imposta un colore di primo piano. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Imposta un valore che indica se [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Le opzioni multipagina |
| [setPageHeight(float value)](#setPageHeight-float-) | Imposta l'altezza della pagina. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | Imposta le dimensioni della pagina. |
| [setPageWidth(float value)](#setPageWidth-float-) | Imposta la larghezza della pagina. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ottiene o imposta la tavolozza dei colori. |
| [setPositioning(int value)](#setPositioning-int-) | Imposta il posizionamento. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ottiene o imposta le impostazioni di risoluzione. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Imposta la modalità di smoothing. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Imposta il suggerimento di rendering del testo. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ottiene o imposta il contenitore dei metadati XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copia su.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | Le opzioni di rasterizzazione vettoriale. |

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ottiene un colore di sfondo.

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Ottiene o imposta il bordo X.

**Returns:**
float - Il bordo X.
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Ottiene o imposta il bordo Y.

**Returns:**
float - Il bordo Y.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Ottiene un valore che indica se il disegno è centrato.

**Returns:**
boolean - un valore che indica se il disegno è centrato.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Ottiene un colore di primo piano.

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
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
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Ottiene l'altezza della pagina.

**Returns:**
float - l'altezza della pagina.
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Ottiene le dimensioni della pagina.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Ottiene la larghezza della pagina.

**Returns:**
float - la larghezza della pagina.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ottiene o imposta la tavolozza dei colori.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Ottiene il posizionamento.

Valore: Il posizionamento.

**Returns:**
int - il posizionamento.
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
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Ottiene la modalità di smoothing.

**Returns:**
int - la modalità di smoothing.
### getSource() {#getSource--}
```
public final Source getSource()
```


Ottiene o imposta la sorgente in cui creare l'immagine.

Valore: La sorgente in cui creare l'immagine.

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Ottiene il suggerimento di rendering del testo.

Valore: il suggerimento di rendering del testo.

**Returns:**
int - il suggerimento di rendering del testo.
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Imposta un colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | un colore di sfondo. |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Ottiene o imposta il bordo X.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il bordo X. |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Ottiene o imposta il bordo Y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il bordo Y. |

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

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Imposta un valore che indica se il disegno è centrato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se il disegno è centrato. |

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

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


Imposta un colore di primo piano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | un colore di primo piano. |

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

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Imposta l'altezza della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | l'altezza della pagina. |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


Imposta le dimensioni della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | la dimensione della pagina. |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Imposta la larghezza della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | la larghezza della pagina. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ottiene o imposta la tavolozza dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Imposta il posizionamento.

Valore: Il posizionamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il posizionamento. |

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

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Imposta la modalità di smoothing.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la modalità di smoothing. |

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

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Imposta il suggerimento di rendering del testo.

Valore: il suggerimento di rendering del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il suggerimento di rendering del testo. |

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

