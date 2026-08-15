---
title: "GraphicsPath Klasse"
type: docs
weight: 1570
url: /nl/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initialiseert een nieuw exemplaar van de [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) klasse. |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initialiseert een nieuw exemplaar van de [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) klasse. |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initialiseert een nieuw exemplaar van de [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) klasse. |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initialiseert een nieuw exemplaar van de [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt de grenzen van het object op of stelt ze in. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Haalt de padfiguren op. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Haalt op of stelt een [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeratie in die bepaalt hoe de interieurs van vormen in deze [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) worden gevuld. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Voegt een nieuwe figuur toe. |
| [add_figures(figures)](#add_figures_figures_2) | Voegt nieuwe figuren toe. |
| [add_path(adding_path)](#add_path_adding_path_3) | Voegt het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) toe aan dit pad. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Voegt het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) toe aan dit pad. |
| [deep_clone()](#deep_clone__5) | Voert een diepe kloon uit van dit grafische pad. |
| flatten() | Converteert elke curve in dit pad naar een reeks verbonden lijnsegmenten. |
| [flatten(matrix)](#flatten_matrix_6) | Past de opgegeven transformatie toe en converteert vervolgens elke curve in dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) naar een reeks verbonden lijnsegmenten. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Converteert elke curve in dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) naar een reeks verbonden lijnsegmenten. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Haalt de grenzen van het object op. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Haalt de grenzen van het object op. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/) en met behulp van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/) en met behulp van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/) en met behulp van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/) en met behulp van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point)](#is_visible_point_18) | Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in de zichtbare knipregio van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in de zichtbare knipregio van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_26) | Verwijdert een figuur. |
| [remove_figures(figures)](#remove_figures_figures_27) | Verwijdert figuren. |
| reset() | Leegt het grafische pad en stelt de [FillMode](/psd/python-net/aspose.psd/fillmode/) in op [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Keert de volgorde van figuren, vormen en punten in elke vorm van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om. |
| [transform(transform)](#transform_transform_28) | Past de opgegeven transformatie toe op de vorm. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | Voegt een extra omtrek toe aan het pad. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Voegt een extra omtrek toe aan het [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Vervangt dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) door curven die het gebied omsluiten dat wordt gevuld wanneer dit pad wordt getekend met de opgegeven pen. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initialiseert een nieuw exemplaar van de [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) klasse.

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initialiseert een nieuw exemplaar van de [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | De figuren om van te initialiseren. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initialiseert een nieuw exemplaar van de [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | De figuren om van te initialiseren. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | De vulmodus. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initialiseert een nieuw exemplaar van de [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | De vulmodus. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Voegt een nieuwe figuur toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | De toe te voegen figuur. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Voegt nieuwe figuren toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | De toe te voegen figuren. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Voegt het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) toe aan dit pad.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | De [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om toe te voegen. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Voegt het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) toe aan dit pad.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | De [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om toe te voegen. |
| verbinden | bool | Een Booleaanse waarde die aangeeft of de eerste figuur in het toegevoegde pad deel uitmaakt van de laatste figuur in dit pad. Een waarde van true geeft aan dat de eerste figuur in het toegevoegde pad deel uitmaakt van de laatste figuur in dit pad. Een waarde van false geeft aan dat de eerste figuur in het toegevoegde pad gescheiden is van de laatste figuur in dit pad. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Voert een diepe kloon uit van dit grafische pad.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Een diepe kloon van het graphics pad. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Past de opgegeven transformatie toe en converteert vervolgens elke curve in dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) naar een reeks verbonden lijnsegmenten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Een [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) vóór het afvlakken getransformeerd wordt. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Converteert elke curve in dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) naar een reeks verbonden lijnsegmenten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Een [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) vóór het afvlakken getransformeerd wordt. |
| vlakheid | float | Specificeert de maximaal toegestane fout tussen de curve en zijn afgevlakte benadering. Een waarde van 0,25 is de standaard. Het verlagen van de vlakheidswaarde zal het aantal lijnsegmenten in de benadering verhogen. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Haalt de grenzen van het object op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De geschatte grenzen van het object. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Haalt de grenzen van het object op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De pen die voor het object wordt gebruikt. Dit kan de grootte van de objectgrenzen beïnvloeden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De geschatte grenzen van het object. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die de te testen locatie specificeert. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De [Pen](/psd/python-net/aspose.psd/pen/) om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/); anders false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die de te testen locatie specificeert. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De [Pen](/psd/python-net/aspose.psd/pen/) om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/); anders false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/) en met behulp van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die de te testen locatie specificeert. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De [Pen](/psd/python-net/aspose.psd/pen/) om te testen. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | De [Graphics](/psd/python-net/aspose.psd/graphics/) waarvoor de zichtbaarheid getest moet worden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt zoals getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/); anders false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/) en met behulp van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die de te testen locatie specificeert. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De [Pen](/psd/python-net/aspose.psd/pen/) om te testen. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | De [Graphics](/psd/python-net/aspose.psd/graphics/) waarvoor de zichtbaarheid getest moet worden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt zoals getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/); anders false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het te testen punt. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De [Pen](/psd/python-net/aspose.psd/pen/) om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/); anders false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van het te testen punt. |
| y | int | De y-coördinaat van het te testen punt. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De [Pen](/psd/python-net/aspose.psd/pen/) om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/); anders false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/) en met behulp van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het te testen punt. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De [Pen](/psd/python-net/aspose.psd/pen/) om te testen. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | De [Graphics](/psd/python-net/aspose.psd/graphics/) waarvoor de zichtbaarheid getest moet worden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt zoals getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/); anders false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) wanneer getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/) en met behulp van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van het te testen punt. |
| y | int | De y-coördinaat van het te testen punt. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De [Pen](/psd/python-net/aspose.psd/pen/) om te testen. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | De [Graphics](/psd/python-net/aspose.psd/graphics/) waarvoor de zichtbaarheid getest moet worden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen (onder) de omtrek van dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt zoals getekend met de opgegeven [Pen](/psd/python-net/aspose.psd/pen/); anders false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die het te testen punt vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt; anders false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die het te testen punt vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt; anders false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die het te testen punt vertegenwoordigt. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | De [Graphics](/psd/python-net/aspose.psd/graphics/) waarvoor de zichtbaarheid getest moet worden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen dit bevindt; anders false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die het te testen punt vertegenwoordigt. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | De [Graphics](/psd/python-net/aspose.psd/graphics/) waarvoor de zichtbaarheid getest moet worden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen dit bevindt; anders false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het te testen punt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt; anders false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van het te testen punt. |
| y | int | De y-coördinaat van het te testen punt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt; anders false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in de zichtbare knipregio van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het te testen punt. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | De [Graphics](/psd/python-net/aspose.psd/graphics/) waarvoor de zichtbaarheid getest moet worden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt; anders false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Geeft aan of het opgegeven punt zich bevindt binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in de zichtbare knipregio van de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van het te testen punt. |
| y | int | De y-coördinaat van het te testen punt. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | De [Graphics](/psd/python-net/aspose.psd/graphics/) waarvoor de zichtbaarheid getest moet worden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het opgegeven punt zich binnen dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevindt; anders false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Verwijdert een figuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | De figuur om te verwijderen. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Verwijdert figuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | De figuren om te verwijderen. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Past de opgegeven transformatie toe op de vorm.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | De toe te passen transformatie. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die een parallellogram definiëren waartoe de rechthoek gedefinieerd door <paramref name="srcRect" /> wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechteronderhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) die de rechthoek vertegenwoordigt die wordt getransformeerd naar het parallellogram gedefinieerd door <paramref name="destPoints" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die een parallellogram definiëren waartoe de rechthoek gedefinieerd door <paramref name="srcRect" /> wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechteronderhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) die de rechthoek vertegenwoordigt die wordt getransformeerd naar het parallellogram gedefinieerd door <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Een [Matrix](/psd/python-net/aspose.psd/matrix/) die een geometrische transformatie specificeert die op het pad moet worden toegepast. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die een parallellogram definiëren waartoe de rechthoek gedefinieerd door <paramref name="srcRect" /> wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechteronderhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) die de rechthoek vertegenwoordigt die wordt getransformeerd naar het parallellogram gedefinieerd door <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Een [Matrix](/psd/python-net/aspose.psd/matrix/) die een geometrische transformatie specificeert die op het pad moet worden toegepast. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Een [WarpMode](/psd/python-net/aspose.psd/warpmode/) enumeratie die aangeeft of deze vervormingsbewerking perspectief- of bilineaire modus gebruikt. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Past een warp-transformatie toe, gedefinieerd door een rechthoek en een parallellogram, op dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die een parallellogram definiëren waartoe de rechthoek gedefinieerd door <paramref name="srcRect" /> wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechteronderhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) die de rechthoek vertegenwoordigt die wordt getransformeerd naar het parallellogram gedefinieerd door <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Een [Matrix](/psd/python-net/aspose.psd/matrix/) die een geometrische transformatie specificeert die op het pad moet worden toegepast. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Een [WarpMode](/psd/python-net/aspose.psd/warpmode/) enumeratie die aangeeft of deze vervormingsbewerking perspectief- of bilineaire modus gebruikt. |
| flatness | float | Een waarde van 0 tot 1 die aangeeft hoe vlak het resulterende pad is. Zie voor meer informatie de [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) methoden. |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Voegt een extra omtrek toe aan het pad.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Een [Pen](/psd/python-net/aspose.psd/pen/) die de breedte specificeert tussen de oorspronkelijke omtrek van het pad en de nieuwe omtrek die deze methode creëert. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Voegt een extra omtrek toe aan het [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Een [Pen](/psd/python-net/aspose.psd/pen/) die de breedte specificeert tussen de oorspronkelijke omtrek van het pad en de nieuwe omtrek die deze methode creëert. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Een [Matrix](/psd/python-net/aspose.psd/matrix/) die een transformatie specificeert die op het pad moet worden toegepast vóór het verbreden. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Vervangt dit [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) door curven die het gebied omsluiten dat wordt gevuld wanneer dit pad wordt getekend met de opgegeven pen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Een [Pen](/psd/python-net/aspose.psd/pen/) die de breedte specificeert tussen de oorspronkelijke omtrek van het pad en de nieuwe omtrek die deze methode creëert. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Een [Matrix](/psd/python-net/aspose.psd/matrix/) die een transformatie specificeert die op het pad moet worden toegepast vóór het verbreden. |
| vlakheid | float | Een waarde die de vlakheid voor curven specificeert. |

