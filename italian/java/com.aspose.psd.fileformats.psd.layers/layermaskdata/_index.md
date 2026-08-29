---
title: "LayerMaskData"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce la classe base LayerMaskData che contiene informazioni sui dati della maschera del livello nel file PSD."
type: docs
weight: 21
url: /it/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

Definisce la classe base LayerMaskData che contiene informazioni sui dati della maschera di livello nel file PSD. Può aiutare a modificare i file Adobe\ufffd Photoshop\ufffd programmaticamente e ad automatizzare la modifica del formato PSD. Se il livello ha solo una maschera raster, l'ImageData contiene i byte dei dati della maschera raster. Se il livello ha solo una maschera vettoriale, l'ImageData contiene i byte dei dati della maschera vettoriale rasterizzata (memorizzata nella cache). Se il livello ha sia maschere raster che vettoriali, l'ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. La lunghezza in byte dell'ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) dovrebbe essere uguale a Larghezza \* Altezza di MaskRectangle ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) proprietà. Nota che rimuovere / aggiungere / aggiornare semplicemente il LayerMaskData non è sufficiente per un salvataggio corretto perché i canali non vengono aggiornati; tuttavia può fornire un rendering corretto. Il metodo [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\#addLayerMask-LayerMaskData-) dovrebbe essere usato per questo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Clona la maschera di livello. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Ottiene o imposta la posizione inferiore della maschera di livello. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Ottiene la dimensione dei dati della maschera di livello. |
| [getDefaultColor()](#getDefaultColor--) | Ottiene o imposta il colore predefinito. |
| [getFlags()](#getFlags--) | Ottiene o imposta le flag della maschera di livello. |
| [getHeight_internalized()](#getHeight-internalized--) | Ottiene l'altezza della maschera. |
| [getImageData()](#getImageData--) | Ottiene o imposta i dati della maschera di livello (o la maschera combinata / finale se è presente una maschera vettoriale) nel file PSD. |
| [getLeft()](#getLeft--) | Ottiene o imposta la posizione sinistra della maschera di livello. |
| [getMaskRectangle()](#getMaskRectangle--) | Ottiene o imposta il rettangolo della maschera del livello nel file PSD. |
| [getRight()](#getRight--) | Ottiene o imposta la posizione destra della maschera di livello. |
| [getTop()](#getTop--) | Ottiene o imposta la posizione superiore della maschera di livello. |
| [getWidth_internalized()](#getWidth-internalized--) | Ottiene la larghezza della maschera. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Salva [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) nel StreamContainer specificato. |
| [setBottom(int value)](#setBottom-int-) | Ottiene o imposta la posizione inferiore della maschera di livello. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Ottiene o imposta il colore predefinito. |
| [setFlags(byte value)](#setFlags-byte-) | Ottiene o imposta le flag della maschera di livello. |
| [setImageData(byte[] value)](#setImageData-byte---) | Ottiene o imposta i dati della maschera di livello (o la maschera combinata / finale se è presente una maschera vettoriale) nel file PSD. |
| [setLeft(int value)](#setLeft-int-) | Ottiene o imposta la posizione sinistra della maschera di livello. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Ottiene o imposta il rettangolo della maschera del livello nel file PSD. |
| [setRight(int value)](#setRight-int-) | Ottiene o imposta la posizione destra della maschera di livello. |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta la posizione superiore della maschera di livello. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Clona questa istanza.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Clona la maschera di livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | La maschera. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Ottiene o imposta la posizione inferiore della maschera di livello.

Valore: La posizione inferiore della maschera di livello.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Ottiene la dimensione dei dati della maschera di livello.

Valore: La dimensione dei dati della maschera del livello.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Ottiene o imposta il colore predefinito.

Valore: Il colore predefinito.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Ottiene o imposta le flag della maschera di livello.

Valore: I flag della maschera del livello.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Ottiene l'altezza della maschera.

Valore: L'altezza.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ottiene o imposta i dati della maschera di livello (o la maschera combinata / finale se è presente una maschera vettoriale) nel file PSD.

Valore: I dati dell'immagine.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ottiene o imposta la posizione sinistra della maschera di livello.

Valore: La posizione sinistra della maschera del livello.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Ottiene o imposta il rettangolo della maschera del livello nel file PSD. Accetta le proprietà sinistra, destra, superiore e inferiore e crea Rectangle

Valore: Il rettangolo della maschera.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRight() {#getRight--}
```
public final int getRight()
```


Ottiene o imposta la posizione destra della maschera di livello.

Valore: La posizione destra della maschera del livello.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Ottiene o imposta la posizione superiore della maschera di livello.

Valore: La posizione superiore della maschera del livello.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Ottiene la larghezza della maschera.

Valore: La larghezza.

**Returns:**
int
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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public abstract void save_internalized(StreamContainer streamContainer)
```


Salva [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) nel StreamContainer specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare i dati. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Ottiene o imposta la posizione inferiore della maschera di livello.

Valore: La posizione inferiore della maschera di livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Ottiene o imposta il colore predefinito.

Valore: Il colore predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Ottiene o imposta le flag della maschera di livello.

Valore: I flag della maschera del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Ottiene o imposta i dati della maschera di livello (o la maschera combinata / finale se è presente una maschera vettoriale) nel file PSD.

Valore: I dati dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ottiene o imposta la posizione sinistra della maschera di livello.

Valore: La posizione sinistra della maschera del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Ottiene o imposta il rettangolo della maschera del livello nel file PSD. Accetta le proprietà sinistra, destra, superiore e inferiore e crea Rectangle

Valore: Il rettangolo della maschera.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Ottiene o imposta la posizione destra della maschera di livello.

Valore: La posizione destra della maschera del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ottiene o imposta la posizione superiore della maschera di livello.

Valore: La posizione superiore della maschera del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

