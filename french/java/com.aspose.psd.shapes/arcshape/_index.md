---
title: "ArcShape"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente une forme d'arc."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Représente une forme d'arc.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ArcShape()](#ArcShape--) | Initialise une nouvelle instance de la classe ArcShape. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | Initialise une nouvelle instance de la classe ArcShape. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | Initialise une nouvelle instance de la classe ArcShape. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Obtient les limites de l'objet. |
| [getCenter()](#getCenter--) | Obtient le centre de la forme. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Obtient le point final de la forme. |
| [getLeftBottom()](#getLeftBottom--) | Obtient le point inférieur gauche du rectangle. |
| [getLeftTop()](#getLeftTop--) | Obtient le point supérieur gauche du rectangle. |
| [getRectangleHeight()](#getRectangleHeight--) | Obtient la hauteur du rectangle. |
| [getRectangleWidth()](#getRectangleWidth--) | Obtient la largeur du rectangle. |
| [getRightBottom()](#getRightBottom--) | Obtient le point inférieur droit du rectangle. |
| [getRightTop()](#getRightTop--) | Obtient le point supérieur droit du rectangle. |
| [getSegments()](#getSegments--) | Obtient les segments de la forme. |
| [getStartAngle()](#getStartAngle--) | Obtient ou définit l'angle de départ. |
| [getStartPoint()](#getStartPoint--) | Obtient le point de départ de la forme. |
| [getSweepAngle()](#getSweepAngle--) | Obtient ou définit l'angle d'extension. |
| [hasSegments()](#hasSegments--) | Obtient une valeur indiquant si la forme possède des segments. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Obtient ou définit une valeur indiquant si la forme ordonnée est fermée. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Inverse l'ordre des points pour cette forme. |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtient ou définit une valeur indiquant si la forme ordonnée est fermée. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtient ou définit l'angle de départ. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtient ou définit l'angle d'extension. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applique la transformation spécifiée à la forme. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Initialise une nouvelle instance de la classe ArcShape.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initialise une nouvelle instance de la classe ArcShape.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle. |
| startAngle | float | L'angle de départ. |
| sweepAngle | float | L'angle d'extension. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Initialise une nouvelle instance de la classe ArcShape.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle. |
| startAngle | float | L'angle de départ. |
| sweepAngle | float | L'angle d'extension. |
| isClosed | booléen | Si la valeur est définie sur true, l'arc est fermé. L'arc fermé dégénère en fait en une ellipse. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtient les limites de l'objet.

Valeur : les limites de l'objet.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtient les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice à appliquer avant que les limites ne soient calculées. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtient les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La matrice à appliquer avant que les limites ne soient calculées. |
| pen | [Pen](../../com.aspose.psd/pen) | Le crayon à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Obtient le centre de la forme.

Valeur : le centre de la forme.

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


Obtient le point final de la forme.

Valeur : le point final de la forme.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Obtient le point inférieur gauche du rectangle.

Valeur : le point inférieur gauche du rectangle.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Obtient le point supérieur gauche du rectangle.

Valeur : le point supérieur gauche du rectangle.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Obtient la hauteur du rectangle.

Valeur : la hauteur du rectangle.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Obtient la largeur du rectangle.

Valeur : la largeur du rectangle.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Obtient le point inférieur droit du rectangle.

Valeur : le point inférieur droit du rectangle.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Obtient le point supérieur droit du rectangle.

Valeur : le point supérieur droit du rectangle.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtient les segments de la forme.

Valeur : les segments de la forme.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtient ou définit l'angle de départ.

Valeur : L'angle de départ.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Obtient le point de départ de la forme.

Valeur : le point de départ de la forme.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtient ou définit l'angle d'extension.

Valeur : L'angle d'extension.

**Returns:**
float
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Obtient une valeur indiquant si la forme possède des segments.

Valeur :  vrai  si la forme possède des segments ; sinon,  faux .

**Returns:**
booléen
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


Obtient ou définit une valeur indiquant si la forme ordonnée est fermée. Lors du traitement d'une forme ordonnée fermée, les points de départ et d'arrivée n'ont aucune signification.

Valeur : True si cette forme ordonnée est fermée ; sinon, false.

**Returns:**
booléen
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


Inverse l'ordre des points pour cette forme.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Obtient ou définit une valeur indiquant si la forme ordonnée est fermée. Lors du traitement d'une forme ordonnée fermée, les points de départ et d'arrivée n'ont aucune signification.

Valeur : True si cette forme ordonnée est fermée ; sinon, false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Obtient ou définit l'angle de départ.

Valeur : L'angle de départ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Obtient ou définit l'angle d'extension.

Valeur : L'angle d'extension.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

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


Applique la transformation spécifiée à la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | La transformation à appliquer. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

