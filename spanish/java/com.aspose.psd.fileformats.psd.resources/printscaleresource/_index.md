---
title: "PrintScaleResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Recurso de escala de impresión"
type: docs
weight: 31
url: /es/java/com.aspose.psd.fileformats.psd.resources/printscaleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class PrintScaleResource extends ResourceBlock
```

Recurso de escala de impresión
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrintScaleResource()](#PrintScaleResource--) | Inicializa una nueva instancia de la clase [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource). |
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
| [getMinimalVersion()](#getMinimalVersion--) | Obtiene la versión mínima requerida de PSD. |
| [getName()](#getName--) | Obtiene o establece el nombre del recurso. |
| [getScale()](#getScale--) | Obtiene o establece la escala. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso. |
| [getSize()](#getSize--) | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| [getStyle()](#getStyle--) | Obtiene o establece el estilo. |
| [getXLocation()](#getXLocation--) | Obtiene o establece la ubicación x. |
| [getYLocation()](#getYLocation--) | Obtiene o establece la ubicación y. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Guarda el bloque de recurso en el flujo especificado. |
| [setID(short value)](#setID-short-) | Obtiene o establece el identificador único del recurso. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtiene o establece la información de capa y máscara. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre del recurso. |
| [setScale(float value)](#setScale-float-) | Obtiene o establece la escala. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtiene o establece el estado del bloque de recurso. |
| [setStyle(short value)](#setStyle-short-) | Obtiene o establece el estilo. |
| [setXLocation(float value)](#setXLocation-float-) | Obtiene o establece la ubicación x. |
| [setYLocation(float value)](#setYLocation-float-) | Obtiene o establece la ubicación y. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valida los valores del recurso. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintScaleResource() {#PrintScaleResource--}
```
public PrintScaleResource()
```


Inicializa una nueva instancia de la clase [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource).

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
### getScale() {#getScale--}
```
public final float getScale()
```


Obtiene o establece la escala.

Valor: La escala.

**Returns:**
float
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
### getStyle() {#getStyle--}
```
public final short getStyle()
```


Obtiene o establece el estilo.

Valor: El estilo.

**Returns:**
short
### getXLocation() {#getXLocation--}
```
public final float getXLocation()
```


Obtiene o establece la ubicación x.

Valor: La ubicación x.

**Returns:**
float
### getYLocation() {#getYLocation--}
```
public final float getYLocation()
```


Obtiene o establece la ubicación y.

Valor: La ubicación y.

**Returns:**
float
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

### setScale(float value) {#setScale-float-}
```
public final void setScale(float value)
```


Obtiene o establece la escala.

Valor: La escala.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

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

### setStyle(short value) {#setStyle-short-}
```
public final void setStyle(short value)
```


Obtiene o establece el estilo.

Valor: El estilo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setXLocation(float value) {#setXLocation-float-}
```
public final void setXLocation(float value)
```


Obtiene o establece la ubicación x.

Valor: La ubicación x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setYLocation(float value) {#setYLocation-float-}
```
public final void setYLocation(float value)
```


Obtiene o establece la ubicación y.

Valor: La ubicación y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

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

