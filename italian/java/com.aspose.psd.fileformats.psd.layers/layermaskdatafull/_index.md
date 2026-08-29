---
title: "LayerMaskDataFull"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce la classe LayerMaskDataFull che contiene informazioni sui dati della maschera nel livello del file PSD quando il livello ha sia maschere di livello che vettoriali."
type: docs
weight: 22
url: /it/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Definisce la classe LayerMaskDataFull che contiene informazioni sui dati della maschera nel livello del file PSD quando il livello ha sia maschere di livello che maschere vettoriali. In caso contrario, viene utilizzato un [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). L'ImageData contiene la maschera raster e la maschera vettoriale rasterizzata combinate. La lunghezza in byte di ImageData dovrebbe essere uguale alle proprietà MaskRectangle.Width \* MaskRectangle.Height.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Inizializza una nuova istanza della classe [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Clona la maschera di livello. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene o imposta il colore di sfondo. |
| [getBottom()](#getBottom--) | Ottiene o imposta la posizione inferiore della maschera di livello. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Ottiene la dimensione dei dati della maschera di livello. |
| [getDefaultColor()](#getDefaultColor--) | Ottiene o imposta il colore predefinito. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Ottiene o imposta la posizione inferiore della maschera raster nel livello immagine PSD. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Ottiene o imposta la posizione sinistra della maschera raster nel livello file PSD. |
| [getEnclosingRight()](#getEnclosingRight--) | Ottiene o imposta la posizione destra della maschera raster nel livello file PSD. |
| [getEnclosingTop()](#getEnclosingTop--) | Ottiene o imposta la posizione superiore della maschera raster nel livello immagine PSD. |
| [getFlags()](#getFlags--) | Ottiene o imposta le flag della maschera di livello. |
| [getHeight_internalized()](#getHeight-internalized--) | Ottiene l'altezza della maschera. |
| [getImageData()](#getImageData--) | Ottiene o imposta i dati della maschera di livello (o la maschera combinata / finale se è presente una maschera vettoriale) nel file PSD. |
| [getLeft()](#getLeft--) | Ottiene o imposta la posizione sinistra della maschera di livello. |
| [getMaskRectangle()](#getMaskRectangle--) | Ottiene o imposta il rettangolo della maschera del livello nel file PSD. |
| [getRealFlags()](#getRealFlags--) | Ottiene o imposta i flag della maschera di livello utilizzati per la maschera utente / raster. |
| [getRight()](#getRight--) | Ottiene o imposta la posizione destra della maschera di livello. |
| [getTop()](#getTop--) | Ottiene o imposta la posizione superiore della maschera di livello. |
| [getUserMaskData()](#getUserMaskData--) | Ottiene o imposta i dati della maschera utente (raster) di un livello nel file PSD. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Ottiene o imposta il rettangolo della maschera utente (contenitore) nel livello immagine PSD. |
| [getWidth_internalized()](#getWidth-internalized--) | Ottiene la larghezza della maschera. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Salva [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) nel StreamContainer specificato. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Ottiene o imposta il colore di sfondo. |
| [setBottom(int value)](#setBottom-int-) | Ottiene o imposta la posizione inferiore della maschera di livello. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Ottiene o imposta il colore predefinito. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Ottiene o imposta la posizione inferiore della maschera raster nel livello immagine PSD. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Ottiene o imposta la posizione sinistra della maschera raster nel livello file PSD. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Ottiene o imposta la posizione destra della maschera raster nel livello file PSD. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Ottiene o imposta la posizione superiore della maschera raster nel livello immagine PSD. |
| [setFlags(byte value)](#setFlags-byte-) | Ottiene o imposta le flag della maschera di livello. |
| [setImageData(byte[] value)](#setImageData-byte---) | Ottiene o imposta i dati della maschera di livello (o la maschera combinata / finale se è presente una maschera vettoriale) nel file PSD. |
| [setLeft(int value)](#setLeft-int-) | Ottiene o imposta la posizione sinistra della maschera di livello. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Ottiene o imposta il rettangolo della maschera del livello nel file PSD. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Ottiene o imposta i flag della maschera di livello utilizzati per la maschera utente / raster. |
| [setRight(int value)](#setRight-int-) | Ottiene o imposta la posizione destra della maschera di livello. |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta la posizione superiore della maschera di livello. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Ottiene o imposta i dati della maschera utente (raster) di un livello nel file PSD. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Ottiene o imposta il rettangolo della maschera utente (contenitore) nel livello immagine PSD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Inizializza una nuova istanza della classe [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull).

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Ottiene o imposta il colore di sfondo.

Valore: Il colore di sfondo.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Ottiene o imposta la posizione inferiore della maschera raster nel livello immagine PSD.

Valore: La posizione inferiore della maschera di livello.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Ottiene o imposta la posizione sinistra della maschera raster nel livello file PSD.

Valore: La posizione sinistra della maschera del livello.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Ottiene o imposta la posizione destra della maschera raster nel livello file PSD.

Valore: La posizione destra della maschera del livello.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Ottiene o imposta la posizione superiore della maschera raster nel livello immagine PSD.

Valore: La posizione superiore della maschera del livello.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Ottiene o imposta i flag della maschera di livello utilizzati per la maschera utente / raster. Per la maschera vettoriale viene utilizzata la proprietà Flags.

Valore: I flag reali della maschera di livello.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Ottiene o imposta i dati della maschera utente (raster) di un livello nel file PSD. (Esiste una maschera vettoriale rasterizzata nella proprietà MaskData).

Valore: I dati immagine del livello nell'immagine PSD.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Ottiene o imposta il rettangolo della maschera utente (contenitore) nel livello immagine PSD.

Valore: Il rettangolo della maschera utente.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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
public void save_internalized(StreamContainer streamContainer)
```


Salva [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) nel StreamContainer specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare i dati. |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Ottiene o imposta il colore di sfondo.

Valore: Il colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Ottiene o imposta la posizione inferiore della maschera raster nel livello immagine PSD.

Valore: La posizione inferiore della maschera di livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Ottiene o imposta la posizione sinistra della maschera raster nel livello file PSD.

Valore: La posizione sinistra della maschera del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Ottiene o imposta la posizione destra della maschera raster nel livello file PSD.

Valore: La posizione destra della maschera del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Ottiene o imposta la posizione superiore della maschera raster nel livello immagine PSD.

Valore: La posizione superiore della maschera del livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Ottiene o imposta i flag della maschera di livello utilizzati per la maschera utente / raster. Per la maschera vettoriale viene utilizzata la proprietà Flags.

Valore: I flag reali della maschera di livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Ottiene o imposta i dati della maschera utente (raster) di un livello nel file PSD. (Esiste una maschera vettoriale rasterizzata nella proprietà MaskData).

Valore: I dati immagine del livello nell'immagine PSD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Ottiene o imposta il rettangolo della maschera utente (contenitore) nel livello immagine PSD.

Valore: Il rettangolo della maschera utente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

