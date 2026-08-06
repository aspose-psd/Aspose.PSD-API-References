---
title: "CurvesDiscreteManager"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Gestionnaire pour le calque d'ajustement Curves qui manipule la carte des pixels"
type: docs
weight: 25
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Gestionnaire du calque d'ajustement des courbes qui manipule la carte des pixels
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Initialise une nouvelle instance de la classe [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Obtient les octets pour la ressource. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Obtient la carte pour le filtre de traitement. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Obtient le nombre maximal de canaux. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Obtient la valeur à la position. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Charge les données depuis les octets. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Définit la valeur par défaut à la position. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Définit la valeur à la position. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Définit la valeur de l'ensemble du canal. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Initialise une nouvelle instance de la classe [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxChannelCount | int | Le nombre maximal de canaux. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Obtient les octets pour la ressource.

**Returns:**
byte[] - Octets pour composer CurvResource
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


Obtient la carte pour le filtre de traitement.

**Returns:**
byte[][] - carte de transformation
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Obtient le nombre maximal de canaux.

Valeur : Le nombre maximal de canaux.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Obtient la valeur à la position.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |
| position | byte | La position. |

**Returns:**
byte - Valeur de la courbe selon sa position
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


Charge les données depuis les octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| octets | byte[] | Les octets. |

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


Définit la valeur par défaut à la position.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |
| position | byte | La position. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Définit la valeur à la position.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |
| position | byte | La position. |
| valeur | byte | La valeur. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Définit la valeur de l'ensemble du canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |
| channelValue | byte[] | La valeur du canal. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

