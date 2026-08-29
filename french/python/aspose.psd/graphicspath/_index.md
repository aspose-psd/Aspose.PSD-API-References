---
title: "Classe GraphicsPath"
type: docs
weight: 1570
url: /fr/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initialise une nouvelle instance de la classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initialise une nouvelle instance de la classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initialise une nouvelle instance de la classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initialise une nouvelle instance de la classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient ou définit les limites de l'objet. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Obtient les figures du chemin. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Obtient ou définit une énumération [FillMode](/psd/python-net/aspose.psd/fillmode/) qui détermine comment les intérieurs des formes de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) sont remplis. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Ajoute une nouvelle figure. |
| [add_figures(figures)](#add_figures_figures_2) | Ajoute de nouvelles figures. |
| [add_path(adding_path)](#add_path_adding_path_3) | Ajoute le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié à ce chemin. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Ajoute le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié à ce chemin. |
| [deep_clone()](#deep_clone__5) | Effectue un clonage profond de ce chemin graphique. |
| flatten() | Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés. |
| [flatten(matrix)](#flatten_matrix_6) | Applique la transformation spécifiée, puis convertit chaque courbe de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en une séquence de segments de ligne connectés. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Convertit chaque courbe de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en une séquence de segments de ligne connectés. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Obtient les limites de l'objet. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié et en utilisant le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié et en utilisant le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié et en utilisant le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié et en utilisant le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(point)](#is_visible_point_18) | Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dans la région de découpe visible du [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dans la région de découpe visible du [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié. |
| [remove_figure(figure)](#remove_figure_figure_26) | Supprime une figure. |
| [remove_figures(figures)](#remove_figures_figures_27) | Supprime des figures. |
| reset() | Vide le chemin graphique et définit le [FillMode](/psd/python-net/aspose.psd/fillmode/) sur [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Inverse l'ordre des figures, des formes et des points dans chaque forme de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [transform(transform)](#transform_transform_28) | Applique la transformation spécifiée à la forme. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | Ajoute un contour supplémentaire au chemin. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Ajoute un contour supplémentaire au [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Remplace ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) par des courbes qui entourent la zone remplie lorsque ce chemin est dessiné avec le pen spécifié. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initialise une nouvelle instance de la classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initialise une nouvelle instance de la classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Les figures à initialiser. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initialise une nouvelle instance de la classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Les figures à initialiser. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Le mode de remplissage. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initialise une nouvelle instance de la classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Le mode de remplissage. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Ajoute une nouvelle figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | La figure à ajouter. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Ajoute de nouvelles figures.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Les figures à ajouter. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Ajoute le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié à ce chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) à ajouter. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Ajoute le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) spécifié à ce chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Le [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) à ajouter. |
| connecter | bool | Une valeur booléenne qui indique si la première figure du chemin ajouté fait partie de la dernière figure de ce chemin. Une valeur true indique que la première figure du chemin ajouté fait partie de la dernière figure de ce chemin. Une valeur false indique que la première figure du chemin ajouté est séparée de la dernière figure de ce chemin. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Effectue un clonage profond de ce chemin graphique.

**Returns**

| Type | Description |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Une copie profonde du chemin graphique. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Applique la transformation spécifiée, puis convertit chaque courbe de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en une séquence de segments de ligne connectés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Une [Matrix](/psd/python-net/aspose.psd/matrix/) par laquelle transformer ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) avant l'aplatissement. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Convertit chaque courbe de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) en une séquence de segments de ligne connectés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Une [Matrix](/psd/python-net/aspose.psd/matrix/) par laquelle transformer ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) avant l'aplatissement. |
| planéité | float | Spécifie l'erreur maximale autorisée entre la courbe et son approximation aplatie. Une valeur de 0,25 est la valeur par défaut. Réduire la valeur de planéité augmentera le nombre de segments de ligne dans l'approximation. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice à appliquer avant le calcul des limites sera calculée. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Les limites estimées de l'objet. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice à appliquer avant le calcul des limites sera calculée. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le crayon à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Les limites estimées de l'objet. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le [Pen](/psd/python-net/aspose.psd/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le [Pen](/psd/python-net/aspose.psd/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié et en utilisant le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le [Pen](/psd/python-net/aspose.psd/pen/) à tester. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Le [Graphics](/psd/python-net/aspose.psd/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans (ou sous) le contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) tel que dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié et en utilisant le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui indique l'emplacement à tester. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le [Pen](/psd/python-net/aspose.psd/pen/) à tester. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Le [Graphics](/psd/python-net/aspose.psd/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans (ou sous) le contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) tel que dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le [Pen](/psd/python-net/aspose.psd/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le [Pen](/psd/python-net/aspose.psd/pen/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans le contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié et en utilisant le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le [Pen](/psd/python-net/aspose.psd/pen/) à tester. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Le [Graphics](/psd/python-net/aspose.psd/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans (ou sous) le contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) tel que dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié ; sinon, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) lorsqu'il est dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié et en utilisant le [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le [Pen](/psd/python-net/aspose.psd/pen/) à tester. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Le [Graphics](/psd/python-net/aspose.psd/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans (ou sous) le contour de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) tel que dessiné avec le [Pen](/psd/python-net/aspose.psd/pen/) spécifié ; sinon, false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui représente le point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ; sinon, false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui représente le point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ; sinon, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui représente le point à tester. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Le [Graphics](/psd/python-net/aspose.psd/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans cet élément ; sinon, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) qui représente le point à tester. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Le [Graphics](/psd/python-net/aspose.psd/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans cet élément ; sinon, false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ; sinon, false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ; sinon, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dans la région de découpe visible du [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Le [Graphics](/psd/python-net/aspose.psd/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ; sinon, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Indique si le point spécifié est contenu à l'intérieur de ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) dans la région de découpe visible du [Graphics](/psd/python-net/aspose.psd/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Le [Graphics](/psd/python-net/aspose.psd/graphics/) pour lequel tester la visibilité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Cette méthode renvoie true si le point spécifié est contenu dans ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ; sinon, false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Supprime une figure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | La figure à supprimer. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Supprime des figures.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Les figures à supprimer. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La transformation à appliquer. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par <paramref name=\"srcRect\" /> est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle transformé en parallélogramme défini par <paramref name=\"destPoints\" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par <paramref name=\"srcRect\" /> est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle transformé en parallélogramme défini par <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Une [Matrix](/psd/python-net/aspose.psd/matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par <paramref name=\"srcRect\" /> est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle transformé en parallélogramme défini par <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Une [Matrix](/psd/python-net/aspose.psd/matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Une énumération [WarpMode](/psd/python-net/aspose.psd/warpmode/) qui indique si cette opération de déformation utilise le mode perspective ou bilinéaire. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par <paramref name=\"srcRect\" /> est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle transformé en parallélogramme défini par <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Une [Matrix](/psd/python-net/aspose.psd/matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Une énumération [WarpMode](/psd/python-net/aspose.psd/warpmode/) qui indique si cette opération de déformation utilise le mode perspective ou bilinéaire. |
| flatness | float | Une valeur comprise entre 0 et 1 qui indique à quel point le chemin résultant est plat. Pour plus d'informations, consultez les méthodes [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/). |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Ajoute un contour supplémentaire au chemin.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Ajoute un contour supplémentaire au [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Une [Matrix](/psd/python-net/aspose.psd/matrix/) qui spécifie une transformation à appliquer au chemin avant l'élargissement. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Remplace ce [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) par des courbes qui entourent la zone remplie lorsque ce chemin est dessiné avec le pen spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) qui spécifie la largeur entre le contour original du chemin et le nouveau contour créé par cette méthode. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Une [Matrix](/psd/python-net/aspose.psd/matrix/) qui spécifie une transformation à appliquer au chemin avant l'élargissement. |
| planéité | float | Une valeur qui spécifie la planéité des courbes. |

