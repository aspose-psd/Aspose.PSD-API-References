---
title: "Classe Rectangle"
type: docs
weight: 3810
url: /fr/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initialise une nouvelle instance de la classe Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initialise une nouvelle instance de la structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) avec l'emplacement et la taille spécifiés. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initialise une nouvelle instance de la structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) avec l'emplacement et la taille spécifiés. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) et [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtient une nouvelle instance de la structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) dont les valeurs [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) et [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) sont définies à zéro. |
| height | int | r/w | Obtient ou définit la hauteur de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| is_empty | bool | r | Obtient une valeur indiquant si toutes les propriétés numériques de ce [Rectangle](/psd/python-net/aspose.psd/rectangle/) ont des valeurs égales à zéro. |
| left | int | r/w | Obtient ou définit la coordonnée x du bord gauche de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | r/w | Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) et [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Obtient ou définit la taille de ce [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | Obtient ou définit la coordonnée y du bord supérieur de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| width | int | r/w | Obtient ou définit la largeur de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| x | int | r/w | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | r/w | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Convertit la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée en une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) en arrondissant les valeurs de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) au prochain entier supérieur. |
| [contains(point)](#contains_point_2) | Détermine si le point spécifié est contenu dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(rect)](#contains_rect_3) | Détermine si la région rectangulaire représentée par <paramref name="rect" /> est entièrement contenue dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | Détermine si le point spécifié est contenu dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Crée une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) avec les emplacements des bords spécifiés. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Crée un nouveau [Rectangle](/psd/python-net/aspose.psd/rectangle/) à partir de deux points spécifiés. Les deux côtés verticaux du [Rectangle](/psd/python-net/aspose.psd/rectangle/) créé seront égaux aux <paramref name="point1" /> et <paramref name="point2" /> fournis. Ceux-ci sont généralement les sommets opposés. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Crée et renvoie une copie gonflée de la structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) spécifiée. La copie est gonflée du montant indiqué. La structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) originale reste inchangée. |
| [inflate(size)](#inflate_size_8) | Agrandit ce [Rectangle](/psd/python-net/aspose.psd/rectangle/) du montant spécifié. |
| [inflate(width, height)](#inflate_width_height_9) | Agrandit ce [Rectangle](/psd/python-net/aspose.psd/rectangle/) du montant spécifié. |
| [intersect(a, b)](#intersect_a_b_10) | Renvoie une troisième structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représente l’intersection de deux autres structures [Rectangle](/psd/python-net/aspose.psd/rectangle/). S’il n’y a aucune intersection, un [Rectangle](/psd/python-net/aspose.psd/rectangle/) vide est renvoyé. |
| [intersect(rect)](#intersect_rect_11) | Remplace ce [Rectangle](/psd/python-net/aspose.psd/rectangle/) par l’intersection de lui‑même et du [Rectangle](/psd/python-net/aspose.psd/rectangle/) spécifié. |
| [intersects_with(rect)](#intersects_with_rect_12) | Détermine si ce rectangle intersecte <paramref name="rect" />. |
| normalize() | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas. |
| [offset(pos)](#offset_pos_13) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(x, y)](#offset_x_y_14) | Ajuste la position de ce rectangle du montant spécifié. |
| [round(value)](#round_value_15) | Convertit le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifié en un [Rectangle](/psd/python-net/aspose.psd/rectangle/) en arrondissant les valeurs du [RectangleF](/psd/python-net/aspose.psd/rectanglef/) aux entiers les plus proches. |
| [truncate(value)](#truncate_value_16) | Convertit le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifié en un [Rectangle](/psd/python-net/aspose.psd/rectangle/) en tronquant les valeurs du [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [union(a, b)](#union_a_b_17) | Obtient une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui contient l’union de deux structures [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initialise une nouvelle instance de la classe Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initialise une nouvelle instance de la structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) avec l'emplacement et la taille spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Un [Point](/psd/python-net/aspose.psd/point/) qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [Size](/psd/python-net/aspose.psd/size) | Une [Size](/psd/python-net/aspose.psd/size/) qui représente la largeur et la hauteur de la région rectangulaire. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Initialise une nouvelle instance de la structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) avec l'emplacement et la taille spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle. |
| width | int | La largeur du rectangle. |
| hauteur | int | La hauteur du rectangle. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Convertit la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée en une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) en arrondissant les valeurs de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) au prochain entier supérieur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Renvoie un [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Détermine si le point spécifié est contenu dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Le [Point](/psd/python-net/aspose.psd/point/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point représenté par <paramref name="point" /> est contenu dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/); sinon false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Détermine si la région rectangulaire représentée par <paramref name="rect" /> est entièrement contenue dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le [Rectangle](/psd/python-net/aspose.psd/rectangle/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si la région rectangulaire représentée par <paramref name="rect" /> est entièrement contenue dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/); sinon false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Détermine si le point spécifié est contenu dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point défini par <paramref name="x" /> et <paramref name="y" /> est contenu dans cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/); sinon false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crée une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) avec les emplacements des bords spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| left | int | La coordonnée x du coin supérieur gauche de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | La coordonnée y du coin supérieur gauche de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | La coordonnée x du coin inférieur droit de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| bottom | int | La coordonnée y du coin inférieur droit de cette structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le nouveau [Rectangle](/psd/python-net/aspose.psd/rectangle/) que cette méthode crée. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Crée un nouveau [Rectangle](/psd/python-net/aspose.psd/rectangle/) à partir de deux points spécifiés. Les deux côtés verticaux du [Rectangle](/psd/python-net/aspose.psd/rectangle/) créé seront égaux aux <paramref name="point1" /> et <paramref name="point2" /> fournis. Ceux-ci sont généralement les sommets opposés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Le premier [Point](/psd/python-net/aspose.psd/point/) du nouveau rectangle. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Le deuxième [Point](/psd/python-net/aspose.psd/point/) du nouveau rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) nouvellement créé. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Crée et renvoie une copie gonflée de la structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) spécifiée. La copie est gonflée du montant indiqué. La structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) originale reste inchangée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le [Rectangle](/psd/python-net/aspose.psd/rectangle/) avec lequel commencer. Ce rectangle n’est pas modifié. |
| x | int | Le montant d’agrandissement horizontal de ce [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | Le montant d’agrandissement vertical de ce [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le [Rectangle](/psd/python-net/aspose.psd/rectangle/) agrandi. |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Agrandit ce [Rectangle](/psd/python-net/aspose.psd/rectangle/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | La quantité pour gonfler ce rectangle. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Agrandit ce [Rectangle](/psd/python-net/aspose.psd/rectangle/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | Le montant d’agrandissement horizontal de ce [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| height | int | Le montant d’agrandissement vertical de ce [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Renvoie une troisième structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représente l’intersection de deux autres structures [Rectangle](/psd/python-net/aspose.psd/rectangle/). S’il n’y a aucune intersection, un [Rectangle](/psd/python-net/aspose.psd/rectangle/) vide est renvoyé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un premier rectangle à intersecter. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un deuxième rectangle à intersecter. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représente l’intersection de <paramref name="a" /> et <paramref name="b" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Remplace ce [Rectangle](/psd/python-net/aspose.psd/rectangle/) par l’intersection de lui‑même et du [Rectangle](/psd/python-net/aspose.psd/rectangle/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le [Rectangle](/psd/python-net/aspose.psd/rectangle/) avec lequel intersecter. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Détermine si ce rectangle intersecte <paramref name="rect" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true s'il y a une intersection, sinon false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Quantité pour décaler l'emplacement. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | Le décalage horizontal. |
| y | int | Le décalage vertical. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Convertit le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifié en un [Rectangle](/psd/python-net/aspose.psd/rectangle/) en arrondissant les valeurs du [RectangleF](/psd/python-net/aspose.psd/rectanglef/) aux entiers les plus proches.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un nouveau [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Convertit le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifié en un [Rectangle](/psd/python-net/aspose.psd/rectangle/) en tronquant les valeurs du [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un nouveau [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Obtient une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui contient l’union de deux structures [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un premier rectangle à unir. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un deuxième rectangle à unir. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui délimite l'union des deux structures [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


