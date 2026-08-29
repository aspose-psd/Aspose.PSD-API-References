---
title: "PixelsData"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe per memorizzare i dati dei pixel dell'immagine e i suoi limiti."
type: docs
weight: 10
url: /it/java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

La classe per memorizzare i dati dei pixel dell'immagine e i suoi limiti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PixelsData()](#PixelsData--) | Inizializza una nuova istanza della classe [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | Inizializza una nuova istanza della classe [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | Crea l'istanza di PixelsDataLoader per l'istanza corrente di [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [createSaver_internalized()](#createSaver-internalized--) | Crea l'istanza di PixelsDataSaver per l'istanza corrente di [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [deepClone()](#deepClone--) | Crea una copia completa dell'istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti dei dati dei pixel. |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | Ottiene o imposta i dati dei pixel. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Ottiene o imposta i limiti dei dati dei pixel. |
| [setPixels(int[] value)](#setPixels-int---) | Ottiene o imposta i dati dei pixel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


Inizializza una nuova istanza della classe [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


Inizializza una nuova istanza della classe [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I dati dei pixel. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei limiti dei pixel. |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


Crea l'istanza di PixelsDataLoader per l'istanza corrente di [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


Crea l'istanza di PixelsDataSaver per l'istanza corrente di [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
com.aspose.internal.IPixelsSaver - La nuova istanza di PixelsDataSaver basata sull'istanza corrente di [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea una copia completa dell'istanza.

**Returns:**
java.lang.Object - La copia dell'istanza.
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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Ottiene o imposta i limiti dei dati dei pixel.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPixels() {#getPixels--}
```
public final int[] getPixels()
```


Ottiene o imposta i dati dei pixel.

**Returns:**
int[]
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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Ottiene o imposta i limiti dei dati dei pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


Ottiene o imposta i dati dei pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

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

