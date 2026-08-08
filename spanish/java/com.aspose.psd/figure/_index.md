---
title: "Figura"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La figura."
type: docs
weight: 42
url: /es/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

La figura. Un contenedor para formas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Figure()](#Figure--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Agrega una forma a la figura. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Agrega un rango de formas a la figura. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtiene o establece los límites del objeto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Obtiene los límites del objeto. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Obtiene los segmentos completos de la figura. |
| [getShapes()](#getShapes--) | Obtiene las formas de la figura. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Obtiene un valor que indica si esta figura está cerrada. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Elimina una forma de la figura. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Elimina un rango de formas de la figura. |
| [reverse()](#reverse--) | Invierte el orden de las formas de esta figura y el orden de los puntos de las formas. |
| [setClosed(boolean value)](#setClosed-boolean-) | Establece un valor que indica si esta figura está cerrada. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Aplica la transformación especificada a la forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


Agrega una forma a la figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | La forma a agregar. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Agrega un rango de formas a la figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Las formas a agregar. |

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


Obtiene o establece los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtiene los segmentos completos de la figura.

**Returns:**
com.aspose.psd.ShapeSegment[] - Los segmentos de la figura.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Obtiene las formas de la figura.

**Returns:**
com.aspose.psd.Shape[] - Las formas de la figura.
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


Obtiene un valor que indica si esta figura está cerrada. Una figura cerrada solo hará una diferencia en el caso en que las formas primera y última de la figura sean formas continuas. En tal caso, el primer punto de la primera forma se conectará mediante una línea recta al último punto de la última forma.

**Returns:**
boolean -  True  si esta figura está cerrada; de lo contrario,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


Elimina una forma de la figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | La forma a eliminar. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Elimina un rango de formas de la figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | El rango de formas a eliminar. |

### reverse() {#reverse--}
```
public void reverse()
```


Invierte el orden de las formas de esta figura y el orden de los puntos de las formas.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Establece un valor que indica si esta figura está cerrada. Una figura cerrada solo hará una diferencia en el caso en que las formas primera y última de la figura sean formas continuas. En tal caso, el primer punto de la primera forma se conectará mediante una línea recta al último punto de la última forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Verdadero si esta figura está cerrada; de lo contrario, falso. |

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

