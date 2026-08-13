---
title: "Classe Region"
type: docs
weight: 3870
url: /fr/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Region()](#Region__1) | Initialise un nouveau [Region](/psd/python-net/aspose.psd/region/). |
| [Region(path)](#Region_path_2) | Initialise un nouveau [Region](/psd/python-net/aspose.psd/region/) avec le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié. |
| [Region(rect)](#Region_rect_3) | Initialise un nouveau [Region](/psd/python-net/aspose.psd/region/) à partir de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [Region(rect)](#Region_rect_4) | Initialise un nouveau [Region](/psd/python-net/aspose.psd/region/) à partir de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [complement(path)](#complement_path_1) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour contenir la partie du [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié qui n'intersecte pas avec ce [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_2) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour contenir la partie du [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifié qui n'intersecte pas avec ce [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_3) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour contenir la partie du [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifié qui n'intersecte pas avec ce [Region](/psd/python-net/aspose.psd/region/). |
| [complement(region)](#complement_region_4) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour contenir la partie du [Region](/psd/python-net/aspose.psd/region/) spécifié qui n'intersecte pas avec ce [Region](/psd/python-net/aspose.psd/region/). |
| [deep_clone()](#deep_clone__5) | Crée une copie profonde exacte de ce [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié. |
| [exclude(rect)](#exclude_rect_7) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [exclude(rect)](#exclude_rect_8) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [exclude(region)](#exclude_region_9) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [Region](/psd/python-net/aspose.psd/region/) spécifié. |
| [intersect(path)](#intersect_path_10) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) à l'intersection de lui-même avec le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié. |
| [intersect(rect)](#intersect_rect_11) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) à l'intersection de lui-même avec la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [intersect(rect)](#intersect_rect_12) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) à l'intersection de lui-même avec la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [intersect(region)](#intersect_region_13) | Met à jour ce [Region](/psd/python-net/aspose.psd/region/) à l'intersection de lui-même avec le [Region](/psd/python-net/aspose.psd/region/) spécifié. |
| [is_empty(g)](#is_empty_g_14) | Teste si ce [Region](/psd/python-net/aspose.psd/region/) a un intérieur vide sur la surface de dessin spécifiée. |
| [is_infinite(g)](#is_infinite_g_15) | Teste si ce [Region](/psd/python-net/aspose.psd/region/) a un intérieur infini sur la surface de dessin spécifiée. |
| [is_visible(point)](#is_visible_point_16) | Teste si la structure [PointF](/psd/python-net/aspose.psd/pointf/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point)](#is_visible_point_17) | Teste si la structure [PointF](/psd/python-net/aspose.psd/pointf/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point, g)](#is_visible_point_g_18) | Teste si la structure [PointF](/psd/python-net/aspose.psd/pointf/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(point, g)](#is_visible_point_g_19) | Teste si la structure [PointF](/psd/python-net/aspose.psd/pointf/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(rect)](#is_visible_rect_20) | Teste si une partie de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect)](#is_visible_rect_21) | Teste si une partie de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Teste si une partie de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Teste si une partie de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(x, y)](#is_visible_x_y_24) | Teste si le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Teste si le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'il est dessiné avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Teste si le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'il est dessiné avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Teste si une partie du rectangle spécifié est contenue dans cette [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Teste si une partie du rectangle spécifié est contenue dans cette [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Teste si une partie du rectangle spécifié est contenue dans cette [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée à l'aide du [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Teste si une partie du rectangle spécifié est contenue dans cette [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée à l'aide du [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| make_empty() | Initialise cette [Region](/psd/python-net/aspose.psd/region/) avec un intérieur vide. |
| make_infinite() | Initialise cet objet [Region](/psd/python-net/aspose.psd/region/) avec un intérieur infini. |
| [transform(matrix)](#transform_matrix_31) | Transforme cette [Region](/psd/python-net/aspose.psd/region/) à l'aide de la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée. |
| [translate(dx, dy)](#translate_dx_dy_32) | Décale les coordonnées de cette [Region](/psd/python-net/aspose.psd/region/) du montant spécifié. |
| [translate(dx, dy)](#translate_dx_dy_33) | Décale les coordonnées de cette [Region](/psd/python-net/aspose.psd/region/) du montant spécifié. |
| [union(path)](#union_path_34) | Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union d'elle-même et du [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié. |
| [union(rect)](#union_rect_35) | Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union d'elle-même et de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [union(rect)](#union_rect_36) | Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union d'elle-même et de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [union(region)](#union_region_37) | Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union d'elle-même et de la [Region](/psd/python-net/aspose.psd/region/) spécifiée. |
| [xor(path)](#xor_path_38) | Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union moins l'intersection d'elle-même avec le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié. |
| [xor(rect)](#xor_rect_39) | Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union moins l'intersection d'elle-même avec la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [xor(rect)](#xor_rect_40) | Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union moins l'intersection d'elle-même avec la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée. |
| [xor(region)](#xor_region_41) | Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union moins l'intersection d'elle-même avec la [Region](/psd/python-net/aspose.psd/region/) spécifiée. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Initialise un nouveau [Region](/psd/python-net/aspose.psd/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Initialise un nouveau [Region](/psd/python-net/aspose.psd/region/) avec le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit la nouvelle [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Initialise un nouveau [Region](/psd/python-net/aspose.psd/region/) à partir de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui définit l'intérieur de la nouvelle [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Initialise un nouveau [Region](/psd/python-net/aspose.psd/region/) à partir de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui définit l'intérieur de la nouvelle [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour contenir la partie du [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié qui n'intersecte pas avec ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) pour compléter cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour contenir la partie du [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifié qui n'intersecte pas avec ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) pour compléter cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour contenir la partie du [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifié qui n'intersecte pas avec ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) pour compléter cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour contenir la partie du [Region](/psd/python-net/aspose.psd/region/) spécifié qui n'intersecte pas avec ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | L'objet [Region](/psd/python-net/aspose.psd/region/) pour compléter cet objet [Region](/psd/python-net/aspose.psd/region/). |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Crée une copie profonde exacte de ce [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| Type | Description |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) que cette méthode crée. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) à exclure de cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à exclure de cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à exclure de cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [Region](/psd/python-net/aspose.psd/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) à exclure de cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) à l'intersection de lui-même avec le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) à intersecter avec cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) à l'intersection de lui-même avec la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à intersecter avec cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) à l'intersection de lui-même avec la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à intersecter avec cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Met à jour ce [Region](/psd/python-net/aspose.psd/region/) à l'intersection de lui-même avec le [Region](/psd/python-net/aspose.psd/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) à intersecter avec cette [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Teste si ce [Region](/psd/python-net/aspose.psd/region/) a un intérieur vide sur la surface de dessin spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente une surface de dessin. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si l'intérieur de ce [Region](/psd/python-net/aspose.psd/region/) est vide lorsque la transformation associée à <paramref name=\"g\" /> est appliquée ; sinon, false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Teste si ce [Region](/psd/python-net/aspose.psd/region/) a un intérieur infini sur la surface de dessin spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente une surface de dessin. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si l'intérieur de ce [Region](/psd/python-net/aspose.psd/region/) est infini lorsque la transformation associée à <paramref name=\"g\" /> est appliquée ; sinon, false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Teste si la structure [PointF](/psd/python-net/aspose.psd/pointf/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | La structure [PointF](/psd/python-net/aspose.psd/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque <paramref name=\"point\" /> est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Teste si la structure [PointF](/psd/python-net/aspose.psd/pointf/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | La structure [PointF](/psd/python-net/aspose.psd/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque <paramref name=\"point\" /> est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Teste si la structure [PointF](/psd/python-net/aspose.psd/pointf/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | La structure [PointF](/psd/python-net/aspose.psd/pointf/) à tester. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque <paramref name=\"point\" /> est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Teste si la structure [PointF](/psd/python-net/aspose.psd/pointf/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | La structure [PointF](/psd/python-net/aspose.psd/pointf/) à tester. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque <paramref name=\"point\" /> est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Teste si une partie de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque n'importe quelle partie de <paramref name=\"rect\" /> est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Teste si une partie de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque n'importe quelle partie de <paramref name=\"rect\" /> est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Teste si une partie de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à tester. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque <paramref name=\"rect\" /> est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Teste si une partie de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à tester. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque <paramref name=\"rect\" /> est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Teste si le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True lorsque le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Teste si le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'il est dessiné avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True lorsque le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Teste si le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/) lorsqu'il est dessiné avec le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True lorsque le point spécifié est contenu dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Teste si une partie du rectangle spécifié est contenue dans cette [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | float | La largeur du rectangle à tester. |
| hauteur | float | La hauteur du rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque n'importe quelle partie du rectangle spécifié est contenue dans cet objet [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Teste si une partie du rectangle spécifié est contenue dans cette [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | int | La largeur du rectangle à tester. |
| hauteur | int | La hauteur du rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque n'importe quelle partie du rectangle spécifié est contenue dans cet objet [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Teste si une partie du rectangle spécifié est contenue dans cette [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée à l'aide du [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | float | La largeur du rectangle à tester. |
| hauteur | float | La hauteur du rectangle à tester. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque n'importe quelle partie du rectangle spécifié est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Teste si une partie du rectangle spécifié est contenue dans cette [Region](/psd/python-net/aspose.psd/region/) lorsqu'elle est dessinée à l'aide du [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | int | La largeur du rectangle à tester. |
| hauteur | int | La hauteur du rectangle à tester. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true lorsque n'importe quelle partie du rectangle spécifié est contenue dans ce [Region](/psd/python-net/aspose.psd/region/) ; sinon, false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Transforme cette [Region](/psd/python-net/aspose.psd/region/) à l'aide de la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) par laquelle transformer ce [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Décale les coordonnées de cette [Region](/psd/python-net/aspose.psd/region/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | Le montant pour décaler ce [Region](/psd/python-net/aspose.psd/region/) horizontalement. |
| dy | float | Le montant pour décaler ce [Region](/psd/python-net/aspose.psd/region/) verticalement. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Décale les coordonnées de cette [Region](/psd/python-net/aspose.psd/region/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | int | Le montant pour décaler ce [Region](/psd/python-net/aspose.psd/region/) horizontalement. |
| dy | int | Le montant pour décaler ce [Region](/psd/python-net/aspose.psd/region/) verticalement. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union d'elle-même et du [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) à unir avec ce [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union d'elle-même et de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à unir avec ce [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union d'elle-même et de la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à unir avec ce [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union d'elle-même et de la [Region](/psd/python-net/aspose.psd/region/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Le [Region](/psd/python-net/aspose.psd/region/) à unir avec ce [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union moins l'intersection d'elle-même avec le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) à xor avec ce [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union moins l'intersection d'elle-même avec la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à xor avec ce [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union moins l'intersection d'elle-même avec la structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) à xor avec ce [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Met à jour cette [Region](/psd/python-net/aspose.psd/region/) avec l'union moins l'intersection d'elle-même avec la [Region](/psd/python-net/aspose.psd/region/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Le [Region](/psd/python-net/aspose.psd/region/) à xor avec ce [Region](/psd/python-net/aspose.psd/region/). |

