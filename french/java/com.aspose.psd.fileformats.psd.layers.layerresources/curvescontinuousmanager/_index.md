---
title: "CurvesContinuousManager"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Gestionnaire du calque d'ajustement des courbes qui manipule les courbes"
type: docs
weight: 24
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Gestionnaire du calque d'ajustement des courbes qui manipule les courbes
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Initialise une nouvelle instance de la classe [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Ajoute le point de la courbe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Obtient les octets pour la ressource. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Obtient le point de la courbe par indice. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Obtient le nombre de points de la courbe. |
| [getMap_internalized()](#getMap-internalized--) | Obtient la carte pour le filtre de traitement. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Obtient le nombre maximal de canaux. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Charge les données depuis les octets. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Supprime le point de la courbe. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Met à jour le point de la courbe. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Initialise une nouvelle instance de la classe [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxChannelCount | int | Le nombre maximal de canaux. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Ajoute le point de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |
| x | byte | La position x. |
| y | byte | La position y. |

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
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


Obtient le point de la courbe par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |
| pointIndex | int | Indice du point. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Obtient le nombre de points de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |

**Returns:**
int - Nombre de points de courbe dans le canal
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Obtient la carte pour le filtre de traitement.

**Returns:**
byte[][] - Carte pour le traitement du canal.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Obtient le nombre maximal de canaux.

Valeur : Le nombre maximal de canaux.

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




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


Supprime le point de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |
| pointIndex | int | Indice du point. |

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


Met à jour le point de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelIndex | int | Indice du canal. |
| pointIndex | int | Indice du point. |
| x | byte | La position x. |
| y | byte | La position y. |

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

