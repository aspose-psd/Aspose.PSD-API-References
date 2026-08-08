---
title: "PathShape"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La figura a partir de los nudos de la curva Bézier."
type: docs
weight: 16
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

La figura a partir de los nudos de la curva Bézier.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PathShape()](#PathShape--) | Inicializa una nueva instancia de la clase [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Inicializa una nueva instancia de la clase [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Obtiene la matriz de nudos Bézier. |
| [getPathOperations()](#getPathOperations--) | Obtiene o establece las operaciones de ruta (operaciones booleanas). |
| [getShapeIndex()](#getShapeIndex--) | Obtiene o establece el índice de la forma de ruta actual en la capa. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Obtiene o establece un valor que indica si esta instancia está cerrada. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtiene o establece un valor que indica si esta instancia está cerrada. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Asigna una matriz de nudos Bezier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Obtiene o establece las operaciones de ruta (operaciones booleanas). |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Obtiene o establece el índice de la forma de ruta actual en la capa. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | Crea los registros  VectorPathRecord  basados en esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


Inicializa una nueva instancia de la clase [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


Inicializa una nueva instancia de la clase [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | El registro de longitud. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Los registros de nudos Bezier. |

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
### getItems() {#getItems--}
```
public final BezierKnotRecord[] getItems()
```


Obtiene la matriz de nudos Bézier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Matriz de BezierKnotRecord
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Obtiene o establece las operaciones de ruta (operaciones booleanas).

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Obtiene o establece el índice de la forma de ruta actual en la capa.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Obtiene o establece un valor que indica si esta instancia está cerrada.

Valor:  true  si esta instancia está cerrada; de lo contrario,  false .

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




### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Obtiene o establece un valor que indica si esta instancia está cerrada.

Valor:  true  si esta instancia está cerrada; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Asigna una matriz de nudos Bezier.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Matriz de nudos Bezier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Obtiene o establece las operaciones de ruta (operaciones booleanas).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Obtiene o establece el índice de la forma de ruta actual en la capa.

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
### toVectorPathRecords() {#toVectorPathRecords--}
```
public final System.Collections.Generic.IGenericEnumerable<VectorPathRecord> toVectorPathRecords()
```


Crea los registros  VectorPathRecord  basados en esta instancia.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - Devuelve un  LengthRecord  y un  BezierKnotRecord  por cada punto en esta instancia.
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

