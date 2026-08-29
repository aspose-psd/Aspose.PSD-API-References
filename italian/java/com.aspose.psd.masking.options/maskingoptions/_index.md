---
title: "MaskingOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta le opzioni comuni di mascheramento dell'immagine."
type: docs
weight: 16
url: /it/java/com.aspose.psd.masking.options/maskingoptions/
---

**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Rappresenta le opzioni comuni di mascheramento dell'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Il numero dell'oggetto di sfondo |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Ottiene gli argomenti per l'algoritmo di segmentazione. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Ottiene il colore di sostituzione dello sfondo. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Ottiene un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo. |
| [getExportOptions()](#getExportOptions--) | Ottiene le opzioni di esportazione dell'immagine. |
| [getMaskingArea()](#getMaskingArea--) | Ottiene l'area di mascheramento. |
| [getMethod()](#getMethod--) | Ottiene il metodo di segmentazione. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Imposta gli argomenti per l'algoritmo di segmentazione. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Imposta il colore di sostituzione dello sfondo. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Imposta un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Imposta le opzioni di esportazione dell'immagine. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Imposta l'area di mascheramento. |
| [setMethod(int value)](#setMethod-int-) | Imposta il metodo di segmentazione. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Il numero dell'oggetto di sfondo

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Ottiene gli argomenti per l'algoritmo di segmentazione.

Valore: Gli argomenti per l'algoritmo di segmentazione.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Ottiene il colore di sostituzione dello sfondo.

Valore: Il colore di sostituzione dello sfondo. Questo colore verrà utilizzato come colore di sfondo nelle immagini risultanti.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Ottiene un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo.

Valore:  true  se decomporre; altrimenti,  false .

**Returns:**
boolean - un valore che indica se è inutile separare ogni Forma dalla maschera come oggetto individuale o come oggetto unito dalla maschera separato dallo sfondo.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Ottiene le opzioni di esportazione dell'immagine.

Valore: Le opzioni di esportazione dell'immagine che saranno utilizzate per creare le immagini risultanti.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
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

