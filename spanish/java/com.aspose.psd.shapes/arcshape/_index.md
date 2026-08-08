---
title: "ArcShape"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa una forma de arco."
type: docs
weight: 10
url: /es/java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Representa una forma de arco.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ArcShape()](#ArcShape--) | Inicializa una nueva instancia de la clase ArcShape. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | Inicializa una nueva instancia de la clase ArcShape. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | Inicializa una nueva instancia de la clase ArcShape. |
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
| [getLeftBottom()](#getLeftBottom--) | Obtiene el punto inferior izquierdo del rectángulo. |
| [getLeftTop()](#getLeftTop--) | Obtiene el punto superior izquierdo del rectángulo. |
| [getRectangleHeight()](#getRectangleHeight--) | Obtiene la altura del rectángulo. |
| [getRectangleWidth()](#getRectangleWidth--) | Obtiene el ancho del rectángulo. |
| [getRightBottom()](#getRightBottom--) | Obtiene el punto inferior derecho del rectángulo. |
| [getRightTop()](#getRightTop--) | Obtiene el punto superior derecho del rectángulo. |
| [getSegments()](#getSegments--) | Obtiene los segmentos de la forma. |
| [getStartAngle()](#getStartAngle--) | Obtiene o establece el ángulo de inicio. |
| [getStartPoint()](#getStartPoint--) | Obtiene el punto inicial de la forma. |
| [getSweepAngle()](#getSweepAngle--) | Obtiene o establece el ángulo de barrido. |
| [hasSegments()](#hasSegments--) | Obtiene un valor que indica si la forma tiene segmentos. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Obtiene o establece un valor que indica si la forma ordenada está cerrada. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Invierte el orden de los puntos de esta forma. |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtiene o establece un valor que indica si la forma ordenada está cerrada. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtiene o establece el ángulo de inicio. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtiene o establece el ángulo de barrido. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Aplica la transformación especificada a la forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Inicializa una nueva instancia de la clase ArcShape.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Inicializa una nueva instancia de la clase ArcShape.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo. |
| startAngle | float | El ángulo de inicio. |
| sweepAngle | float | El ángulo de barrido. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Inicializa una nueva instancia de la clase ArcShape.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo. |
| startAngle | float | El ángulo de inicio. |
| sweepAngle | float | El ángulo de barrido. |
| isClosed | boolean | Si se establece en true, el arco está cerrado. El arco cerrado en realidad se degenera en una elipse. |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Obtiene el punto inferior izquierdo del rectángulo.

Valor: El punto inferior izquierdo del rectángulo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Obtiene el punto superior izquierdo del rectángulo.

Valor: El punto superior izquierdo del rectángulo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Obtiene la altura del rectángulo.

Valor: La altura del rectángulo.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Obtiene el ancho del rectángulo.

Value: El ancho del rectángulo.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Obtiene el punto inferior derecho del rectángulo.

Value: El punto inferior derecho del rectángulo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Obtiene el punto superior derecho del rectángulo.

Value: El punto superior derecho del rectángulo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtiene los segmentos de la forma.

Value: Los segmentos de la forma.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtiene o establece el ángulo de inicio.

Valor: El ángulo de inicio.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Obtiene el punto inicial de la forma.

Value: El punto inicial de la forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtiene o establece el ángulo de barrido.

Valor: El ángulo de barrido.

**Returns:**
float
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


Obtiene o establece un valor que indica si la forma ordenada está cerrada. Al procesar una forma ordenada cerrada, los puntos de inicio y fin no tienen significado.

Valor: True si esta forma ordenada está cerrada; de lo contrario, false.

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


Obtiene o establece un valor que indica si la forma ordenada está cerrada. Al procesar una forma ordenada cerrada, los puntos de inicio y fin no tienen significado.

Valor: True si esta forma ordenada está cerrada; de lo contrario, false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Obtiene o establece el ángulo de inicio.

Valor: El ángulo de inicio.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Obtiene o establece el ángulo de barrido.

Valor: El ángulo de barrido.

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

