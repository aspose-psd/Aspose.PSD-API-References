---
title: "AiLayerSection"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La sezione di livello del formato Ai"
type: docs
weight: 15
url: /it/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

La sezione di livello del formato Ai
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Aggiunge l'immagine raster. |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Ottiene o imposta il componente di colore blu. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Ottiene o imposta l'indice del colore. |
| [getColorNumber()](#getColorNumber--) | Ottiene o imposta il numero del colore. |
| [getData()](#getData--) | Ottiene i dati della stringa. |
| [getDimValue()](#getDimValue--) | Ottiene o imposta il valore di attenuazione come percentuale. |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getGreen()](#getGreen--) | Ottiene o imposta il componente di colore verde. |
| [getName()](#getName--) | Ottiene o imposta il nome del livello. |
| [getRasterImages()](#getRasterImages--) | Ottiene le immagini raster. |
| [getRed()](#getRed--) | Ottiene o imposta il componente di colore rosso. |
| [getStream_internalized()](#getStream-internalized--) | Ottiene lo stream interno |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Ottiene o imposta un valore che indica se questa istanza ha maschere multistrato. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Ottiene o imposta un valore che indica se questo livello è attenuato. |
| [isLocked()](#isLocked--) | Ottiene o imposta un valore che indica se questo livello è bloccato. |
| [isPreview()](#isPreview--) | Ottiene o imposta un valore che indica se questo livello è in anteprima. |
| [isPrinted()](#isPrinted--) | Ottiene o imposta un valore che indica se questo livello è stampato. |
| [isShown()](#isShown--) | Ottiene o imposta un valore che indica se questo livello è mostrato. |
| [isTemplate()](#isTemplate--) | Ottiene o imposta un valore che indica se questo livello è un livello modello. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Ottiene o imposta il componente di colore blu. |
| [setColorIndex(int value)](#setColorIndex-int-) | Ottiene o imposta l'indice del colore. |
| [setColorNumber(int value)](#setColorNumber-int-) | Ottiene o imposta il numero del colore. |
| [setDimValue(int value)](#setDimValue-int-) | Ottiene o imposta il valore di attenuazione come percentuale. |
| [setGreen(int value)](#setGreen-int-) | Ottiene o imposta il componente di colore verde. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Ottiene o imposta un valore che indica se questo livello è attenuato. |
| [setLocked(boolean value)](#setLocked-boolean-) | Ottiene o imposta un valore che indica se questo livello è bloccato. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Ottiene o imposta un valore che indica se questa istanza ha maschere multistrato. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome del livello. |
| [setPreview(boolean value)](#setPreview-boolean-) | Ottiene o imposta un valore che indica se questo livello è in anteprima. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Ottiene o imposta un valore che indica se questo livello è stampato. |
| [setRed(int value)](#setRed-int-) | Ottiene o imposta il componente di colore rosso. |
| [setShown(boolean value)](#setShown-boolean-) | Ottiene o imposta un valore che indica se questo livello è mostrato. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Ottiene o imposta un valore che indica se questo livello è un livello modello. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Aggiunge l'immagine raster.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | L'immagine raster. |

### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |
| proprietà | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Ottiene o imposta il componente di colore blu.

Valore: Il componente di colore blu.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Ottiene o imposta l'indice del colore. Questo argomento può assumere valori compresi tra \\u20131 e 26. Ogni intero rappresenta un colore che può essere assegnato al livello per scopi di identificazione dell'utente.

Valore: L'indice del colore.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Ottiene o imposta il numero del colore. -1 è il valore del colore personalizzato dalle proprietà Rosso, Verde, Blu. Specifica l'impostazione del colore del livello\\u2019s.

Valore: Il numero del colore.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Ottiene i dati della stringa.

**Returns:**
java.lang.String - I dati della stringa della sezione
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Ottiene o imposta il valore di attenuazione in percentuale. Riduce l'intensità delle immagini collegate e delle immagini bitmap contenute nel livello alla percentuale specificata.

Valore: Il valore di attenuazione in percentuale.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Ottiene o imposta il componente di colore verde.

Valore: Il componente di colore verde.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Ottiene o imposta il nome del livello. Specifica il nome dell'elemento come appare nel pannello Livelli.

Valore: Il nome del livello.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Ottiene le immagini raster.

Valore: Le immagini raster.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Ottiene o imposta il componente di colore rosso.

Valore: Il componente di colore rosso.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Ottiene lo stream interno

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Ottiene o imposta un valore che indica se questa istanza ha maschere multistrato.

Valore:  true  se questa istanza ha maschere multistrato; altrimenti,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Ottiene o imposta un valore che indica se questo livello è attenuato. Riduce l'intensità delle immagini collegate e delle immagini bitmap contenute nel livello.

Valore:  true  se questo livello è attenuato; altrimenti,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Ottiene o imposta un valore che indica se questo livello è bloccato. Impedisce modifiche all'elemento.

Valore:  true  se questo livello è bloccato; altrimenti,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Ottiene o imposta un valore che indica se questo livello è in anteprima. Visualizza l'opera contenuta nel livello a colori invece che come contorni.

Valore:  true  se questo livello è in anteprima; altrimenti,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Ottiene o imposta un valore che indica se questo livello è stampato. Rende l'opera contenuta nel livello stampabile se true.

Valore:  true  se questo livello è stampato; altrimenti,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Ottiene o imposta un valore che indica se questo livello è visibile. Visualizza tutta l'opera contenuta nel livello sulla tavola da disegno se true.

Valore:  true  se questo livello è visibile; altrimenti,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Ottiene o imposta un valore che indica se questo livello è un livello modello.

Valore:  true  se questo livello è un modello; altrimenti,  false .

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Ottiene o imposta il componente di colore blu.

Valore: Il componente di colore blu.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Ottiene o imposta l'indice del colore. Questo argomento può assumere valori compresi tra \\u20131 e 26. Ogni intero rappresenta un colore che può essere assegnato al livello per scopi di identificazione dell'utente.

Valore: L'indice del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Ottiene o imposta il numero del colore. -1 è il valore del colore personalizzato dalle proprietà Rosso, Verde, Blu. Specifica l'impostazione del colore del livello\\u2019s.

Valore: Il numero del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Ottiene o imposta il valore di attenuazione in percentuale. Riduce l'intensità delle immagini collegate e delle immagini bitmap contenute nel livello alla percentuale specificata.

Valore: Il valore di attenuazione in percentuale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Ottiene o imposta il componente di colore verde.

Valore: Il componente di colore verde.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Ottiene o imposta un valore che indica se questo livello è attenuato. Riduce l'intensità delle immagini collegate e delle immagini bitmap contenute nel livello.

Valore:  true  se questo livello è attenuato; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Ottiene o imposta un valore che indica se questo livello è bloccato. Impedisce modifiche all'elemento.

Valore:  true  se questo livello è bloccato; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza ha maschere multistrato.

Valore:  true  se questa istanza ha maschere multistrato; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ottiene o imposta il nome del livello. Specifica il nome dell'elemento come appare nel pannello Livelli.

Valore: Il nome del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Ottiene o imposta un valore che indica se questo livello è in anteprima. Visualizza l'opera contenuta nel livello a colori invece che come contorni.

Valore:  true  se questo livello è in anteprima; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Ottiene o imposta un valore che indica se questo livello è stampato. Rende l'opera contenuta nel livello stampabile se true.

Valore:  true  se questo livello è stampato; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Ottiene o imposta il componente di colore rosso.

Valore: Il componente di colore rosso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Ottiene o imposta un valore che indica se questo livello è visibile. Visualizza tutta l'opera contenuta nel livello sulla tavola da disegno se true.

Valore:  true  se questo livello è visibile; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Ottiene o imposta un valore che indica se questo livello è un livello modello.

Valore:  true  se questo livello è un modello; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

