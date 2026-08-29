---
title: "Figure"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La figure."
type: docs
weight: 42
url: /fr/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

La figure. Un conteneur pour les formes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Figure()](#Figure--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Ajoute une forme à la figure. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Ajoute une plage de formes à la figure. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtient ou définit les limites de l'objet. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Obtient les limites de l'objet. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Obtient les segments complets de la figure. |
| [getShapes()](#getShapes--) | Obtient les formes de la figure. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Obtient une valeur indiquant si cette figure est fermée. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Supprime une forme de la figure. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Supprime une plage de formes de la figure. |
| [reverse()](#reverse--) | Inverse l'ordre des formes de cette figure ainsi que l'ordre des points des formes. |
| [setClosed(boolean value)](#setClosed-boolean-) | Définit une valeur indiquant si cette figure est fermée. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Applique la transformation spécifiée à la forme. |
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


Ajoute une forme à la figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | La forme à ajouter. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Ajoute une plage de formes à la figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Les formes à ajouter. |

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


Obtient ou définit les limites de l'objet.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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


Obtient les segments complets de la figure.

**Returns:**
com.aspose.psd.ShapeSegment[] - Les segments de la figure.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Obtient les formes de la figure.

**Returns:**
com.aspose.psd.Shape[] - Les formes de la figure.
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


Obtient une valeur indiquant si cette figure est fermée. Une figure fermée ne fera une différence que dans le cas où les premières et dernières formes de la figure sont des formes continues. Dans ce cas, le premier point de la première forme sera relié par une ligne droite au dernier point de la dernière forme.

**Returns:**
boolean -  True  si cette figure est fermée ; sinon,  false .
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


Supprime une forme de la figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | La forme à supprimer. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Supprime une plage de formes de la figure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | La plage de formes à supprimer. |

### reverse() {#reverse--}
```
public void reverse()
```


Inverse l'ordre des formes de cette figure ainsi que l'ordre des points des formes.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Définit une valeur indiquant si cette figure est fermée. Une figure fermée ne fera une différence que dans le cas où les premières et dernières formes de la figure sont des formes continues. Dans ce cas, le premier point de la première forme sera relié par une ligne droite au dernier point de la dernière forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | True  si cette figure est fermée ; sinon,  false . |

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

