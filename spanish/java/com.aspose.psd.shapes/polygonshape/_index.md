---
title: "PolygonShape"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa una forma de polígono."
type: docs
weight: 15
url: /es/java/com.aspose.psd.shapes/polygonshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Representa una forma de polígono.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Inicializa una nueva instancia de la  PolygonShape  clase. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.psd.PointF---) | Inicializa una nueva instancia de la  PolygonShape  clase. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.psd.PointF---boolean-) | Inicializa una nueva instancia de la  PolygonShape  clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Obtiene los límites del objeto. |
| [getCenter()](#getCenter--) | Obtiene el centro de la forma. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Obtiene el punto final de la forma. |
| [getPoints()](#getPoints--) | Obtiene o establece los puntos de la curva. |
| [getSegments()](#getSegments--) | Obtiene los segmentos de la forma. |
| [getStartPoint()](#getStartPoint--) | Obtiene el punto inicial de la forma. |
| [hasSegments()](#hasSegments--) | Obtiene un valor que indica si la forma tiene segmentos. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Obtiene o establece un valor que indica si la forma está cerrada. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Invierte el orden de los puntos de esta forma. |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtiene o establece un valor que indica si la forma está cerrada. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Obtiene o establece los puntos de la curva. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Aplica la transformación especificada a la forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Inicializa una nueva instancia de la  PolygonShape  clase.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.psd.PointF---}
```
public PolygonShape(PointF[] points)
```


Inicializa una nueva instancia de la  PolygonShape  clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | La matriz de puntos. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.psd.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Inicializa una nueva instancia de la  PolygonShape  clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | La matriz de puntos. |
| isClosed | boolean | Si se establece en  true  el polígono está cerrado. |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtiene los límites del objeto.

Valor: Los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matriz a aplicar antes de que se calculen los límites. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matriz a aplicar antes de que se calculen los límites. |
| pen | [Pen](../../com.aspose.psd/pen) | El bolígrafo a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Obtiene el centro de la forma.

Valor: El centro de la forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Obtiene el punto final de la forma.

Value: El punto final de la forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Obtiene o establece los puntos de la curva.

Value: Los puntos de la curva.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtiene los segmentos de la forma.

Value: Los segmentos de la forma.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Obtiene el punto inicial de la forma.

Value: El punto inicial de la forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Obtiene un valor que indica si la forma tiene segmentos.

Value:  True  si la forma tiene segmentos; de lo contrario,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Obtiene o establece un valor que indica si la forma está cerrada.

Value:  true  si la forma está cerrada; de lo contrario,  false .

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




### reverse() {#reverse--}
```
public void reverse()
```


Invierte el orden de los puntos de esta forma.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Obtiene o establece un valor que indica si la forma está cerrada.

Value:  true  si la forma está cerrada; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Obtiene o establece los puntos de la curva.

Value: Los puntos de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Aplica la transformación especificada a la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | La transformación a aplicar. |

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

