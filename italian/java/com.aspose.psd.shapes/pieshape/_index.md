---
title: "PieShape"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una forma a torta."
type: docs
weight: 14
url: /it/java/com.aspose.psd.shapes/pieshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

Rappresenta una forma a torta.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PieShape()](#PieShape--) | Inizializza una nuova istanza della classe  PieShape . |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.psd.RectangleF-float-float-) | Inizializza una nuova istanza della classe  PieShape . |
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
| [getStartAngle()](#getStartAngle--) | Ottiene o imposta l'angolo di partenza. |
| [getSweepAngle()](#getSweepAngle--) | Ottiene o imposta l'angolo di sweep. |
| [hasSegments()](#hasSegments--) | Restituisce un valore che indica se la forma ha segmenti. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStartAngle(float value)](#setStartAngle-float-) | Ottiene o imposta l'angolo di partenza. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Ottiene o imposta l'angolo di sweep. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applica la trasformazione specificata alla forma. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PieShape() {#PieShape--}
```
public PieShape()
```


Inizializza una nuova istanza della classe  PieShape .

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.psd.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Inizializza una nuova istanza della classe  PieShape .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Il rettangolo. |
| startAngle | float | L'angolo di partenza. |
| sweepAngle | float | L'angolo di sweep. |

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
public ShapeSegment[] getSegments()
```


Restituisce i segmenti della forma.

Valore: I segmenti della forma.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Ottiene o imposta l'angolo di partenza.

Valore: L'angolo di partenza.

**Returns:**
float
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Ottiene o imposta l'angolo di sweep.

Valore: L'angolo di sweep.

**Returns:**
float
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




### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Ottiene o imposta l'angolo di partenza.

Valore: L'angolo di partenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Ottiene o imposta l'angolo di sweep.

Valore: L'angolo di sweep.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

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

