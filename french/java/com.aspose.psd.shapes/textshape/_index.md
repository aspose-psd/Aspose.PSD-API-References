---
title: "TextShape"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente une forme de texte."
type: docs
weight: 18
url: /fr/java/com.aspose.psd.shapes/textshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Représente une forme de texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextShape()](#TextShape--) | Initialise une nouvelle instance de la classe TextShape. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-) | Initialise une nouvelle instance de la classe TextShape. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Obtient les limites de l'objet. |
| [getCenter()](#getCenter--) | Obtient le centre de la forme. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Obtient ou définit la police utilisée pour dessiner le texte. |
| [getLeftBottom()](#getLeftBottom--) | Obtient le point inférieur gauche du rectangle. |
| [getLeftTop()](#getLeftTop--) | Obtient le point supérieur gauche du rectangle. |
| [getRectangleHeight()](#getRectangleHeight--) | Obtient la hauteur du rectangle. |
| [getRectangleWidth()](#getRectangleWidth--) | Obtient la largeur du rectangle. |
| [getRightBottom()](#getRightBottom--) | Obtient le point inférieur droit du rectangle. |
| [getRightTop()](#getRightTop--) | Obtient le point supérieur droit du rectangle. |
| [getSegments()](#getSegments--) | Obtient les segments de la forme. |
| [getText()](#getText--) | Obtient ou définit le texte dessiné. |
| [getTextFormat()](#getTextFormat--) | Obtient ou définit le format du texte. |
| [hasSegments()](#hasSegments--) | Obtient une valeur indiquant si la forme possède des segments. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFont(Font value)](#setFont-com.aspose.psd.Font-) | Obtient ou définit la police utilisée pour dessiner le texte. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte dessiné. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.psd.StringFormat-) | Obtient ou définit le format du texte. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applique la transformation spécifiée à la forme. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initialise une nouvelle instance de la classe TextShape.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initialise une nouvelle instance de la classe TextShape.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à dessiner. |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle du texte. |
| font | [Font](../../com.aspose.psd/font) | La police à utiliser. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Le format de chaîne. |

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
### getFont() {#getFont--}
```
public Font getFont()
```


Obtient ou définit la police utilisée pour dessiner le texte.

Valeur : La police utilisée pour dessiner le texte.

**Returns:**
[Font](../../com.aspose.psd/font)
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
### getText() {#getText--}
```
public String getText()
```


Obtient ou définit le texte dessiné.

Valeur : Le texte dessiné.

**Returns:**
java.lang.String
### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Obtient ou définit le format du texte.

Valeur : Le format du texte.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat)
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




### setFont(Font value) {#setFont-com.aspose.psd.Font-}
```
public void setFont(Font value)
```


Obtient ou définit la police utilisée pour dessiner le texte.

Valeur : La police utilisée pour dessiner le texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.psd/font) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Obtient ou définit le texte dessiné.

Valeur : Le texte dessiné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.psd.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Obtient ou définit le format du texte.

Valeur : Le format du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.psd/stringformat) |  |

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

