---
title: "RectangleProjectedShape"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente une forme projetée sur un rectangle orienté dans une direction particulière."
type: docs
weight: 16
url: /fr/java/com.aspose.psd.shapes/rectangleprojectedshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Représente une forme projetée sur un rectangle orienté d'une manière particulière. Spécifiée par quatre points qui peuvent être tournés dans l'espace tout en conservant la même longueur des arêtes et 90 degrés entre les arêtes adjacentes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RectangleProjectedShape()](#RectangleProjectedShape--) | Initialise une nouvelle instance de la classe  RectangleProjectedShape. |
| [RectangleProjectedShape(RectangleF rectangle)](#RectangleProjectedShape-com.aspose.psd.RectangleF-) | Initialise une nouvelle instance de la classe  RectangleProjectedShape. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Obtient les limites de l'objet. |
| [getCenter()](#getCenter--) | Obtient le centre de la forme. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Obtient le point inférieur gauche du rectangle. |
| [getLeftTop()](#getLeftTop--) | Obtient le point supérieur gauche du rectangle. |
| [getRectangleHeight()](#getRectangleHeight--) | Obtient la hauteur du rectangle. |
| [getRectangleWidth()](#getRectangleWidth--) | Obtient la largeur du rectangle. |
| [getRightBottom()](#getRightBottom--) | Obtient le point inférieur droit du rectangle. |
| [getRightTop()](#getRightTop--) | Obtient le point supérieur droit du rectangle. |
| [getSegments()](#getSegments--) | Obtient les segments de la forme. |
| [hasSegments()](#hasSegments--) | Obtient une valeur indiquant si la forme possède des segments. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applique la transformation spécifiée à la forme. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleProjectedShape() {#RectangleProjectedShape--}
```
public RectangleProjectedShape()
```


Initialise une nouvelle instance de la classe  RectangleProjectedShape.

### RectangleProjectedShape(RectangleF rectangle) {#RectangleProjectedShape-com.aspose.psd.RectangleF-}
```
public RectangleProjectedShape(RectangleF rectangle)
```


Initialise une nouvelle instance de la classe  RectangleProjectedShape.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle à partir duquel initialiser. |

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
public abstract ShapeSegment[] getSegments()
```


Obtient les segments de la forme.

**Returns:**
com.aspose.psd.ShapeSegment[] - Les segments de la forme.
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

