---
title: "ResolutionInfoResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El recurso de información de resolución"
type: docs
weight: 33
url: /es/java/com.aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class ResolutionInfoResource extends ResourceBlock
```

El recurso de información de resolución
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ResolutionInfoResource()](#ResolutionInfoResource--) | Inicializa una nueva instancia de la clase [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource). |
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
| [getHDpi()](#getHDpi--) | DPI horizontal. |
| [getHResDisplayUnit()](#getHResDisplayUnit--) | Unidades de visualización para la resolución horizontal. |
| [getHeightDisplayUnit()](#getHeightDisplayUnit--) | Obtiene o establece la unidad de visualización de altura. |
| [getID()](#getID--) | Obtiene o establece el identificador único del recurso. |
| [getMinimalVersion()](#getMinimalVersion--) | Obtiene la versión mínima requerida de PSD. |
| [getName()](#getName--) | Obtiene o establece el nombre del recurso. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso. |
| [getSize()](#getSize--) | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| [getVDpi()](#getVDpi--) | DPI vertical. |
| [getVResDisplayUnit()](#getVResDisplayUnit--) | Unidades de visualización para la resolución vertical. |
| [getWidthDisplayUnit()](#getWidthDisplayUnit--) | Obtiene o establece la unidad de visualización de ancho. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Guarda el bloque de recurso en el flujo especificado. |
| [setHDpi(FixedPointDecimal value)](#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | DPI horizontal. |
| [setHResDisplayUnit(int value)](#setHResDisplayUnit-int-) | Unidades de visualización para la resolución horizontal. |
| [setHeightDisplayUnit(int value)](#setHeightDisplayUnit-int-) | Obtiene o establece la unidad de visualización de altura. |
| [setID(short value)](#setID-short-) | Obtiene o establece el identificador único del recurso. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtiene o establece la información de capa y máscara. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre del recurso. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtiene o establece el estado del bloque de recurso. |
| [setVDpi(FixedPointDecimal value)](#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | DPI vertical. |
| [setVResDisplayUnit(int value)](#setVResDisplayUnit-int-) | Unidades de visualización para la resolución vertical. |
| [setWidthDisplayUnit(int value)](#setWidthDisplayUnit-int-) | Obtiene o establece la unidad de visualización de ancho. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valida los valores del recurso. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionInfoResource() {#ResolutionInfoResource--}
```
public ResolutionInfoResource()
```


Inicializa una nueva instancia de la clase [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource).

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
### getHDpi() {#getHDpi--}
```
public final FixedPointDecimal getHDpi()
```


DPI horizontal.

Valor: El DPI horizontal.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getHResDisplayUnit() {#getHResDisplayUnit--}
```
public final int getHResDisplayUnit()
```


Unidades de visualización para la resolución horizontal. Esto solo afecta a la interfaz de usuario; la resolución sigue almacenada en el archivo PSD como píxeles/pulgada.

Valor: La unidad de visualización de la resolución horizontal.

**Returns:**
int
### getHeightDisplayUnit() {#getHeightDisplayUnit--}
```
public final int getHeightDisplayUnit()
```


Obtiene o establece la unidad de visualización de altura.

Valor: La unidad de visualización de altura.

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
### getVDpi() {#getVDpi--}
```
public final FixedPointDecimal getVDpi()
```


DPI vertical.

Valor: La resolución vertical en ppp.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getVResDisplayUnit() {#getVResDisplayUnit--}
```
public final int getVResDisplayUnit()
```


Unidades de visualización para la resolución vertical.

Valor: La unidad de visualización de la resolución vertical.

**Returns:**
int
### getWidthDisplayUnit() {#getWidthDisplayUnit--}
```
public final int getWidthDisplayUnit()
```


Obtiene o establece la unidad de visualización de ancho.

Valor: La unidad de visualización del ancho.

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

### setHDpi(FixedPointDecimal value) {#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setHDpi(FixedPointDecimal value)
```


DPI horizontal.

Valor: El DPI horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setHResDisplayUnit(int value) {#setHResDisplayUnit-int-}
```
public final void setHResDisplayUnit(int value)
```


Unidades de visualización para la resolución horizontal. Esto solo afecta a la interfaz de usuario; la resolución sigue almacenada en el archivo PSD como píxeles/pulgada.

Valor: La unidad de visualización de la resolución horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHeightDisplayUnit(int value) {#setHeightDisplayUnit-int-}
```
public final void setHeightDisplayUnit(int value)
```


Obtiene o establece la unidad de visualización de altura.

Valor: La unidad de visualización de altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

### setVDpi(FixedPointDecimal value) {#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setVDpi(FixedPointDecimal value)
```


DPI vertical.

Valor: La resolución vertical en ppp.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setVResDisplayUnit(int value) {#setVResDisplayUnit-int-}
```
public final void setVResDisplayUnit(int value)
```


Unidades de visualización para la resolución vertical.

Valor: La unidad de visualización de la resolución vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWidthDisplayUnit(int value) {#setWidthDisplayUnit-int-}
```
public final void setWidthDisplayUnit(int value)
```


Obtiene o establece la unidad de visualización de ancho.

Valor: La unidad de visualización del ancho.

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

