---
title: "LayerStateInformationResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Recurso de información del estado de la capa"
type: docs
weight: 28
url: /es/java/com.aspose.psd.fileformats.psd.resources/layerstateinformationresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class LayerStateInformationResource extends ResourceBlock
```

Recurso de información del estado de la capa
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LayerStateInformationResource()](#LayerStateInformationResource--) | Inicializa una nueva instancia de la clase [LayerStateInformationResource](../../com.aspose.psd.fileformats.psd.resources/layerstateinformationresource). |
## Campos

| Campo | Descripción |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | La firma del recurso de ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | La firma regular del recurso de Photoshop. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Obtiene el tamaño de los datos del recurso en bytes. |
| [getID()](#getID--) | Obtiene o establece el identificador único del recurso. |
| [getLayerIndex()](#getLayerIndex--) | Obtiene o establece el índice de la capa. |
| [getMinimalVersion()](#getMinimalVersion--) | Obtiene la versión mínima requerida de PSD. |
| [getName()](#getName--) | Obtiene o establece el nombre del recurso. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso. |
| [getSize()](#getSize--) | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Guarda el bloque de recurso en el flujo especificado. |
| [setID(short value)](#setID-short-) | Obtiene o establece el identificador único del recurso. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtiene o establece la información de capa y máscara. |
| [setLayerIndex(short value)](#setLayerIndex-short-) | Obtiene o establece el índice de la capa. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre del recurso. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtiene o establece el estado del bloque de recurso. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valida los valores del recurso. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerStateInformationResource() {#LayerStateInformationResource--}
```
public LayerStateInformationResource()
```


Inicializa una nueva instancia de la clase [LayerStateInformationResource](../../com.aspose.psd.fileformats.psd.resources/layerstateinformationresource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


La firma del recurso de ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


La firma regular del recurso de Photoshop.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtiene el tamaño de los datos del recurso en bytes.

Valor: El tamaño de los datos del recurso.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Obtiene o establece el identificador único del recurso.

Valor: El identificador único del recurso.

**Returns:**
short
### getLayerIndex() {#getLayerIndex--}
```
public final short getLayerIndex()
```


Obtiene o establece el índice de la capa.

Valor: El índice de la capa.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Obtiene la versión mínima requerida de PSD.

Valor: La versión mínima de PSD.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consiste en dos bytes de 0).

Valor: El nombre del recurso.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Obtiene la firma del recurso. Debe ser siempre '8BIM'.

Valor: La firma del recurso.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos.

Valor: El tamaño del bloque de recurso.

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Guarda el bloque de recurso en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | El flujo donde guardar el bloque de recurso. |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Obtiene o establece el identificador único del recurso.

Valor: El identificador único del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Obtiene o establece la información de capa y máscara.

Valor: La información de capa y máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setLayerIndex(short value) {#setLayerIndex-short-}
```
public final void setLayerIndex(short value)
```


Obtiene o establece el índice de la capa.

Valor: El índice de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consiste en dos bytes de 0).

Valor: El nombre del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firma | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Obtiene o establece el estado del bloque de recurso.

Valor: El estado del bloque de recurso.

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
### validateValues() {#validateValues--}
```
public void validateValues()
```


Valida los valores del recurso.

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

