---
title: "CurvesContinuousManager"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Gestore per il livello di regolazione Curve che manipola le curve"
type: docs
weight: 24
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Gestore per il livello di regolazione Curve che manipola le curve
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Inizializza una nuova istanza della classe [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Aggiunge il punto della curva. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Ottiene i byte per la risorsa. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Ottiene il punto della curva per indice. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Ottiene il conteggio dei punti della curva. |
| [getMap_internalized()](#getMap-internalized--) | Ottiene la mappa per il filtro di elaborazione. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Ottiene il conteggio massimo dei canali. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Carica i dati dai byte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Rimuove il punto della curva. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Aggiorna il punto della curva. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Inizializza una nuova istanza della classe [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxChannelCount | int | Il conteggio massimo dei canali. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Aggiunge il punto della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |
| x | byte | La posizione x. |
| y | byte | La posizione y. |

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
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Ottiene i byte per la risorsa.

**Returns:**
byte[] - Byte per comporre CurvResource
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


Ottiene il punto della curva per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |
| pointIndex | int | Indice del punto. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Ottiene il conteggio dei punti della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |

**Returns:**
int - Conteggio di Curve Point nel canale
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Ottiene la mappa per il filtro di elaborazione.

**Returns:**
byte[][] - Mappa per l'elaborazione del canale.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Ottiene il conteggio massimo dei canali.

Valore: Il conteggio massimo dei canali.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadFromBytes_internalized(byte[] bytes) {#loadFromBytes-internalized-byte---}
```
public void loadFromBytes_internalized(byte[] bytes)
```


Carica i dati dai byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| byte | byte[] | I byte. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


Rimuove il punto della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |
| pointIndex | int | Indice del punto. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y) {#updateCurvePoint-int-int-byte-byte-}
```
public final void updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)
```


Aggiorna il punto della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |
| pointIndex | int | Indice del punto. |
| x | byte | La posizione x. |
| y | byte | La posizione y. |

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

