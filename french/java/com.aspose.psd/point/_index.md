---
title: "Point"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente une paire ordonnée de coordonnées entières x et y qui définit un point dans un plan bidimensionnel."
type: docs
weight: 82
url: /fr/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Représente une paire ordonnée de coordonnées entières x et y qui définit un point dans un plan bidimensionnel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initialise une nouvelle instance de la structure Aspose.Imaging.Point avec les coordonnées spécifiées. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Initialise une nouvelle instance de la structure Aspose.Imaging.Point à partir de la structure Aspose.Imaging.Size. |
| [Point(int dw)](#Point-int-) | Initialise une nouvelle instance de la structure Aspose.Imaging.Point en utilisant des coordonnées spécifiées par une valeur entière. |
## Champs

| Champ | Description |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Représente le format du point. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Ajoute le Aspose.Imaging.Size spécifié au Aspose.Imaging.Point spécifié. |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Convertit le Aspose.Imaging.PointF spécifié en un Aspose.Imaging.Point en arrondissant les valeurs du Aspose.Imaging.PointF aux entiers supérieurs les plus proches. |
| [equals(Object obj)](#equals-java.lang.Object-) | Spécifie si ce  Aspose.Imaging.Point  contient les mêmes coordonnées que le  System.Object  spécifié. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure  Aspose.Imaging.Point  dont les valeurs  Aspose.Imaging.Point.X  et  Aspose.Imaging.Point.Y  sont définies à zéro. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x de ce  Aspose.Imaging.Point . |
| [getY()](#getY--) | Obtient ou définit la coordonnée y de ce  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour ce  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si ce  Aspose.Imaging.Point  est vide. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Translater ce  Aspose.Imaging.Point  par le  Aspose.Imaging.Point  spécifié. |
| [offset(int dx, int dy)](#offset-int-int-) | Translater ce  Aspose.Imaging.Point  du montant spécifié. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Translater un  Aspose.Imaging.Point  d'une  Aspose.Imaging.Size  donnée. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Compare deux objets  Aspose.Imaging.Point . |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Compare deux objets  Aspose.Imaging.Point . |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Translater un  Aspose.Imaging.Point  par le négatif d'une  Aspose.Imaging.Size  donnée. |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Convertit le  Aspose.Imaging.PointF  spécifié en un objet  Aspose.Imaging.Point  en arrondissant les valeurs du  Aspose.Imaging.Point  à l'entier le plus proche. |
| [setX(int value)](#setX-int-) | Obtient ou définit la coordonnée x de ce  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | Obtient ou définit la coordonnée y de ce  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Renvoie le résultat de la soustraction de la  Aspose.Imaging.Size  spécifiée du  Aspose.Imaging.Point  spécifié. |
| [toString()](#toString--) | Convertit ce  Aspose.Imaging.Point  en une chaîne lisible par l'homme. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Convertit la structure  Point  spécifiée en la structure  PointF . |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Convertit la structure  Aspose.Imaging.Point  spécifiée en une structure  Aspose.Imaging.Size . |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Convertit le  Aspose.Imaging.PointF  spécifié en un  Aspose.Imaging.Point  en tronquant les valeurs du  Aspose.Imaging.Point . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Initialise une nouvelle instance de la structure Aspose.Imaging.Point avec les coordonnées spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La position horizontale du point. |
| y | int | La position verticale du point. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Initialise une nouvelle instance de la structure Aspose.Imaging.Point à partir de la structure Aspose.Imaging.Size.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Contient les nouvelles coordonnées du point. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initialise une nouvelle instance de la structure Aspose.Imaging.Point en utilisant des coordonnées spécifiées par une valeur entière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dw | int | Un entier 32 bits qui spécifie les coordonnées du nouveau point. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Représente le format du point.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Ajoute le Aspose.Imaging.Size spécifié au Aspose.Imaging.Point spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  Aspose.Imaging.Point  à ajouter. |
| size | [Size](../../com.aspose.psd/size) | Le  Aspose.Imaging.Size  à ajouter au  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Convertit le Aspose.Imaging.PointF spécifié en un Aspose.Imaging.Point en arrondissant les valeurs du Aspose.Imaging.PointF aux entiers supérieurs les plus proches.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  Aspose.Imaging.PointF  à convertir. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Spécifie si ce  Aspose.Imaging.Point  contient les mêmes coordonnées que le  System.Object  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le  System.Object  à tester. |

**Returns:**
booléen - Vrai si  obj  est un  Aspose.Imaging.Point  et possède les mêmes coordonnées que ce  Aspose.Imaging.Point .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Obtient une nouvelle instance de la structure  Aspose.Imaging.Point  dont les valeurs  Aspose.Imaging.Point.X  et  Aspose.Imaging.Point.Y  sont définies à zéro.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Obtient ou définit la coordonnée x de ce  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Obtient ou définit la coordonnée y de ce  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour ce  Aspose.Imaging.Point .

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si ce  Aspose.Imaging.Point  est vide.

**Returns:**
booléen - Vrai si à la fois  Aspose.Imaging.Point.X  et  Aspose.Imaging.Point.Y  sont 0 ; sinon, faux.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

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




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Translater ce  Aspose.Imaging.Point  par le  Aspose.Imaging.Point  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  Aspose.Imaging.Point  utilisé pour décaler ce  Aspose.Imaging.Point . |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Translater ce  Aspose.Imaging.Point  du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | int | Le montant pour décaler la coordonnée x. |
| dy | int | Le montant pour décaler la coordonnée y. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Translater un  Aspose.Imaging.Point  d'une  Aspose.Imaging.Size  donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  Aspose.Imaging.Point  à translater. |
| size | [Size](../../com.aspose.psd/size) | Un  Aspose.Imaging.Size  qui spécifie la paire de nombres à ajouter aux coordonnées du  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Compare deux objets  Aspose.Imaging.Point . Le résultat indique si les valeurs des propriétés  Aspose.Imaging.Point.X  et  Aspose.Imaging.Point.Y  des deux objets  Aspose.Imaging.Point  sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Un premier  Aspose.Imaging.Point  à comparer. |
| point2 | [Point](../../com.aspose.psd/point) | Un second  Aspose.Imaging.Point  à comparer. |

**Returns:**
booléen - Vrai si les valeurs  Aspose.Imaging.Point.X  et  Aspose.Imaging.Point.Y  de  point1  et  point2  sont égales ; sinon, faux.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Compare deux objets  Aspose.Imaging.Point . Le résultat indique si les valeurs des propriétés  Aspose.Imaging.Point.X  ou  Aspose.Imaging.Point.Y  des deux objets  Aspose.Imaging.Point  sont différentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Un premier  Aspose.Imaging.Point  à comparer. |
| point2 | [Point](../../com.aspose.psd/point) | Un second  Aspose.Imaging.Point  à comparer. |

**Returns:**
booléen - Vrai si les valeurs de l'une ou l'autre des propriétés  Aspose.Imaging.Point.X  ou  Aspose.Imaging.Point.Y  de  point1  et  point2  diffèrent ; sinon, faux.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Translater un  Aspose.Imaging.Point  par le négatif d'une  Aspose.Imaging.Size  donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  Aspose.Imaging.Point  à translater. |
| size | [Size](../../com.aspose.psd/size) | Un  Aspose.Imaging.Size  qui spécifie la paire de nombres à soustraire des coordonnées du  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Convertit le  Aspose.Imaging.PointF  spécifié en un objet  Aspose.Imaging.Point  en arrondissant les valeurs du  Aspose.Imaging.Point  à l'entier le plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  Aspose.Imaging.PointF  à convertir. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtient ou définit la coordonnée x de ce  Aspose.Imaging.Point .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtient ou définit la coordonnée y de ce  Aspose.Imaging.Point .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Renvoie le résultat de la soustraction de la  Aspose.Imaging.Size  spécifiée du  Aspose.Imaging.Point  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  Aspose.Imaging.Point  à soustraire de. |
| size | [Size](../../com.aspose.psd/size) | Le  Aspose.Imaging.Size  à soustraire du  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Convertit ce  Aspose.Imaging.Point  en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une System.String qui représente cette instance.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Convertit la structure  Point  spécifiée en la structure  PointF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  Point  à convertir. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Convertit la structure  Aspose.Imaging.Point  spécifiée en une structure  Aspose.Imaging.Size .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  Aspose.Imaging.Point  à convertir. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Convertit le  Aspose.Imaging.PointF  spécifié en un  Aspose.Imaging.Point  en tronquant les valeurs du  Aspose.Imaging.Point .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  Aspose.Imaging.PointF  à convertir. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

