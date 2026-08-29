---
title: "CurvesDiscreteManager"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Administrador para Curves Adjustment Layer que manipula el mapa de píxeles"
type: docs
weight: 25
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Administrador de la capa de ajuste Curves que manipula el mapa de píxeles
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Inicializa una nueva instancia de la clase [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Obtiene los bytes del recurso. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Obtiene el mapa para el filtro de procesamiento |
| [getMaxChannelCount()](#getMaxChannelCount--) | Obtiene la cantidad máxima de canales. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Obtiene el valor en la posición. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Carga datos desde bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Establece el valor predeterminado en la posición. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Establece el valor en la posición. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Establece el valor de todo el canal. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Inicializa una nueva instancia de la clase [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxChannelCount | int | La cantidad máxima de canales. |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Obtiene el mapa para el filtro de procesamiento

**Returns:**
byte[][] - mapa de transformación
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Obtiene la cantidad máxima de canales.

Valor: la cantidad máxima de canales.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Obtiene el valor en la posición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |
| position | byte | La posición. |

**Returns:**
byte - Valor de la curva por su posición
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Establece el valor predeterminado en la posición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |
| position | byte | La posición. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Establece el valor en la posición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |
| position | byte | La posición. |
| valor | byte | El valor. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Establece el valor de todo el canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| channelIndex | int | Índice del canal. |
| channelValue | byte[] | El valor del canal. |

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

