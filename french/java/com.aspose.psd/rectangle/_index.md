---
title: "Rectangle"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle."
type: docs
weight: 88
url: /fr/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initialise une nouvelle instance de la structure  com.aspose.psd.Rectangle  avec l'emplacement et la taille spécifiés. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Initialise une nouvelle instance de la structure  com.aspose.psd.Rectangle  avec l'emplacement et la taille spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Convertit la structure  com.aspose.psd.RectangleF  spécifiée en une structure  com.aspose.psd.Rectangle  en arrondissant les valeurs de  com.aspose.psd.RectangleF  à l'entier supérieur suivant. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Détermine si le point spécifié est contenu dans cette structure  com.aspose.psd.Rectangle . |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Détermine si la région rectangulaire représentée par  rect  est entièrement contenue dans cette structure  com.aspose.psd.Rectangle . |
| [contains(int x, int y)](#contains-int-int-) | Détermine si le point spécifié est contenu dans cette structure  com.aspose.psd.Rectangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste si  obj  est une structure  com.aspose.psd.Rectangle  avec le même emplacement et la même taille que cette structure  com.aspose.psd.Rectangle . |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Crée une structure  com.aspose.psd.Rectangle  avec les emplacements de bord spécifiés. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Crée un nouveau  Rectangle  à partir de deux points spécifiés. |
| [getBottom()](#getBottom--) | Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés  com.aspose.psd.Rectangle.Y  et  com.aspose.psd.Rectangle.Height  de cette structure  com.aspose.psd.Rectangle . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure  com.aspose.psd.Rectangle  dont les valeurs  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  et  com.aspose.psd.Rectangle.Height  sont définies à zéro. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur de cette structure  com.aspose.psd.Rectangle . |
| [getLeft()](#getLeft--) | Obtient ou définit la coordonnée x du bord gauche de cette structure  com.aspose.psd.Rectangle . |
| [getLocation()](#getLocation--) | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle . |
| [getRight()](#getRight--) | Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés  com.aspose.psd.Rectangle.X  et  com.aspose.psd.Rectangle.Width  de cette structure  com.aspose.psd.Rectangle . |
| [getSize()](#getSize--) | Obtient ou définit la taille de cette structure  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Obtient ou définit la coordonnée y du bord supérieur de cette structure  com.aspose.psd.Rectangle . |
| [getWidth()](#getWidth--) | Obtient la largeur de cette structure  com.aspose.psd.Rectangle . |
| [getX()](#getX--) | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle . |
| [getY()](#getY--) | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle . |
| [hashCode()](#hashCode--) | Renvoie le code de hachage de cette structure  com.aspose.psd.Rectangle . |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Crée et renvoie une copie gonflée de la structure  com.aspose.psd.Rectangle  spécifiée. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Gonfle cette structure  com.aspose.psd.Rectangle  du montant spécifié. |
| [inflate(int width, int height)](#inflate-int-int-) | Gonfle cette structure  com.aspose.psd.Rectangle  du montant spécifié. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Remplace cette structure  com.aspose.psd.Rectangle  par l'intersection d'elle-même et de la structure  com.aspose.psd.Rectangle  spécifiée. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Renvoie une troisième structure  com.aspose.psd.Rectangle  qui représente l'intersection de deux autres structures  com.aspose.psd.Rectangle . |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Détermine si ce rectangle intersecte avec  rect . |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si toutes les propriétés numériques de cette structure  com.aspose.psd.Rectangle  ont des valeurs égales à zéro. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Obtient une valeur indiquant si ce  Rectangle  est au moins partiellement visible |
| [normalize()](#normalize--) | Normalise le rectangle en rendant sa largeur et sa hauteur positives, la gauche inférieure à la droite et le haut inférieur au bas. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(int x, int y)](#offset-int-int-) | Ajuste la position de ce rectangle du montant spécifié. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Teste si deux structures  com.aspose.psd.Rectangle  ont la même position et la même taille. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Teste si deux structures  com.aspose.psd.Rectangle  diffèrent par leur position ou leur taille. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Convertit le  com.aspose.psd.RectangleF  spécifié en un  com.aspose.psd.Rectangle  en arrondissant les valeurs du  com.aspose.psd.RectangleF  aux entiers les plus proches. |
| [setBottom(int value)](#setBottom-int-) | Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés  com.aspose.psd.Rectangle.Y  et  com.aspose.psd.Rectangle.Height  de cette structure  com.aspose.psd.Rectangle . |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit la hauteur de cette structure  com.aspose.psd.Rectangle . |
| [setLeft(int value)](#setLeft-int-) | Obtient ou définit la coordonnée x du bord gauche de cette structure  com.aspose.psd.Rectangle . |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle . |
| [setRight(int value)](#setRight-int-) | Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés  com.aspose.psd.Rectangle.X  et  com.aspose.psd.Rectangle.Width  de cette structure  com.aspose.psd.Rectangle . |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Obtient ou définit la taille de cette structure  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Obtient ou définit la coordonnée y du bord supérieur de cette structure  com.aspose.psd.Rectangle . |
| [setWidth(int value)](#setWidth-int-) | Définit la largeur de cette structure  com.aspose.psd.Rectangle . |
| [setX(int value)](#setX-int-) | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle . |
| [setY(int value)](#setY-int-) | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle . |
| [toString()](#toString--) | Convertit les attributs de cette structure  com.aspose.psd.Rectangle  en une chaîne lisible par l'homme. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Convertit le  com.aspose.psd.RectangleF  spécifié en un  com.aspose.psd.Rectangle  en tronquant les valeurs du  com.aspose.psd.RectangleF . |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Obtient une structure  com.aspose.psd.Rectangle  qui contient l'union de deux structures  com.aspose.psd.Rectangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initialise une nouvelle instance de la structure  com.aspose.psd.Rectangle  avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle. |
| largeur | int | La largeur du rectangle. |
| hauteur | int | La hauteur du rectangle. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Initialise une nouvelle instance de la structure  com.aspose.psd.Rectangle  avec l'emplacement et la taille spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [Size](../../com.aspose.psd/size) | Un  com.aspose.psd.Size  qui représente la largeur et la hauteur de la région rectangulaire. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Convertit la structure  com.aspose.psd.RectangleF  spécifiée en une structure  com.aspose.psd.Rectangle  en arrondissant les valeurs de  com.aspose.psd.RectangleF  à l'entier supérieur suivant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | La structure  com.aspose.psd.RectangleF  à convertir. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Détermine si le point spécifié est contenu dans cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  com.aspose.psd.Point  à tester. |

**Returns:**
booléen - Cette méthode renvoie true si le point représenté par  point  est contenu dans cette structure  com.aspose.psd.Rectangle ; sinon false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Détermine si la région rectangulaire représentée par  rect  est entièrement contenue dans cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Le  com.aspose.psd.Rectangle  à tester. |

**Returns:**
booléen - Cette méthode renvoie true si la région rectangulaire représentée par  rect  est entièrement contenue dans cette structure  com.aspose.psd.Rectangle ; sinon false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Détermine si le point spécifié est contenu dans cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns:**
booléen - Cette méthode renvoie true si le point défini par  x  et  y  est contenu dans cette structure  com.aspose.psd.Rectangle ; sinon false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste si  obj  est une structure  com.aspose.psd.Rectangle  avec le même emplacement et la même taille que cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le  System.Object  à tester. |

**Returns:**
booléen - Cette méthode renvoie true si  obj  est une structure  com.aspose.psd.Rectangle  et que ses propriétés  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , et  com.aspose.psd.Rectangle.Height  sont égales aux propriétés correspondantes de cette structure  com.aspose.psd.Rectangle ; sinon false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Crée une structure  com.aspose.psd.Rectangle  avec les emplacements de bord spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | int | La coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle. |
| top | int | La coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle. |
| right | int | La coordonnée x du coin inférieur droit de cette structure  com.aspose.psd.Rectangle. |
| bottom | int | La coordonnée y du coin inférieur droit de cette structure  com.aspose.psd.Rectangle. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crée un nouveau  Rectangle  à partir de deux points spécifiés. Les deux côtés verticaux du  Rectangle  créé seront égaux aux points  point1  et  point2 . Ce seront généralement les sommets opposés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Le premier  Point  du nouveau rectangle. |
| point2 | [Point](../../com.aspose.psd/point) | Le deuxième  Point  du nouveau rectangle. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés  com.aspose.psd.Rectangle.Y  et  com.aspose.psd.Rectangle.Height  de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - La coordonnée y qui est la somme de  com.aspose.psd.Rectangle.Y  et  com.aspose.psd.Rectangle.Height  de ce  com.aspose.psd.Rectangle .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Obtient une nouvelle instance de la structure  com.aspose.psd.Rectangle  dont les valeurs  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  et  com.aspose.psd.Rectangle.Height  sont définies à zéro.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit la hauteur de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - La hauteur de cette structure  com.aspose.psd.Rectangle.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Obtient ou définit la coordonnée x du bord gauche de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - La coordonnée x du bord gauche de cette structure  com.aspose.psd.Rectangle.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Obtient ou définit les coordonnées du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle .

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés  com.aspose.psd.Rectangle.X  et  com.aspose.psd.Rectangle.Width  de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - La coordonnée x qui est la somme de  com.aspose.psd.Rectangle.X  et  com.aspose.psd.Rectangle.Width  de ce  com.aspose.psd.Rectangle .
### getSize() {#getSize--}
```
public Size getSize()
```


Obtient ou définit la taille de cette structure  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Obtient ou définit la coordonnée y du bord supérieur de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - La coordonnée y du bord supérieur de cette structure  com.aspose.psd.Rectangle.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - La largeur de cette structure  com.aspose.psd.Rectangle.
### getX() {#getX--}
```
public int getX()
```


Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - La coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle.
### getY() {#getY--}
```
public int getY()
```


Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - La coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage de cette structure  com.aspose.psd.Rectangle .

**Returns:**
int - Un entier qui représente le code de hachage de ce rectangle.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Crée et renvoie une copie gonflée de la structure  com.aspose.psd.Rectangle  spécifiée. La copie est gonflée du montant spécifié. La structure  com.aspose.psd.Rectangle  originale reste inchangée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Le  com.aspose.psd.Rectangle  avec lequel commencer. Ce rectangle n'est pas modifié. |
| x | int | Le montant pour gonfler ce com.aspose.psd.Rectangle horizontalement. |
| y | int | Le montant pour gonfler ce com.aspose.psd.Rectangle verticalement. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Gonfle cette structure  com.aspose.psd.Rectangle  du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Le montant pour agrandir ce rectangle. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Gonfle cette structure  com.aspose.psd.Rectangle  du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | Le montant pour gonfler ce com.aspose.psd.Rectangle horizontalement. |
| hauteur | int | Le montant pour gonfler ce com.aspose.psd.Rectangle verticalement. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Remplace cette structure  com.aspose.psd.Rectangle  par l'intersection d'elle-même et de la structure  com.aspose.psd.Rectangle  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Le com.aspose.psd.Rectangle avec lequel intersecter. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Renvoie une troisième structure com.aspose.psd.Rectangle qui représente l'intersection de deux autres structures com.aspose.psd.Rectangle. S'il n'y a pas d'intersection, une com.aspose.psd.Rectangle vide est renvoyée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Un premier rectangle à intersecter. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Un deuxième rectangle à intersecter. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Détermine si ce rectangle intersecte avec  rect .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle à tester. |

**Returns:**
booléen - Cette méthode renvoie true s'il y a une intersection, sinon false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si toutes les propriétés numériques de cette structure  com.aspose.psd.Rectangle  ont des valeurs égales à zéro.

**Returns:**
booléen - Cette propriété renvoie true si les propriétés com.aspose.psd.Rectangle.Width, com.aspose.psd.Rectangle.Height, com.aspose.psd.Rectangle.X et com.aspose.psd.Rectangle.Y de ce com.aspose.psd.Rectangle ont toutes la valeur zéro ; sinon, false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
booléen
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Obtient une valeur indiquant si ce  Rectangle  est au moins partiellement visible

**Returns:**
booléen - true si ce Rectangle est au moins partiellement visible ; sinon, false.
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Valeur du décalage de l'emplacement. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | Le décalage horizontal. |
| y | int | Le décalage vertical. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Teste si deux structures  com.aspose.psd.Rectangle  ont la même position et la même taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | La structure com.aspose.psd.Rectangle qui se trouve à gauche de l'opérateur d'égalité. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | La structure com.aspose.psd.Rectangle qui se trouve à droite de l'opérateur d'égalité. |

**Returns:**
booléen - Cet opérateur renvoie true si les deux structures com.aspose.psd.Rectangle ont des propriétés com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width et com.aspose.psd.Rectangle.Height égales.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Teste si deux structures  com.aspose.psd.Rectangle  diffèrent par leur position ou leur taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | La structure com.aspose.psd.Rectangle qui se trouve à gauche de l'opérateur d'inégalité. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | La structure com.aspose.psd.Rectangle qui se trouve à droite de l'opérateur d'inégalité. |

**Returns:**
booléen - Cet opérateur renvoie true si l'une des propriétés com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width ou com.aspose.psd.Rectangle.Height des deux structures com.aspose.psd.Rectangle est différente ; sinon false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Convertit le  com.aspose.psd.RectangleF  spécifié en un  com.aspose.psd.Rectangle  en arrondissant les valeurs du  com.aspose.psd.RectangleF  aux entiers les plus proches.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Le com.aspose.psd.RectangleF à convertir. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés  com.aspose.psd.Rectangle.Y  et  com.aspose.psd.Rectangle.Height  de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée y qui est la somme de com.aspose.psd.Rectangle.Y et com.aspose.psd.Rectangle.Height de ce com.aspose.psd.Rectangle. |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit la hauteur de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La hauteur de cette structure com.aspose.psd.Rectangle. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Obtient ou définit la coordonnée x du bord gauche de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée x du bord gauche de cette structure com.aspose.psd.Rectangle. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Obtient ou définit les coordonnées du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Un Point qui représente le coin supérieur gauche de cette structure com.aspose.psd.Rectangle. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés  com.aspose.psd.Rectangle.X  et  com.aspose.psd.Rectangle.Width  de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée x qui est la somme de com.aspose.psd.Rectangle.X et com.aspose.psd.Rectangle.Width de ce com.aspose.psd.Rectangle. |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Obtient ou définit la taille de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Un com.aspose.psd.Size qui représente la largeur et la hauteur de cette structure com.aspose.psd.Rectangle. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtient ou définit la coordonnée y du bord supérieur de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée y du bord supérieur de cette structure com.aspose.psd.Rectangle. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Définit la largeur de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La largeur de cette structure com.aspose.psd.Rectangle. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée x du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La coordonnée y du coin supérieur gauche de cette structure  com.aspose.psd.Rectangle. |

### toString() {#toString--}
```
public String toString()
```


Convertit les attributs de cette structure  com.aspose.psd.Rectangle  en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une chaîne qui contient la position, la largeur et la hauteur de cette structure com.aspose.psd.Rectangle.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Convertit le  com.aspose.psd.RectangleF  spécifié en un  com.aspose.psd.Rectangle  en tronquant les valeurs du  com.aspose.psd.RectangleF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Le com.aspose.psd.RectangleF à convertir. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Obtient une structure  com.aspose.psd.Rectangle  qui contient l'union de deux structures  com.aspose.psd.Rectangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Un premier rectangle à unir. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Un deuxième rectangle à unir. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

