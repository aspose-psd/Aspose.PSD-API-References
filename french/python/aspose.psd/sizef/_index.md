---
title: "Classe SizeF"
type: docs
weight: 4090
url: /fr/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initialise une nouvelle instance de la classe SizeF |
| [SizeF(point)](#SizeF_point_2) | Initialise une nouvelle instance de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) à partir du [PointF](/psd/python-net/aspose.psd/pointf/) spécifié. |
| [SizeF(size)](#SizeF_size_3) | Initialise une nouvelle instance de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) à partir du [SizeF](/psd/python-net/aspose.psd/sizef/) spécifié. |
| [SizeF(width, height)](#SizeF_width_height_4) | Initialise une nouvelle instance de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) à partir des dimensions spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Obtient une nouvelle instance de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) dont les valeurs [SizeF.width](/psd/python-net/aspose.psd/sizef/) et [SizeF.height](/psd/python-net/aspose.psd/sizef/) sont réglées à zéro. |
| height | float | r/w | Obtient ou définit le composant vertical de ce [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | Obtient une valeur indiquant si ce [SizeF](/psd/python-net/aspose.psd/sizef/) a une largeur et une hauteur nulles. |
| width | float | r/w | Obtient ou définit le composant horizontal de ce [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Ajoute la largeur et la hauteur d'une structure [SizeF](/psd/python-net/aspose.psd/sizef/) à la largeur et la hauteur d'une autre structure [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Soustrait la largeur et la hauteur d'une structure [SizeF](/psd/python-net/aspose.psd/sizef/) de la largeur et la hauteur d'une autre structure [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [to_point_f()](#to_point_f__3) | Convertit un [SizeF](/psd/python-net/aspose.psd/sizef/) en un [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Convertit un [SizeF](/psd/python-net/aspose.psd/sizef/) en une structure [Size](/psd/python-net/aspose.psd/size/) avec des valeurs de taille tronquées. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initialise une nouvelle instance de la classe SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initialise une nouvelle instance de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) à partir du [PointF](/psd/python-net/aspose.psd/pointf/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Le [PointF](/psd/python-net/aspose.psd/pointf/) à partir duquel initialiser ce [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initialise une nouvelle instance de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) à partir du [SizeF](/psd/python-net/aspose.psd/sizef/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Le [SizeF](/psd/python-net/aspose.psd/sizef/) à partir duquel créer le nouveau [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initialise une nouvelle instance de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) à partir des dimensions spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | float | Le composant largeur du nouveau [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | Le composant hauteur du nouveau [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Ajoute la largeur et la hauteur d'une structure [SizeF](/psd/python-net/aspose.psd/sizef/) à la largeur et la hauteur d'une autre structure [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Le premier [SizeF](/psd/python-net/aspose.psd/sizef/) à ajouter. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Le deuxième [SizeF](/psd/python-net/aspose.psd/sizef/) à ajouter. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Une structure [SizeF](/psd/python-net/aspose.psd/sizef/) qui est le résultat de l'opération d'addition. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Soustrait la largeur et la hauteur d'une structure [SizeF](/psd/python-net/aspose.psd/sizef/) de la largeur et la hauteur d'une autre structure [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | La structure [SizeF](/psd/python-net/aspose.psd/sizef/) du côté gauche de l'opérateur de soustraction. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | La structure [SizeF](/psd/python-net/aspose.psd/sizef/) du côté droit de l'opérateur de soustraction. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Le [SizeF](/psd/python-net/aspose.psd/sizef/) qui est le résultat de l'opération de soustraction. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Convertit un [SizeF](/psd/python-net/aspose.psd/sizef/) en un [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Renvoie une structure [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Convertit un [SizeF](/psd/python-net/aspose.psd/sizef/) en une structure [Size](/psd/python-net/aspose.psd/size/) avec des valeurs de taille tronquées.

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Renvoie une structure [Size](/psd/python-net/aspose.psd/size/). |


