---
title: "PolygonShape"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una forma poligonale."
type: docs
weight: 15
url: /it/java/com.aspose.psd.shapes/polygonshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Rappresenta una forma poligonale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Inizializza una nuova istanza della classe  PolygonShape  . |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.psd.PointF---) | Inizializza una nuova istanza della classe  PolygonShape  . |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.psd.PointF---boolean-) | Inizializza una nuova istanza della classe  PolygonShape  . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Ottiene i limiti dell'oggetto. |
| [getCenter()](#getCenter--) | Restituisce il centro della forma. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Ottiene il punto finale della forma. |
| [getPoints()](#getPoints--) | Ottiene o imposta i punti della curva. |
| [getSegments()](#getSegments--) | Restituisce i segmenti della forma. |
| [getStartPoint()](#getStartPoint--) | Ottiene il punto iniziale della forma. |
| [hasSegments()](#hasSegments--) | Restituisce un valore che indica se la forma ha segmenti. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Ottiene o imposta un valore che indica se la forma è chiusa. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Inverte l'ordine dei punti per questa forma. |
| [setClosed(boolean value)](#setClosed-boolean-) | Ottiene o imposta un valore che indica se la forma è chiusa. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Ottiene o imposta i punti della curva. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applica la trasformazione specificata alla forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Inizializza una nuova istanza della classe  PolygonShape  .

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.psd.PointF---}
```
public PolygonShape(PointF[] points)
```


Inizializza una nuova istanza della classe  PolygonShape  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | L'array dei punti. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.psd.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Inizializza una nuova istanza della classe  PolygonShape  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | L'array dei punti. |
| isClosed | boolean | Se impostato su  true  il poligono è chiuso. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ottiene i limiti dell'oggetto.

Valore: i limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](../../com.aspose.psd/pen) | La penna da usare per l'oggetto. Questo può influenzare le dimensioni dei limiti dell'oggetto. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Restituisce il centro della forma.

Valore: il centro della forma.

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


Ottiene il punto finale della forma.

Valore: Il punto finale della forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Ottiene o imposta i punti della curva.

Valore: I punti della curva.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Restituisce i segmenti della forma.

Valore: I segmenti della forma.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Ottiene il punto iniziale della forma.

Valore: Il punto iniziale della forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Restituisce un valore che indica se la forma ha segmenti.

Valore:  True  se la forma ha segmenti; altrimenti,  false .

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


Ottiene o imposta un valore che indica se la forma è chiusa.

Valore:  true  se la forma è chiusa; altrimenti,  false .

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


Inverte l'ordine dei punti per questa forma.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Ottiene o imposta un valore che indica se la forma è chiusa.

Valore:  true  se la forma è chiusa; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Ottiene o imposta i punti della curva.

Valore: I punti della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Applica la trasformazione specificata alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | La trasformazione da applicare. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

