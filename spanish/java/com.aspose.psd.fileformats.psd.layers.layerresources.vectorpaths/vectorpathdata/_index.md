---
title: "VectorPathData"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La clase para trabajar con una ruta vectorial."
type: docs
weight: 18
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

La clase para trabajar con una ruta vectorial.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Inicializa una nueva instancia de la clase [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
| [VectorPathData()](#VectorPathData--) | Inicializa una nueva instancia de la clase [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
## Campos

| Campo | Descripción |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | El tamaño de la información general como versión y banderas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Obtiene como matriz de bytes. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtiene la longitud de los datos de ruta vectorial en el recurso en bytes. |
| [getPaths()](#getPaths--) | Obtiene o establece los registros de ruta. |
| [getVersion()](#getVersion--) | Obtiene o establece la versión. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Obtiene o establece un valor que indica si esta instancia está deshabilitada. |
| [isInverted()](#isInverted--) | Obtiene o establece un valor que indica si esta instancia está invertida. |
| [isNotLinked()](#isNotLinked--) | Obtiene o establece un valor que indica si esta instancia no está vinculada. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Obtiene o establece un valor que indica si esta instancia está deshabilitada. |
| [setInverted(boolean value)](#setInverted-boolean-) | Obtiene o establece un valor que indica si esta instancia está invertida. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Obtiene o establece un valor que indica si esta instancia no está vinculada. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Obtiene o establece los registros de ruta. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece la versión. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Inicializa una nueva instancia de la clase [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos del recurso. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Inicializa una nueva instancia de la clase [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


El tamaño de la información general como versión y banderas.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Obtiene como matriz de bytes.

**Returns:**
byte[] - El recurso como matriz de bytes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Obtiene la longitud de los datos de ruta vectorial en el recurso en bytes.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Obtiene o establece los registros de ruta.

Valor: Las rutas.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtiene o establece la versión.

Valor: La versión.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Obtiene o establece un valor que indica si esta instancia está deshabilitada.

Valor:  true  si esta instancia está deshabilitada; de lo contrario,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Obtiene o establece un valor que indica si esta instancia está invertida.

Valor:  true  si esta instancia está invertida; de lo contrario,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Obtiene o establece un valor que indica si esta instancia no está vinculada.

Valor:  true  si esta instancia no está vinculada; de lo contrario,  false .

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Obtiene o establece un valor que indica si esta instancia está deshabilitada.

Valor:  true  si esta instancia está deshabilitada; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Obtiene o establece un valor que indica si esta instancia está invertida.

Valor:  true  si esta instancia está invertida; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Obtiene o establece un valor que indica si esta instancia no está vinculada.

Valor:  true  si esta instancia no está vinculada; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Obtiene o establece los registros de ruta.

Valor: Las rutas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Obtiene o establece la versión.

Valor: La versión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

