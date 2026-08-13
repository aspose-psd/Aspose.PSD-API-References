---
title: "Classe RectangleF"
type: docs
weight: 3830
url: /fr/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initialise une nouvelle instance de la classe RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initialise une nouvelle instance de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) avec l'emplacement et la taille spécifiés. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initialise une nouvelle instance de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) avec l'emplacement et la taille spécifiés. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | float | r/w | Obtient ou définit la coordonnée y qui est la somme de [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) et de [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient une nouvelle instance de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dont les valeurs [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) et [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) sont définies à zéro. |
| height | float | r/w | Obtient ou définit la hauteur de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| is_empty | bool | r | Obtient une valeur indiquant si la propriété [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) ou [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) de cette [RectangleF](/psd/python-net/aspose.psd/rectanglef/) a une valeur de zéro. |
| left | float | r/w | Obtient ou définit la coordonnée x du bord gauche de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| right | float | r/w | Obtient ou définit la coordonnée x qui est la somme de [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) et de [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Obtient ou définit la taille de cette [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| top | float | r/w | Obtient ou définit la coordonnée y du bord supérieur de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| width | float | r/w | Obtient ou définit la largeur de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| x | float | r/w | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| y | float | r/w | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains(point)](#contains_point_1) | Détermine si le point spécifié est contenu dans cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(rect)](#contains_rect_2) | Détermine si la région rectangulaire représentée par <paramref name="rect" /> est entièrement contenue dans cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | Détermine si le point spécifié est contenu dans cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Crée une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Crée un nouveau [Rectangle](/psd/python-net/aspose.psd/rectangle/) à partir de deux points spécifiés. Les deux sommets du [Rectangle](/psd/python-net/aspose.psd/rectangle/) créé seront égaux aux paramètres <paramref name="point1" /> et <paramref name="point2" />. Ils sont généralement les sommets opposés. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Crée et renvoie une copie gonflée de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. La copie est agrandie du montant indiqué. Le rectangle original reste inchangé. |
| [inflate(size)](#inflate_size_7) | Gonfle ce [RectangleF](/psd/python-net/aspose.psd/rectanglef/) du montant spécifié. |
| [inflate(x, y)](#inflate_x_y_8) | Gonfle cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) du montant spécifié. |
| [intersect(a, b)](#intersect_a_b_9) | Renvoie une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) vide est renvoyé. |
| [intersect(rect)](#intersect_rect_10) | Remplace cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) par l'intersection d'elle-même et de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [intersects_with(rect)](#intersects_with_rect_11) | Détermine si ce rectangle intersecte <paramref name="rect" />. |
| normalize() | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas. |
| [offset(pos)](#offset_pos_12) | Ajuste la position de ce rectangle du montant spécifié. |
| [offset(x, y)](#offset_x_y_13) | Ajuste la position de ce rectangle du montant spécifié. |
| [union(a, b)](#union_a_b_14) | Crée le plus petit rectangle possible qui peut contenir les deux rectangles formant une union. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initialise une nouvelle instance de la classe RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initialise une nouvelle instance de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) avec l'emplacement et la taille spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui représente le coin supérieur gauche de la région rectangulaire. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Un [SizeF](/psd/python-net/aspose.psd/sizef/) qui représente la largeur et la hauteur de la région rectangulaire. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initialise une nouvelle instance de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) avec l'emplacement et la taille spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle. |
| width | float | La largeur du rectangle. |
| hauteur | float | La hauteur du rectangle. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Détermine si le point spécifié est contenu dans cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Le [PointF](/psd/python-net/aspose.psd/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie vrai si le point représenté par le paramètre <paramref name="point" /> est contenu dans cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/); sinon faux. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Détermine si la région rectangulaire représentée par <paramref name="rect" /> est entièrement contenue dans cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie vrai si la région rectangulaire représentée par <paramref name="rect" /> est entièrement contenue dans la région rectangulaire représentée par ce [RectangleF](/psd/python-net/aspose.psd/rectanglef/); sinon faux. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Détermine si le point spécifié est contenu dans cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point défini par <paramref name="x" /> et <paramref name="y" /> est contenu dans cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/); sinon false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crée une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gauche | float | La coordonnée x du coin supérieur gauche de la région rectangulaire. |
| haut | float | La coordonnée y du coin supérieur gauche de la région rectangulaire. |
| droite | float | La coordonnée x du coin inférieur droit de la région rectangulaire. |
| bottom | float | La coordonnée y du coin inférieur droit de la région rectangulaire. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le nouveau [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que cette méthode crée. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Crée un nouveau [Rectangle](/psd/python-net/aspose.psd/rectangle/) à partir de deux points spécifiés. Les deux sommets du [Rectangle](/psd/python-net/aspose.psd/rectangle/) créé seront égaux aux paramètres <paramref name="point1" /> et <paramref name="point2" />. Ils sont généralement les sommets opposés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Le premier [Point](/psd/python-net/aspose.psd/point/) du nouveau rectangle. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Le deuxième [Point](/psd/python-net/aspose.psd/point/) du nouveau rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) nouvellement créé. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Crée et renvoie une copie gonflée de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. La copie est agrandie du montant indiqué. Le rectangle original reste inchangé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à copier. Ce rectangle n'est pas modifié. |
| x | float | La quantité pour gonfler la copie du rectangle horizontalement. |
| y | float | La quantité pour gonfler la copie du rectangle verticalement. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le [RectangleF](/psd/python-net/aspose.psd/rectanglef/) gonflé. |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Gonfle ce [RectangleF](/psd/python-net/aspose.psd/rectanglef/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La quantité pour gonfler ce rectangle. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Gonfle cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La quantité pour gonfler horizontalement cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| y | float | La quantité pour gonfler verticalement cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Renvoie une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) vide est renvoyé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un premier rectangle à intersecter. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un deuxième rectangle à intersecter. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une troisième structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dont la taille représente la zone chevauchée des deux rectangles spécifiés. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Remplace cette structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) par l'intersection d'elle-même et de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle à intersecter. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Détermine si ce rectangle intersecte <paramref name="rect" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true s'il y a une quelconque intersection. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | La quantité pour décaler l'emplacement. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Ajuste la position de ce rectangle du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La quantité pour décaler l'emplacement horizontalement. |
| y | float | La quantité pour décaler l'emplacement verticalement. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Crée le plus petit rectangle possible qui peut contenir les deux rectangles formant une union.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un premier rectangle à unir. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un deuxième rectangle à unir. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une troisième structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui contient les deux rectangles qui forment l'union. |


