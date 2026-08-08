---
title: "IPathShape"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La Shape de los nudos de la curva Bezier."
type: docs
weight: 31
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

La Shape de los nudos de la curva Bezier.
## Métodos

| Método | Descripción |
| --- | --- |
| [getItems()](#getItems--) | Obtiene la matriz de nudos Bézier. |
| [getPathOperations()](#getPathOperations--) | Las operaciones para combinar formas de ruta (operaciones booleanas). |
| [isClosed()](#isClosed--) | Obtiene o establece la propiedad que determina si Shape está cerrada. |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtiene o establece la propiedad que determina si Shape está cerrada. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Asigna una matriz de nudos Bexier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Las operaciones para combinar formas de ruta (operaciones booleanas). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Obtiene la matriz de nudos Bézier.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Matriz de BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Las operaciones para combinar formas de ruta (operaciones booleanas).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Obtiene o establece la propiedad que determina si Shape está cerrada.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Obtiene o establece la propiedad que determina si Shape está cerrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Asigna una matriz de nudos Bexier.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Matriz de nudos Bezier |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Las operaciones para combinar formas de ruta (operaciones booleanas).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

