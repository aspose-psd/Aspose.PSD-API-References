---
title: "CurvesDiscreteManager"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Gestore per Curves Adjustment Layer che manipola la mappa dei pixel"
type: docs
weight: 25
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Gestore per il livello di regolazione Curve che manipola la mappa dei pixel
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Inizializza una nuova istanza della classe [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Ottiene i byte per la risorsa. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Ottiene la mappa per l'elaborazione del filtro |
| [getMaxChannelCount()](#getMaxChannelCount--) | Ottiene il conteggio massimo dei canali. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Ottiene il valore nella posizione. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Carica i dati dai byte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Imposta al valore predefinito nella posizione. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Imposta il valore nella posizione. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Imposta il valore dell'intero canale. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Inizializza una nuova istanza della classe [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxChannelCount | int | Il conteggio massimo dei canali. |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Ottiene la mappa per l'elaborazione del filtro

**Returns:**
byte[][] - mappa di trasformazione
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Ottiene il conteggio massimo dei canali.

Valore: Il conteggio massimo dei canali.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Ottiene il valore nella posizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |
| position | byte | La posizione. |

**Returns:**
byte - Valore della curva per la sua posizione
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Imposta al valore predefinito nella posizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |
| position | byte | La posizione. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Imposta il valore nella posizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |
| position | byte | La posizione. |
| valore | byte | Il valore. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Imposta il valore dell'intero canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelIndex | int | Indice del canale. |
| channelValue | byte[] | Il valore del canale. |

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

