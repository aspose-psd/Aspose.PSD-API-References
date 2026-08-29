---
title: "CurvesContinuousManager"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Administrador de la capa de ajuste Curves que manipula curvas"
type: docs
weight: 24
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Administrador de la capa de ajuste Curves que manipula curvas
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Inicializa una nueva instancia de la clase [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager). |
## Métodos

| Método | Descripción |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Añade el punto de la curva. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Obtiene los bytes del recurso. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Obtiene el punto de la curva por índice. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Obtiene el recuento de puntos de la curva. |
| [getMap_internalized()](#getMap-internalized--) | Obtiene el mapa para el filtro de procesamiento. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Obtiene la cantidad máxima de canales. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Carga datos desde bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Elimina el punto de la curva. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Actualiza el punto de la curva. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Inicializa una nueva instancia de la clase [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxChannelCount | int | La cantidad máxima de canales. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Añade el punto de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |
| x | byte | La ubicación x. |
| y | byte | La ubicación y. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Obtiene los bytes del recurso.

**Returns:**
byte[] - Bytes para componer CurvResource
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


Obtiene el punto de la curva por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |
| pointIndex | int | Índice del punto. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Obtiene el recuento de puntos de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |

**Returns:**
int - Cantidad de puntos de curva en el canal
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Obtiene el mapa para el filtro de procesamiento.

**Returns:**
byte[][] - Mapa para el procesamiento del canal.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Obtiene la cantidad máxima de canales.

Valor: la cantidad máxima de canales.

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


Carga datos desde bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | byte[] | Los bytes. |

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


Elimina el punto de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |
| pointIndex | int | Índice del punto. |

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


Actualiza el punto de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |
| pointIndex | int | Índice del punto. |
| x | byte | La ubicación x. |
| y | byte | La ubicación y. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

