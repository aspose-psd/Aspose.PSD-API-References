---
title: "Point Classe"
type: docs
weight: 3530
url: /fr/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | Initialise une nouvelle instance de la classe Point |
| [Point(dw)](#Point_dw_2) | Initialise une nouvelle instance de la structure [Point](/psd/python-net/aspose.psd/point/) en utilisant des coordonnées spécifiées par une valeur entière. |
| [Point(size)](#Point_size_3) | Initialise une nouvelle instance de la structure [Point](/psd/python-net/aspose.psd/point/) à partir de la structure [Size](/psd/python-net/aspose.psd/size/). |
| [Point(x, y)](#Point_x_y_4) | Initialise une nouvelle instance de la structure [Point](/psd/python-net/aspose.psd/point/) avec les coordonnées spécifiées. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Obtient une nouvelle instance de la structure [Point](/psd/python-net/aspose.psd/point/) dont les valeurs [Point.x](/psd/python-net/aspose.psd/point/) et [Point.y](/psd/python-net/aspose.psd/point/) sont définies à zéro. |
| is_empty | bool | r | Obtient une valeur indiquant si ce [Point](/psd/python-net/aspose.psd/point/) est vide. |
| x | int | r/w | Obtient ou définit la coordonnée x de ce [Point](/psd/python-net/aspose.psd/point/). |
| y | int | r/w | Obtient ou définit la coordonnée y de ce [Point](/psd/python-net/aspose.psd/point/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Ajoute le [Size](/psd/python-net/aspose.psd/size/) spécifié au [Point](/psd/python-net/aspose.psd/point/) spécifié. |
| [ceiling(point)](#ceiling_point_2) | Convertit le [PointF](/psd/python-net/aspose.psd/pointf/) spécifié en un [Point](/psd/python-net/aspose.psd/point/) en arrondissant les valeurs du [PointF](/psd/python-net/aspose.psd/pointf/) à la prochaine valeur entière supérieure. |
| [offset(dx, dy)](#offset_dx_dy_3) | Déplace ce [Point](/psd/python-net/aspose.psd/point/) du montant spécifié. |
| [offset(point)](#offset_point_4) | Déplace ce [Point](/psd/python-net/aspose.psd/point/) du [Point](/psd/python-net/aspose.psd/point/) spécifié. |
| [round(point)](#round_point_5) | Convertit le [PointF](/psd/python-net/aspose.psd/pointf/) spécifié en un objet [Point](/psd/python-net/aspose.psd/point/) en arrondissant les valeurs du [Point](/psd/python-net/aspose.psd/point/) à l'entier le plus proche. |
| [subtract(point, size)](#subtract_point_size_6) | Renvoie le résultat de la soustraction du [Size](/psd/python-net/aspose.psd/size/) spécifié du [Point](/psd/python-net/aspose.psd/point/) spécifié. |
| [truncate(point)](#truncate_point_7) | Convertit le [PointF](/psd/python-net/aspose.psd/pointf/) spécifié en un [Point](/psd/python-net/aspose.psd/point/) en tronquant les valeurs du [Point](/psd/python-net/aspose.psd/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initialise une nouvelle instance de la classe Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initialise une nouvelle instance de la structure [Point](/psd/python-net/aspose.psd/point/) en utilisant des coordonnées spécifiées par une valeur entière.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dw | int | Un entier de 32 bits qui spécifie les coordonnées du nouveau point. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initialise une nouvelle instance de la structure [Point](/psd/python-net/aspose.psd/point/) à partir de la structure [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Contient les coordonnées du nouveau point. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initialise une nouvelle instance de la structure [Point](/psd/python-net/aspose.psd/point/) avec les coordonnées spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La position horizontale du point. |
| y | int | La position verticale du point. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Ajoute le [Size](/psd/python-net/aspose.psd/size/) spécifié au [Point](/psd/python-net/aspose.psd/point/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) auquel ajouter. |
| size | [Size](/psd/python-net/aspose.psd/size) | Le [Size](/psd/python-net/aspose.psd/size/) à ajouter au <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) qui est le résultat de l'opération d'addition. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Convertit le [PointF](/psd/python-net/aspose.psd/pointf/) spécifié en un [Point](/psd/python-net/aspose.psd/point/) en arrondissant les valeurs du [PointF](/psd/python-net/aspose.psd/pointf/) à la prochaine valeur entière supérieure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Le [PointF](/psd/python-net/aspose.psd/pointf/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) vers lequel cette méthode convertit. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Déplace ce [Point](/psd/python-net/aspose.psd/point/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | int | Le montant pour décaler la coordonnée x. |
| dy | int | Le montant pour décaler la coordonnée y. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Déplace ce [Point](/psd/python-net/aspose.psd/point/) du [Point](/psd/python-net/aspose.psd/point/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) utilisé pour décaler ce [Point](/psd/python-net/aspose.psd/point/). |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Convertit le [PointF](/psd/python-net/aspose.psd/pointf/) spécifié en un objet [Point](/psd/python-net/aspose.psd/point/) en arrondissant les valeurs du [Point](/psd/python-net/aspose.psd/point/) à l'entier le plus proche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Le [PointF](/psd/python-net/aspose.psd/pointf/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) vers lequel cette méthode convertit. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Renvoie le résultat de la soustraction du [Size](/psd/python-net/aspose.psd/size/) spécifié du [Point](/psd/python-net/aspose.psd/point/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) à soustraire de. |
| size | [Size](/psd/python-net/aspose.psd/size) | Le [Size](/psd/python-net/aspose.psd/size/) à soustraire du <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) qui est le résultat de l'opération de soustraction. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Convertit le [PointF](/psd/python-net/aspose.psd/pointf/) spécifié en un [Point](/psd/python-net/aspose.psd/point/) en tronquant les valeurs du [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Le [PointF](/psd/python-net/aspose.psd/pointf/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) vers lequel cette méthode convertit. |


