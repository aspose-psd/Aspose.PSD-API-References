---
title: "GridAndGuidesResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el recurso de cuadrícula y guías."
type: docs
weight: 20
url: /es/java/com.aspose.psd.fileformats.psd.resources/gridandguidesresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class GridAndGuidesResource extends ResourceBlock
```

Representa el recurso de cuadrícula y guías.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GridAndGuidesResource()](#GridAndGuidesResource--) | Inicializa una nueva instancia de la clase [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource). |
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
| [getGridCycleX()](#getGridCycleX--) | Obtiene o establece el ciclo de cuadrícula horizontal. |
| [getGridCycleY()](#getGridCycleY--) | Obtiene o establece el ciclo de cuadrícula vertical. |
| [getGuideCount()](#getGuideCount--) | Obtiene el recuento de bloques de recursos de guía. |
| [getGuides()](#getGuides--) | Obtiene o establece las guías. |
| [getHeaderVersion()](#getHeaderVersion--) | Obtiene o establece la versión del encabezado. |
| [getID()](#getID--) | Obtiene o establece el identificador único del recurso. |
| [getMinimalVersion()](#getMinimalVersion--) | Obtiene la versión mínima requerida de PSD. |
| [getName()](#getName--) | Obtiene o establece el nombre del recurso. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso. |
| [getSize()](#getSize--) | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Guarda el bloque de recurso en el flujo especificado. |
| [setGridCycleX(int value)](#setGridCycleX-int-) | Obtiene o establece el ciclo de cuadrícula horizontal. |
| [setGridCycleY(int value)](#setGridCycleY-int-) | Obtiene o establece el ciclo de cuadrícula vertical. |
| [setGuides(GuideResource[] value)](#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---) | Obtiene o establece las guías. |
| [setHeaderVersion(int value)](#setHeaderVersion-int-) | Obtiene o establece la versión del encabezado. |
| [setID(short value)](#setID-short-) | Obtiene o establece el identificador único del recurso. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Obtiene o establece la información de capa y máscara. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre del recurso. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Obtiene o establece el estado del bloque de recurso. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Valida los valores del recurso. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GridAndGuidesResource() {#GridAndGuidesResource--}
```
public GridAndGuidesResource()
```


Inicializa una nueva instancia de la clase [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource).

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
### getGridCycleX() {#getGridCycleX--}
```
public final int getGridCycleX()
```


Obtiene o establece el ciclo de cuadrícula horizontal. El valor predeterminado es 576.

Valor: El ciclo de cuadrícula horizontal.

**Returns:**
int
### getGridCycleY() {#getGridCycleY--}
```
public final int getGridCycleY()
```


Obtiene o establece el ciclo de cuadrícula vertical. El valor predeterminado es 576.

Valor: El ciclo de cuadrícula vertical.

**Returns:**
int
### getGuideCount() {#getGuideCount--}
```
public final int getGuideCount()
```


Obtiene el recuento de bloques de recursos de guía.

Valor: El recuento de bloques de recursos de guía.

**Returns:**
int
### getGuides() {#getGuides--}
```
public final GuideResource[] getGuides()
```


Obtiene o establece las guías.

Valor: Las guías.

**Returns:**
com.aspose.psd.fileformats.psd.resources.GuideResource[]
### getHeaderVersion() {#getHeaderVersion--}
```
public final int getHeaderVersion()
```


Obtiene o establece la versión del encabezado. Este valor siempre debe ser 1.

Valor: La versión del encabezado.

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

Valor: La versión mínima de psd.

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

### setGridCycleX(int value) {#setGridCycleX-int-}
```
public final void setGridCycleX(int value)
```


Obtiene o establece el ciclo de cuadrícula horizontal. El valor predeterminado es 576.

Valor: El ciclo de cuadrícula horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGridCycleY(int value) {#setGridCycleY-int-}
```
public final void setGridCycleY(int value)
```


Obtiene o establece el ciclo de cuadrícula vertical. El valor predeterminado es 576.

Valor: El ciclo de cuadrícula vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGuides(GuideResource[] value) {#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---}
```
public final void setGuides(GuideResource[] value)
```


Obtiene o establece las guías.

Valor: Las guías.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GuideResource\[\]](../../com.aspose.psd.fileformats.psd.resources/guideresource) |  |

### setHeaderVersion(int value) {#setHeaderVersion-int-}
```
public final void setHeaderVersion(int value)
```


Obtiene o establece la versión del encabezado. Este valor siempre debe ser 1.

Valor: La versión del encabezado.

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

