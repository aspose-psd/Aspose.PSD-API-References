---
title: "RectangleProjectedShape"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una forma proiettata su un rettangolo ruotato in una particolare orientazione."
type: docs
weight: 16
url: /it/java/com.aspose.psd.shapes/rectangleprojectedshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Rappresenta una forma che viene proiettata su un rettangolo ruotato in una particolare orientazione. Specificata da quattro punti che possono essere ruotati nello spazio mantenendo la stessa lunghezza dei lati e 90 gradi tra i lati adiacenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RectangleProjectedShape()](#RectangleProjectedShape--) | Inizializza una nuova istanza della classe  RectangleProjectedShape. |
| [RectangleProjectedShape(RectangleF rectangle)](#RectangleProjectedShape-com.aspose.psd.RectangleF-) | Inizializza una nuova istanza della classe  RectangleProjectedShape. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Ottiene i limiti dell'oggetto. |
| [getCenter()](#getCenter--) | Restituisce il centro della forma. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Ottiene il punto in basso a sinistra del rettangolo. |
| [getLeftTop()](#getLeftTop--) | Ottiene il punto in alto a sinistra del rettangolo. |
| [getRectangleHeight()](#getRectangleHeight--) | Ottiene l'altezza del rettangolo. |
| [getRectangleWidth()](#getRectangleWidth--) | Ottiene la larghezza del rettangolo. |
| [getRightBottom()](#getRightBottom--) | Ottiene il punto in basso a destra del rettangolo. |
| [getRightTop()](#getRightTop--) | Ottiene il punto in alto a destra del rettangolo. |
| [getSegments()](#getSegments--) | Restituisce i segmenti della forma. |
| [hasSegments()](#hasSegments--) | Restituisce un valore che indica se la forma ha segmenti. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applica la trasformazione specificata alla forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleProjectedShape() {#RectangleProjectedShape--}
```
public RectangleProjectedShape()
```


Inizializza una nuova istanza della classe  RectangleProjectedShape.

### RectangleProjectedShape(RectangleF rectangle) {#RectangleProjectedShape-com.aspose.psd.RectangleF-}
```
public RectangleProjectedShape(RectangleF rectangle)
```


Inizializza una nuova istanza della classe  RectangleProjectedShape.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo da cui inizializzare. |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Ottiene il punto in basso a sinistra del rettangolo.

Valore: il punto in basso a sinistra del rettangolo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Ottiene il punto in alto a sinistra del rettangolo.

Valore: il punto in alto a sinistra del rettangolo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Ottiene l'altezza del rettangolo.

Valore: l'altezza del rettangolo.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Ottiene la larghezza del rettangolo.

Valore: La larghezza del rettangolo.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Ottiene il punto in basso a destra del rettangolo.

Valore: Il punto in basso a destra del rettangolo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Ottiene il punto in alto a destra del rettangolo.

Valore: Il punto in alto a destra del rettangolo.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


Restituisce i segmenti della forma.

**Returns:**
com.aspose.psd.ShapeSegment[] - I segmenti della forma.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

