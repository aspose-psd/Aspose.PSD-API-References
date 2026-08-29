---
title: "RectangleF"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Stocke un ensemble de quatre nombres flottants qui représentent la position et la taille d'un rectangle."
type: docs
weight: 89
url: /fr/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Stocke un ensemble de quatre nombres flottants qui représentent la position et la taille d'un rectangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initialise une nouvelle instance de la structure  com.aspose.psd.RectangleF  avec l'emplacement et la taille spécifiés. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Initialise une nouvelle instance de la structure  com.aspose.psd.RectangleF  avec l'emplacement et la taille spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Détermine si le point spécifié est contenu dans cette structure  com.aspose.psd.RectangleF . |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Détermine si la région rectangulaire représentée par  rect  est entièrement contenue dans cette structure  com.aspose.psd.RectangleF . |
| [contains(float x, float y)](#contains-float-float-) | Détermine si le point spécifié est contenu dans cette structure  com.aspose.psd.RectangleF . |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Divise les valeurs du rectangle actuel pour transformer les valeurs d'échelle verticale et horizontale de la matrice et renvoie une nouvelle instance de [RectangleF](../../com.aspose.psd/rectanglef) avec les valeurs résultantes. |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste si  obj  est un  com.aspose.psd.RectangleF  avec le même emplacement et la même taille que ce  com.aspose.psd.RectangleF . |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Crée une structure  com.aspose.psd.RectangleF  avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Crée un nouveau  Rectangle  à partir de deux points spécifiés. |
| [getBottom()](#getBottom--) | Obtient ou définit la coordonnée y qui est la somme de  com.aspose.psd.RectangleF.Y  et  com.aspose.psd.RectangleF.Height  de cette structure  com.aspose.psd.RectangleF . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure  com.aspose.psd.RectangleF  dont les valeurs  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  et  com.aspose.psd.RectangleF.Height  sont réglées à zéro. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur de cette structure  com.aspose.psd.RectangleF . |
| [getLeft()](#getLeft--) | Obtient ou définit la coordonnée x du bord gauche de cette structure  com.aspose.psd.RectangleF . |
| [getLocation()](#getLocation--) | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF . |
| [getRight()](#getRight--) | Obtient ou définit la coordonnée x qui est la somme de  com.aspose.psd.RectangleF.X  et  com.aspose.psd.RectangleF.Width  de cette structure  com.aspose.psd.RectangleF . |
| [getSize()](#getSize--) | Obtient ou définit la taille de ce  com.aspose.psd.RectangleF . |
| [getTop()](#getTop--) | Obtient ou définit la coordonnée y du bord supérieur de cette structure  com.aspose.psd.RectangleF . |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur de cette structure  com.aspose.psd.RectangleF . |
| [getX()](#getX--) | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF . |
| [getY()](#getY--) | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF . |
| [hashCode()](#hashCode--) | Obtient le code de hachage pour cette  com.aspose.psd.RectangleF  structure. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Crée et renvoie une copie gonflée de la structure  com.aspose.psd.RectangleF  spécifiée. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Gonfle ce  com.aspose.psd.RectangleF  du montant spécifié. |
| [inflate(float x, float y)](#inflate-float-float-) | Gonfle cette  com.aspose.psd.RectangleF  structure du montant spécifié. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Remplace cette  com.aspose.psd.RectangleF  structure par l'intersection d'elle-même et de la structure  com.aspose.psd.RectangleF  spécifiée. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Renvoie une structure  com.aspose.psd.RectangleF  qui représente l'intersection de deux rectangles. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Détermine si ce rectangle intersecte avec  rect . |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si la propriété  com.aspose.psd.RectangleF.Width  ou  com.aspose.psd.RectangleF.Height  de ce  com.aspose.psd.RectangleF  a une valeur zéro. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Multiplie les valeurs du rectangle actuel pour transformer les valeurs d'échelle verticale et horizontale de la matrice et renvoie une nouvelle instance [RectangleF](../../com.aspose.psd/rectanglef) avec les valeurs résultantes. |
| [normalize()](#normalize--) | Normalise le rectangle en rendant sa largeur et sa hauteur positives, la gauche inférieure à la droite et le haut inférieur au bas. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(float x, float y)](#offset-float-float-) | Ajuste la position de ce rectangle du montant spécifié. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Implémente l'opérateur /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Teste si deux structures  com.aspose.psd.RectangleF  ont la même position et la même taille. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Teste si deux structures  com.aspose.psd.RectangleF  diffèrent en position ou en taille. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Implémente l'opérateur \*. |
| [setBottom(float value)](#setBottom-float-) | Obtient ou définit la coordonnée y qui est la somme de  com.aspose.psd.RectangleF.Y  et  com.aspose.psd.RectangleF.Height  de cette structure  com.aspose.psd.RectangleF . |
| [setHeight(float value)](#setHeight-float-) | Obtient ou définit la hauteur de cette structure  com.aspose.psd.RectangleF . |
| [setLeft(float value)](#setLeft-float-) | Obtient ou définit la coordonnée x du bord gauche de cette structure  com.aspose.psd.RectangleF . |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF . |
| [setRight(float value)](#setRight-float-) | Obtient ou définit la coordonnée x qui est la somme de  com.aspose.psd.RectangleF.X  et  com.aspose.psd.RectangleF.Width  de cette structure  com.aspose.psd.RectangleF . |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Obtient ou définit la taille de ce  com.aspose.psd.RectangleF . |
| [setTop(float value)](#setTop-float-) | Obtient ou définit la coordonnée y du bord supérieur de cette structure  com.aspose.psd.RectangleF . |
| [setWidth(float value)](#setWidth-float-) | Obtient ou définit la largeur de cette structure  com.aspose.psd.RectangleF . |
| [setX(float value)](#setX-float-) | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF . |
| [setY(float value)](#setY-float-) | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF . |
| [toRectangle_internalized()](#toRectangle-internalized--) | Convertit un [RectangleF](../../com.aspose.psd/rectanglef) en une structure [Rectangle](../../com.aspose.psd/rectangle) avec des valeurs de rectangle tronquées. |
| [toString()](#toString--) | Convertit les attributs de ce  com.aspose.psd.RectangleF  en une chaîne lisible par l'homme. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Convertit la structure  com.aspose.psd.Rectangle  spécifiée en une structure  com.aspose.psd.RectangleF  . |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Crée le plus petit rectangle possible qui peut contenir les deux rectangles formant une union. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initialise une nouvelle instance de la structure  com.aspose.psd.RectangleF  avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle. |
| largeur | float | La largeur du rectangle. |
| hauteur | float | La hauteur du rectangle. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initialise une nouvelle instance de la structure  com.aspose.psd.RectangleF  avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [SizeF](../../com.aspose.psd/sizef) | Un  com.aspose.psd.SizeF  qui représente la largeur et la hauteur de la région rectangulaire. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Détermine si le point spécifié est contenu dans cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  com.aspose.psd.PointF  à tester. |

**Returns:**
booléen - Cette méthode renvoie true si le point représenté par le paramètre  point  est contenu dans cette structure  com.aspose.psd.RectangleF ; sinon false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Détermine si la région rectangulaire représentée par  rect  est entièrement contenue dans cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Le  com.aspose.psd.RectangleF  à tester. |

**Returns:**
booléen - Cette méthode renvoie true si la région rectangulaire représentée par  rect  est entièrement contenue dans la région rectangulaire représentée par cette  com.aspose.psd.RectangleF ; sinon false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Détermine si le point spécifié est contenu dans cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns:**
booléen - Cette méthode renvoie true si le point défini par  x  et  y  est contenu dans cette structure  com.aspose.psd.RectangleF ; sinon false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


Divise les valeurs du rectangle actuel pour transformer les valeurs d'échelle verticale et horizontale de la matrice et renvoie une nouvelle instance de [RectangleF](../../com.aspose.psd/rectanglef) avec les valeurs résultantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transformMatrix | double[] | La matrice de transformation du calque. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste si  obj  est un  com.aspose.psd.RectangleF  avec le même emplacement et la même taille que ce  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le  System.Object  à tester. |

**Returns:**
booléen - Cette méthode renvoie true si  obj  est un  com.aspose.psd.RectangleF  et que ses propriétés X, Y, Width et Height sont égales aux propriétés correspondantes de ce  com.aspose.psd.RectangleF ; sinon false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Crée une structure  com.aspose.psd.RectangleF  avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | float | La coordonnée x du coin supérieur gauche de la région rectangulaire. |
| top | float | La coordonnée y du coin supérieur gauche de la région rectangulaire. |
| right | float | La coordonnée x du coin inférieur droit de la région rectangulaire. |
| bottom | float | La coordonnée y du coin inférieur droit de la région rectangulaire. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crée un nouveau  Rectangle  à partir de deux points spécifiés. Les deux sommets du  Rectangle  créé seront égaux aux points  point1  et  point2  transmis. Ceux-ci sont généralement les sommets opposés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Le premier  Point  du nouveau rectangle. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Le deuxième  Point  du nouveau rectangle. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Obtient ou définit la coordonnée y qui est la somme de  com.aspose.psd.RectangleF.Y  et  com.aspose.psd.RectangleF.Height  de cette structure  com.aspose.psd.RectangleF .

**Returns:**
float - La coordonnée y qui est la somme de  com.aspose.psd.RectangleF.Y  et  com.aspose.psd.RectangleF.Height  de cette structure  com.aspose.psd.RectangleF.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Obtient une nouvelle instance de la structure  com.aspose.psd.RectangleF  dont les valeurs  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  et  com.aspose.psd.RectangleF.Height  sont réglées à zéro.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtient ou définit la hauteur de cette structure  com.aspose.psd.RectangleF .

**Returns:**
float - La hauteur de cette structure  com.aspose.psd.RectangleF.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Obtient ou définit la coordonnée x du bord gauche de cette structure  com.aspose.psd.RectangleF .

**Returns:**
float - La coordonnée x du bord gauche de cette structure  com.aspose.psd.RectangleF.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Obtient ou définit les coordonnées du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF .

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Obtient ou définit la coordonnée x qui est la somme de  com.aspose.psd.RectangleF.X  et  com.aspose.psd.RectangleF.Width  de cette structure  com.aspose.psd.RectangleF .

**Returns:**
float - La coordonnée x qui est la somme de  com.aspose.psd.RectangleF.X  et  com.aspose.psd.RectangleF.Width  de cette structure  com.aspose.psd.RectangleF.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Obtient ou définit la taille de ce  com.aspose.psd.RectangleF .

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Obtient ou définit la coordonnée y du bord supérieur de cette structure  com.aspose.psd.RectangleF .

**Returns:**
float - La coordonnée y du bord supérieur de cette structure  com.aspose.psd.RectangleF.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtient ou définit la largeur de cette structure  com.aspose.psd.RectangleF .

**Returns:**
float - La largeur de cette structure  com.aspose.psd.RectangleF.
### getX() {#getX--}
```
public float getX()
```


Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF .

**Returns:**
float - La coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF.
### getY() {#getY--}
```
public float getY()
```


Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF .

**Returns:**
float - La coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage pour cette  com.aspose.psd.RectangleF  structure.

**Returns:**
int - Le code de hachage pour cette  com.aspose.psd.RectangleF .
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crée et renvoie une copie agrandie de la structure  com.aspose.psd.RectangleF  spécifiée. La copie est agrandie du montant spécifié. Le rectangle original reste inchangé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Le  com.aspose.psd.RectangleF  à copier. Ce rectangle n'est pas modifié. |
| x | float | Le montant pour agrandir horizontalement la copie du rectangle. |
| y | float | Le montant pour agrandir verticalement la copie du rectangle. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Gonfle ce  com.aspose.psd.RectangleF  du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Le montant pour agrandir ce rectangle. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Gonfle cette  com.aspose.psd.RectangleF  structure du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Le montant pour agrandir horizontalement cette structure  com.aspose.psd.RectangleF. |
| y | float | Le montant pour agrandir verticalement cette structure  com.aspose.psd.RectangleF. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Remplace cette  com.aspose.psd.RectangleF  structure par l'intersection d'elle-même et de la structure  com.aspose.psd.RectangleF  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle à intersecter. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Renvoie une structure  com.aspose.psd.RectangleF  qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, une structure  com.aspose.psd.RectangleF  vide est renvoyée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Un premier rectangle à intersecter. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Un deuxième rectangle à intersecter. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Détermine si ce rectangle intersecte avec  rect .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle à tester. |

**Returns:**
boolean - Cette méthode renvoie true si une intersection existe.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si la propriété  com.aspose.psd.RectangleF.Width  ou  com.aspose.psd.RectangleF.Height  de ce  com.aspose.psd.RectangleF  a une valeur zéro.

**Returns:**
boolean - Cette propriété renvoie true si la propriété  com.aspose.psd.RectangleF.Width  ou  com.aspose.psd.RectangleF.Height  de ce  com.aspose.psd.RectangleF  a une valeur de zéro ; sinon, false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
booléen
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Multiplie les valeurs du rectangle actuel pour transformer les valeurs d'échelle verticale et horizontale de la matrice et renvoie une nouvelle instance [RectangleF](../../com.aspose.psd/rectanglef) avec les valeurs résultantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transformMatrix | double[] | La matrice de transformation du calque. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


Normalise le rectangle en rendant sa largeur et sa hauteur positives, la gauche inférieure à la droite et le haut inférieur au bas.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | Le montant pour décaler l'emplacement. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Le montant pour décaler l'emplacement horizontalement. |
| y | float | Le montant pour décaler l'emplacement verticalement. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implémente l'opérateur /.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle. |
| diviseur | float | Le diviseur. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Teste si deux structures  com.aspose.psd.RectangleF  ont la même position et la même taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | La structure com.aspose.psd.RectangleF qui se trouve à gauche de l'opérateur d'égalité. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | La structure com.aspose.psd.RectangleF qui se trouve à droite de l'opérateur d'égalité. |

**Returns:**
boolean - Cet opérateur renvoie true si les deux structures com.aspose.psd.RectangleF spécifiées ont des propriétés com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width et com.aspose.psd.RectangleF.Height égales.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Teste si deux structures  com.aspose.psd.RectangleF  diffèrent en position ou en taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | La structure com.aspose.psd.RectangleF qui se trouve à gauche de l'opérateur d'inégalité. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | La structure com.aspose.psd.RectangleF qui se trouve à droite de l'opérateur d'inégalité. |

**Returns:**
boolean - Cet opérateur renvoie true si l'une des propriétés com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width ou com.aspose.psd.RectangleF.Height des deux structures com.aspose.psd.RectangleF est différente ; sinon false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implémente l'opérateur \*.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Le rectangle. |
| multiplicateur | float | Le multiplicateur. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Obtient ou définit la coordonnée y qui est la somme de  com.aspose.psd.RectangleF.Y  et  com.aspose.psd.RectangleF.Height  de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Obtient ou définit la hauteur de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Obtient ou définit la coordonnée x du bord gauche de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Obtient ou définit les coordonnées du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Obtient ou définit la coordonnée x qui est la somme de  com.aspose.psd.RectangleF.X  et  com.aspose.psd.RectangleF.Width  de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Obtient ou définit la taille de ce  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Obtient ou définit la coordonnée y du bord supérieur de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Obtient ou définit la largeur de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Convertit un [RectangleF](../../com.aspose.psd/rectanglef) en une structure [Rectangle](../../com.aspose.psd/rectangle) avec des valeurs de rectangle tronquées.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Convertit les attributs de ce  com.aspose.psd.RectangleF  en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une chaîne qui contient la position, la largeur et la hauteur de cette structure com.aspose.psd.RectangleF.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Convertit la structure  com.aspose.psd.Rectangle  spécifiée en une structure  com.aspose.psd.RectangleF  .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La structure com.aspose.psd.Rectangle à convertir. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crée le plus petit rectangle possible qui peut contenir les deux rectangles formant une union.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Un premier rectangle à unir. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Un deuxième rectangle à unir. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

