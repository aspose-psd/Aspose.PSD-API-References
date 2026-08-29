---
title: "Classe Size"
type: docs
weight: 4080
url: /fr/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Size()](#Size__1) | Initialise une nouvelle instance de la classe Size |
| [Size(point)](#Size_point_2) | Initialise une nouvelle instance de la structure [Size](/psd/python-net/aspose.psd/size/) à partir du [Point](/psd/python-net/aspose.psd/point/) spécifié. |
| [Size(width, height)](#Size_width_height_3) | Initialise une nouvelle instance de la structure [Size](/psd/python-net/aspose.psd/size/) à partir des dimensions spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Obtient une nouvelle instance de la structure [Size](/psd/python-net/aspose.psd/size/) dont les valeurs [Size.width](/psd/python-net/aspose.psd/size/) et [Size.height](/psd/python-net/aspose.psd/size/) sont définies à zéro. |
| height | int | r/w | Obtient ou définit le composant vertical de ce [Size](/psd/python-net/aspose.psd/size/). |
| is_empty | bool | r | Obtient une valeur indiquant si ce [Size](/psd/python-net/aspose.psd/size/) a une largeur et une hauteur de 0. |
| width | int | r/w | Obtient ou définit le composant horizontal de ce [Size](/psd/python-net/aspose.psd/size/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Ajoute la largeur et la hauteur d'une structure [Size](/psd/python-net/aspose.psd/size/) à la largeur et la hauteur d'une autre structure [Size](/psd/python-net/aspose.psd/size/). |
| [ceiling(size)](#ceiling_size_2) | Convertit la structure [SizeF](/psd/python-net/aspose.psd/sizef/) spécifiée en une structure [Size](/psd/python-net/aspose.psd/size/) en arrondissant les valeurs de la structure [Size](/psd/python-net/aspose.psd/size/) aux entiers supérieurs les plus proches. |
| [round(size)](#round_size_3) | Convertit la structure [SizeF](/psd/python-net/aspose.psd/sizef/) spécifiée en une structure [Size](/psd/python-net/aspose.psd/size/) en arrondissant les valeurs de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) aux valeurs entières les plus proches. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Soustrait la largeur et la hauteur d'une structure [Size](/psd/python-net/aspose.psd/size/) de la largeur et de la hauteur d'une autre structure [Size](/psd/python-net/aspose.psd/size/). |
| [truncate(size)](#truncate_size_5) | Convertit la structure [SizeF](/psd/python-net/aspose.psd/sizef/) spécifiée en une structure [Size](/psd/python-net/aspose.psd/size/) en tronquant les valeurs de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) à l'entier inférieur suivant. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Initialise une nouvelle instance de la classe Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Initialise une nouvelle instance de la structure [Size](/psd/python-net/aspose.psd/size/) à partir du [Point](/psd/python-net/aspose.psd/point/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) à partir duquel initialiser ce [Size](/psd/python-net/aspose.psd/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Initialise une nouvelle instance de la structure [Size](/psd/python-net/aspose.psd/size/) à partir des dimensions spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | Le composant largeur du nouveau [Size](/psd/python-net/aspose.psd/size/). |
| height | int | Le composant hauteur du nouveau [Size](/psd/python-net/aspose.psd/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Ajoute la largeur et la hauteur d'une structure [Size](/psd/python-net/aspose.psd/size/) à la largeur et la hauteur d'une autre structure [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Le premier [Size](/psd/python-net/aspose.psd/size/) à ajouter. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Le deuxième [Size](/psd/python-net/aspose.psd/size/) à ajouter. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Une structure [Size](/psd/python-net/aspose.psd/size/) qui est le résultat de l'opération d'addition. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Convertit la structure [SizeF](/psd/python-net/aspose.psd/sizef/) spécifiée en une structure [Size](/psd/python-net/aspose.psd/size/) en arrondissant les valeurs de la structure [Size](/psd/python-net/aspose.psd/size/) aux entiers supérieurs les plus proches.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La structure [SizeF](/psd/python-net/aspose.psd/sizef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La structure [Size](/psd/python-net/aspose.psd/size/) vers laquelle cette méthode convertit. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Convertit la structure [SizeF](/psd/python-net/aspose.psd/sizef/) spécifiée en une structure [Size](/psd/python-net/aspose.psd/size/) en arrondissant les valeurs de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) aux valeurs entières les plus proches.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La structure [SizeF](/psd/python-net/aspose.psd/sizef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La structure [Size](/psd/python-net/aspose.psd/size/) vers laquelle cette méthode convertit. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Soustrait la largeur et la hauteur d'une structure [Size](/psd/python-net/aspose.psd/size/) de la largeur et de la hauteur d'une autre structure [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | La structure [Size](/psd/python-net/aspose.psd/size/) du côté gauche de l'opérateur de soustraction. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | La structure [Size](/psd/python-net/aspose.psd/size/) du côté droit de l'opérateur de soustraction. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Le [Size](/psd/python-net/aspose.psd/size/) qui est le résultat de l'opération de soustraction. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Convertit la structure [SizeF](/psd/python-net/aspose.psd/sizef/) spécifiée en une structure [Size](/psd/python-net/aspose.psd/size/) en tronquant les valeurs de la structure [SizeF](/psd/python-net/aspose.psd/sizef/) à l'entier inférieur suivant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La structure [SizeF](/psd/python-net/aspose.psd/sizef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La structure [Size](/psd/python-net/aspose.psd/size/) vers laquelle cette méthode convertit. |


