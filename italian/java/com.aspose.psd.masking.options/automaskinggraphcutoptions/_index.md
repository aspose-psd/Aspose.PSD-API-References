---
title: "AutoMaskingGraphCutOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le opzioni di mascheramento automatico GraphCut."
type: docs
weight: 12
url: /it/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Le opzioni di mascheramento automatico GraphCut.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Inizializza una nuova istanza della classe [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Il numero dell'oggetto di sfondo |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Aggiungi argomenti di auto mascheramento. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Riempire i tratti predefiniti. |
| [getArgs()](#getArgs--) | Ottiene gli argomenti per l'algoritmo di segmentazione. |
| [getAssumedObjects()](#getAssumedObjects--) | Ottiene gli oggetti presunti. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Ottiene il colore di sostituzione dello sfondo. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Ottiene un valore che indica se i tratti predefiniti devono essere calcolati. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Ottiene il rettangolo degli oggetti combinati. |
| [getDecompose()](#getDecompose--) | Ottiene un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Ottiene i tratti di sfondo predefiniti. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Ottiene i tratti di primo piano predefiniti pre‑calcolati. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Ottiene i rettangoli degli oggetti predefiniti. |
| [getExportOptions()](#getExportOptions--) | Ottiene le opzioni di esportazione dell'immagine. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Ottiene il raggio di sfumatura. |
| [getMaskingArea()](#getMaskingArea--) | Ottiene l'area di mascheramento. |
| [getMethod()](#getMethod--) | Ottiene il metodo di segmentazione. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Ottiene il gestore dell'evento di avanzamento del processo di pre‑calcolo dei punti predefiniti. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Ottiene un valore che indica se la collezione di oggetti presunti contiene oggetti umani. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Imposta gli argomenti per l'algoritmo di segmentazione. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Imposta gli oggetti presunti. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Imposta il colore di sostituzione dello sfondo. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Imposta un valore che indica se i tratti predefiniti devono essere calcolati. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | Il rettangolo degli oggetti combinati. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Imposta un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | I tratti di sfondo predefiniti. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | I tratti di primo piano pre-calcolati predefiniti. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | I rettangoli degli oggetti predefiniti. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Imposta le opzioni di esportazione dell'immagine. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Imposta il raggio di sfumatura. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Un valore che indica se la collezione di oggetti presunti contiene oggetti umani. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Imposta l'area di mascheramento. |
| [setMethod(int value)](#setMethod-int-) | Imposta il metodo di segmentazione. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Imposta il gestore dell'evento di avanzamento del processo di pre-calcolo dei punti predefiniti. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Inizializza una nuova istanza della classe [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions).

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Il numero dell'oggetto di sfondo

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Aggiungi argomenti di auto mascheramento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Riempire i tratti predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Ottiene gli argomenti per l'algoritmo di segmentazione.

Valore: Gli argomenti per l'algoritmo di segmentazione.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Ottiene gli oggetti presunti.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - gli oggetti presunti.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Ottiene il colore di sostituzione dello sfondo.

Valore: Il colore di sostituzione dello sfondo. Questo colore verrà utilizzato come colore di sfondo nelle immagini risultanti.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Ottiene un valore che indica se i tratti predefiniti devono essere calcolati.

**Returns:**
boolean - un valore che indica se i tratti predefiniti devono essere calcolati.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Ottiene il rettangolo degli oggetti combinati.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Ottiene un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo.

Valore:  true  se decomporre; altrimenti,  false .

**Returns:**
boolean - un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Ottiene i tratti di sfondo predefiniti.

**Returns:**
com.aspose.psd.Point[] - i tratti di sfondo predefiniti.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Ottiene i tratti di primo piano predefiniti pre‑calcolati.

**Returns:**
com.aspose.psd.Point[] - i tratti di primo piano predefiniti pre-calcolati.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Ottiene i rettangoli degli oggetti predefiniti.

**Returns:**
com.aspose.psd.Rectangle[] - i rettangoli degli oggetti predefiniti.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Ottiene le opzioni di esportazione dell'immagine.

Valore: Le opzioni di esportazione dell'immagine che saranno utilizzate per creare le immagini risultanti.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Ottiene il raggio di sfumatura.

**Returns:**
int - il raggio di sfumatura.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Ottiene l'area di mascheramento.

Valore: L'area di mascheramento che è un'area parziale dell'immagine di origine. Il valore Rectangle.Empty indica l'intera area dell'immagine di origine.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Ottiene il metodo di segmentazione.

Valore: Il metodo di segmentazione.

**Returns:**
int - il metodo di segmentazione.
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Ottiene il gestore dell'evento di avanzamento del processo di pre‑calcolo dei punti predefiniti.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Ottiene un valore che indica se la collezione di oggetti presunti contiene oggetti umani.

**Returns:**
boolean - un valore che indica se la collezione di oggetti presunti contiene oggetti umani.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Imposta gli argomenti per l'algoritmo di segmentazione.

Valore: Gli argomenti per l'algoritmo di segmentazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | gli argomenti per l'algoritmo di segmentazione. |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Imposta gli oggetti presunti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | gli oggetti presunti. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Imposta il colore di sostituzione dello sfondo.

Valore: Il colore di sostituzione dello sfondo. Questo colore verrà utilizzato come colore di sfondo nelle immagini risultanti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | il colore di sostituzione dello sfondo. |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Imposta un valore che indica se i tratti predefiniti devono essere calcolati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se i tratti predefiniti devono essere calcolati. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


Il rettangolo degli oggetti combinati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | il rettangolo combinato degli oggetti. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Imposta un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo.

Valore:  true  se decomporre; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se è inutile separare ogni Shape dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo. |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


I tratti di sfondo predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | i tratti di sfondo predefiniti. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


I tratti di primo piano pre-calcolati predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | i tratti di primo piano predefiniti pre-calcolati. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


I rettangoli degli oggetti predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | i rettangoli degli oggetti predefiniti. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Imposta le opzioni di esportazione dell'immagine.

Valore: Le opzioni di esportazione dell'immagine che saranno utilizzate per creare le immagini risultanti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | le opzioni di esportazione dell'immagine. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Imposta il raggio di sfumatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il raggio di sfumatura. |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Un valore che indica se la collezione di oggetti presunti contiene oggetti umani.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se la collezione di oggetti presunti contiene oggetti umani. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Imposta l'area di mascheramento.

Valore: L'area di mascheramento che è un'area parziale dell'immagine di origine. Il valore Rectangle.Empty indica l'intera area dell'immagine di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | l'area di mascheramento. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Imposta il metodo di segmentazione.

Valore: Il metodo di segmentazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il metodo di segmentazione. |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Imposta il gestore dell'evento di avanzamento del processo di pre-calcolo dei punti predefiniti.

Valore: Il gestore dell'evento di avanzamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | il gestore dell'evento di avanzamento del processo di pre-calcolo dei punti predefiniti. |

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

