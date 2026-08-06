---
title: "PointF"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente une paire ordonnée de coordonnées flottantes x et y qui définit un point dans un plan à deux dimensions."
type: docs
weight: 83
url: /fr/java/com.aspose.psd/pointf/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Représente une paire ordonnée de coordonnées flottantes x et y qui définit un point dans un plan à deux dimensions.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Initialise une nouvelle instance de la structure com.aspose.psd.PointF avec les coordonnées spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(PointF that)](#CloneTo-com.aspose.psd.PointF-) |  |
| [add(PointF point, Size size)](#add-com.aspose.psd.PointF-com.aspose.psd.Size-) | Déplace un com.aspose.psd.PointF donné selon la taille com.aspose.psd.Size spécifiée. |
| [add(PointF point, SizeF size)](#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Déplace un com.aspose.psd.PointF donné selon une com.aspose.psd.SizeF spécifiée. |
| [equals(Object obj)](#equals-java.lang.Object-) | Spécifie si ce com.aspose.psd.PointF contient les mêmes coordonnées que l'objet System.Object spécifié. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure com.aspose.psd.PointF dont les valeurs com.aspose.psd.PointF.X et com.aspose.psd.PointF.Y sont définies à zéro. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x de ce com.aspose.psd.PointF. |
| [getY()](#getY--) | Obtient ou définit la coordonnée y de ce com.aspose.psd.PointF. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette structure com.aspose.psd.PointF. |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si ce com.aspose.psd.PointF est vide. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-) | Déplace un com.aspose.psd.PointF selon une com.aspose.psd.Size donnée. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Déplace le com.aspose.psd.PointF selon la com.aspose.psd.SizeF spécifiée. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Compare deux structures com.aspose.psd.PointF. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Détermine si les coordonnées des points spécifiés ne sont pas égales. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-) | Déplace un com.aspose.psd.PointF par le négatif d'une com.aspose.psd.Size donnée. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Déplace un com.aspose.psd.PointF par le négatif d'une com.aspose.psd.SizeF spécifiée. |
| [setX(float value)](#setX-float-) | Obtient ou définit la coordonnée x de ce com.aspose.psd.PointF. |
| [setY(float value)](#setY-float-) | Obtient ou définit la coordonnée y de ce com.aspose.psd.PointF. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-) | Déplace un com.aspose.psd.PointF par le négatif d'une taille spécifiée. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Déplace un com.aspose.psd.PointF par le négatif d'une taille spécifiée. |
| [toString()](#toString--) | Convertit ce com.aspose.psd.PointF en une chaîne lisible par l'homme. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Initialise une nouvelle instance de la structure com.aspose.psd.PointF avec les coordonnées spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La position horizontale du point. |
| y | float | La position verticale du point. |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.psd/pointf)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(PointF that) {#CloneTo-com.aspose.psd.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [PointF](../../com.aspose.psd/pointf) |  |

### add(PointF point, Size size) {#add-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF add(PointF point, Size size)
```


Déplace un com.aspose.psd.PointF donné selon la taille com.aspose.psd.Size spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  com.aspose.psd.PointF  à traduire. |
| size | [Size](../../com.aspose.psd/size) | Le  com.aspose.psd.Size  qui spécifie les nombres à ajouter aux coordonnées du  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### add(PointF point, SizeF size) {#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Déplace un com.aspose.psd.PointF donné selon une com.aspose.psd.SizeF spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  com.aspose.psd.PointF  à traduire. |
| size | [SizeF](../../com.aspose.psd/sizef) | Le  com.aspose.psd.SizeF  qui spécifie les nombres à ajouter aux coordonnées du  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Spécifie si ce com.aspose.psd.PointF contient les mêmes coordonnées que l'objet System.Object spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le  System.Object  à tester. |

**Returns:**
boolean - Cette méthode renvoie true si  obj  est un  com.aspose.psd.PointF  et possède les mêmes coordonnées que ce  com.aspose.psd.Point .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Obtient une nouvelle instance de la structure com.aspose.psd.PointF dont les valeurs com.aspose.psd.PointF.X et com.aspose.psd.PointF.Y sont définies à zéro.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getX() {#getX--}
```
public float getX()
```


Obtient ou définit la coordonnée x de ce com.aspose.psd.PointF.

**Returns:**
float
### getY() {#getY--}
```
public float getY()
```


Obtient ou définit la coordonnée y de ce com.aspose.psd.PointF.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette structure com.aspose.psd.PointF.

**Returns:**
int - Une valeur entière qui spécifie une valeur de hachage pour cette structure  com.aspose.psd.PointF .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si ce com.aspose.psd.PointF est vide.

**Returns:**
boolean - True si les deux  com.aspose.psd.PointF.X  et  com.aspose.psd.PointF.Y  sont 0 ; sinon, false.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.psd/pointf) |  |
| obj2 | [PointF](../../com.aspose.psd/pointf) |  |

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




### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Déplace un com.aspose.psd.PointF selon une com.aspose.psd.Size donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  com.aspose.psd.PointF  à traduire. |
| size | [Size](../../com.aspose.psd/size) | Un  com.aspose.psd.Size  qui spécifie la paire de nombres à ajouter aux coordonnées du  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns the translated  com.aspose.psd.PointF .
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Déplace le com.aspose.psd.PointF selon la com.aspose.psd.SizeF spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  com.aspose.psd.PointF  à traduire. |
| size | [SizeF](../../com.aspose.psd/sizef) | Le  com.aspose.psd.SizeF  qui spécifie les nombres à ajouter aux coordonnées x et y du  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Compare deux  com.aspose.psd.PointF  structures. Le résultat indique si les valeurs des propriétés  com.aspose.psd.PointF.X  et  com.aspose.psd.PointF.Y  des deux  com.aspose.psd.PointF  structures sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Un premier  com.aspose.psd.PointF  à comparer. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Un deuxième  com.aspose.psd.PointF  à comparer. |

**Returns:**
boolean - True si les valeurs  com.aspose.psd.PointF.X  et  com.aspose.psd.PointF.Y  des structures  com.aspose.psd.PointF  première et deuxième sont égales ; sinon, false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Détermine si les coordonnées des points spécifiés ne sont pas égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Un premier  com.aspose.psd.PointF  à comparer. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Un deuxième  com.aspose.psd.PointF  à comparer. |

**Returns:**
boolean - True pour indiquer que les valeurs  com.aspose.psd.PointF.X  et  com.aspose.psd.PointF.Y  de  point1  et  point2  ne sont pas égales ; sinon, false.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Déplace un com.aspose.psd.PointF par le négatif d'une com.aspose.psd.Size donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  à traduire. |
| size | [Size](../../com.aspose.psd/size) | Un  com.aspose.psd.Size  qui spécifie les nombres à soustraire des coordonnées x et y du  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Déplace un com.aspose.psd.PointF par le négatif d'une com.aspose.psd.SizeF spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  com.aspose.psd.PointF  à traduire. |
| size | [SizeF](../../com.aspose.psd/sizef) | Le  com.aspose.psd.SizeF  qui spécifie les nombres à soustraire des coordonnées du  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Obtient ou définit la coordonnée x de ce com.aspose.psd.PointF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Obtient ou définit la coordonnée y de ce com.aspose.psd.PointF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### subtract(PointF point, Size size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Déplace un com.aspose.psd.PointF par le négatif d'une taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  com.aspose.psd.PointF  à traduire. |
| size | [Size](../../com.aspose.psd/size) | Le  com.aspose.psd.Size  qui spécifie les nombres à soustraire des coordonnées du  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### subtract(PointF point, SizeF size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Déplace un com.aspose.psd.PointF par le négatif d'une taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Le  com.aspose.psd.PointF  à traduire. |
| size | [SizeF](../../com.aspose.psd/sizef) | Le  com.aspose.psd.SizeF  qui spécifie les nombres à soustraire des coordonnées du  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### toString() {#toString--}
```
public String toString()
```


Convertit ce com.aspose.psd.PointF en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une chaîne qui représente ce  com.aspose.psd.PointF .
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

