---
title: "Taille"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente la taille."
type: docs
weight: 98
url: /fr/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Représente la taille.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | Initialise une nouvelle instance de la structure  Aspose.Imaging.Size  à partir du  Aspose.Imaging.Point  spécifié. |
| [Size(int width, int height)](#Size-int-int-) | Initialise une nouvelle instance de la structure  Aspose.Imaging.Size  à partir des dimensions spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | Ajoute la largeur et la hauteur d'une structure  Aspose.Imaging.Size  à la largeur et la hauteur d'une autre structure  Aspose.Imaging.Size . |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | Convertit la structure  Aspose.Imaging.SizeF  spécifiée en une structure  Aspose.Imaging.Size  en arrondissant les valeurs de la structure  Aspose.Imaging.Size  à l'entier supérieur le plus proche. |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste pour voir si l'objet spécifié est un  Aspose.Imaging.Size  avec les mêmes dimensions que ce  Aspose.Imaging.Size . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtient une nouvelle instance de la structure  Aspose.Imaging.Size  qui a les valeurs  Aspose.Imaging.Size.Width  et  Aspose.Imaging.Size.Height  définies à zéro. |
| [getHeight()](#getHeight--) | Obtient ou définit le composant vertical de ce  Aspose.Imaging.Size . |
| [getWidth()](#getWidth--) | Obtient ou définit le composant horizontal de ce  Aspose.Imaging.Size . |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette structure  Aspose.Imaging.Size . |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si ce  Aspose.Imaging.Size  a une largeur et une hauteur de 0. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | Ajoute la largeur et la hauteur d'une structure  Aspose.Imaging.Size  à la largeur et la hauteur d'une autre structure  Aspose.Imaging.Size . |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | Teste si deux  Aspose.Imaging.Size  structures sont égales. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | Teste si deux  Aspose.Imaging.Size  structures sont différentes. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | Soustrait la largeur et la hauteur d'une  Aspose.Imaging.Size  structure de la largeur et de la hauteur d'une autre  Aspose.Imaging.Size  structure. |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | Convertit la structure  Aspose.Imaging.SizeF  spécifiée en une structure  Aspose.Imaging.Size  en arrondissant les valeurs de la structure  Aspose.Imaging.SizeF  aux valeurs entières les plus proches. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit le composant vertical de ce  Aspose.Imaging.Size . |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit le composant horizontal de ce  Aspose.Imaging.Size . |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | Soustrait la largeur et la hauteur d'une  Aspose.Imaging.Size  structure de la largeur et de la hauteur d'une autre  Aspose.Imaging.Size  structure. |
| [toString()](#toString--) | Crée une chaîne lisible par l'homme qui représente ce  Aspose.Imaging.Size . |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | Convertit le  Aspose.Imaging.Size  spécifié en un  Aspose.Imaging.Point . |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | Convertit le  Aspose.Imaging.Size  spécifié en un  Aspose.Imaging.SizeF . |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | Convertit la structure  Aspose.Imaging.SizeF  spécifiée en une structure  Aspose.Imaging.Size  en tronquant les valeurs de la structure  Aspose.Imaging.SizeF  aux entiers immédiatement inférieurs. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


Initialise une nouvelle instance de la structure  Aspose.Imaging.Size  à partir du  Aspose.Imaging.Point  spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Le  Aspose.Imaging.Point  à partir duquel initialiser ce  Aspose.Imaging.Size . |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialise une nouvelle instance de la structure  Aspose.Imaging.Size  à partir des dimensions spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | Le composant largeur du nouveau  Aspose.Imaging.Size . |
| hauteur | int | Le composant hauteur du nouveau  Aspose.Imaging.Size . |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


Ajoute la largeur et la hauteur d'une structure  Aspose.Imaging.Size  à la largeur et la hauteur d'une autre structure  Aspose.Imaging.Size .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Le premier  Aspose.Imaging.Size  à ajouter. |
| size2 | [Size](../../com.aspose.psd/size) | Le deuxième  Aspose.Imaging.Size  à ajouter. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


Convertit la structure  Aspose.Imaging.SizeF  spécifiée en une structure  Aspose.Imaging.Size  en arrondissant les valeurs de la structure  Aspose.Imaging.Size  à l'entier supérieur le plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | La structure  Aspose.Imaging.SizeF  à convertir. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste pour voir si l'objet spécifié est un  Aspose.Imaging.Size  avec les mêmes dimensions que ce  Aspose.Imaging.Size .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le  System.Object  à tester. |

**Returns:**
booléen - Vrai si  obj  est un  Aspose.Imaging.Size  et possède la même largeur et hauteur que ce  Aspose.Imaging.Size ; sinon, faux.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Obtient une nouvelle instance de la structure  Aspose.Imaging.Size  qui a les valeurs  Aspose.Imaging.Size.Width  et  Aspose.Imaging.Size.Height  définies à zéro.

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit le composant vertical de ce  Aspose.Imaging.Size .

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient ou définit le composant horizontal de ce  Aspose.Imaging.Size .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette structure  Aspose.Imaging.Size .

**Returns:**
int - Une valeur entière qui spécifie une valeur de hachage pour cette structure  Aspose.Imaging.Size .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si ce  Aspose.Imaging.Size  a une largeur et une hauteur de 0.

**Returns:**
booléen
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Ajoute la largeur et la hauteur d'une structure  Aspose.Imaging.Size  à la largeur et la hauteur d'une autre structure  Aspose.Imaging.Size .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Le premier  Aspose.Imaging.Size  à ajouter. |
| size2 | [Size](../../com.aspose.psd/size) | Le deuxième  Aspose.Imaging.Size  à ajouter. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Teste si deux  Aspose.Imaging.Size  structures sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | La structure  Aspose.Imaging.Size  du côté gauche de l'opérateur d'égalité. |
| size2 | [Size](../../com.aspose.psd/size) | La structure  Aspose.Imaging.Size  du côté droit de l'opérateur d'égalité. |

**Returns:**
booléen - Vrai si  size1  et  size2  ont la même largeur et hauteur ; sinon, faux.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Teste si deux  Aspose.Imaging.Size  structures sont différentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | La structure  Aspose.Imaging.Size  du côté gauche de l'opérateur d'inégalité. |
| size2 | [Size](../../com.aspose.psd/size) | La structure  Aspose.Imaging.Size  du côté droit de l'opérateur d'inégalité. |

**Returns:**
booléen - Vrai si  size1  et  size2  diffèrent soit en largeur soit en hauteur ; faux si  size1  et  size2  sont égaux.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Soustrait la largeur et la hauteur d'une  Aspose.Imaging.Size  structure de la largeur et de la hauteur d'une autre  Aspose.Imaging.Size  structure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | La structure  Aspose.Imaging.Size  du côté gauche de l'opérateur de soustraction. |
| size2 | [Size](../../com.aspose.psd/size) | La structure  Aspose.Imaging.Size  du côté droit de l'opérateur de soustraction. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


Convertit la structure  Aspose.Imaging.SizeF  spécifiée en une structure  Aspose.Imaging.Size  en arrondissant les valeurs de la structure  Aspose.Imaging.SizeF  aux valeurs entières les plus proches.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | La structure  Aspose.Imaging.SizeF  à convertir. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit le composant vertical de ce  Aspose.Imaging.Size .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtient ou définit le composant horizontal de ce  Aspose.Imaging.Size .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Soustrait la largeur et la hauteur d'une  Aspose.Imaging.Size  structure de la largeur et de la hauteur d'une autre  Aspose.Imaging.Size  structure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | La structure  Aspose.Imaging.Size  du côté gauche de l'opérateur de soustraction. |
| size2 | [Size](../../com.aspose.psd/size) | La structure  Aspose.Imaging.Size  du côté droit de l'opérateur de soustraction. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Crée une chaîne lisible par l'homme qui représente ce  Aspose.Imaging.Size .

**Returns:**
java.lang.String - Une chaîne qui représente ce  Aspose.Imaging.Size .
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


Convertit le  Aspose.Imaging.Size  spécifié en un  Aspose.Imaging.Point .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Le  Aspose.Imaging.Size  à convertir. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


Convertit le  Aspose.Imaging.Size  spécifié en un  Aspose.Imaging.SizeF .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Le  Aspose.Imaging.Size  à convertir. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


Convertit la structure  Aspose.Imaging.SizeF  spécifiée en une structure  Aspose.Imaging.Size  en tronquant les valeurs de la structure  Aspose.Imaging.SizeF  aux entiers immédiatement inférieurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | La structure  Aspose.Imaging.SizeF  à convertir. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

