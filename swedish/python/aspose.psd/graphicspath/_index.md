---
title: "GraphicsPath-klass"
type: docs
weight: 1570
url: /sv/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initierar en ny instans av klassen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initierar en ny instans av klassen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initierar en ny instans av klassen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initierar en ny instans av klassen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Hämtar eller anger objektets gränser. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Hämtar sökvägsfigurerna. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Hämtar eller anger en [FillMode](/psd/python-net/aspose.psd/fillmode/)‑enumeration som bestämmer hur innanmålen av former i denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) fylls. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Lägger till en ny figur. |
| [add_figures(figures)](#add_figures_figures_2) | Lägger till nya figurer. |
| [add_path(adding_path)](#add_path_adding_path_3) | Lägger till den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) till denna sökväg. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Lägger till den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) till denna sökväg. |
| [deep_clone()](#deep_clone__5) | Utför en djup kloning av denna grafikväg. |
| flatten() | Konverterar varje kurva i denna sökväg till en sekvens av sammanhängande linjesegment. |
| [flatten(matrix)](#flatten_matrix_6) | Tillämpar den angivna transformen och konverterar sedan varje kurva i denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) till en sekvens av sammanhängande linjesegment. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Konverterar varje kurva i denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) till en sekvens av sammanhängande linjesegment. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Hämtar objektets gränser. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/) och med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/) och med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/) och med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/) och med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point)](#is_visible_point_18) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) i den synliga klippningsregionen för den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) i den synliga klippningsregionen för den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_26) | Tar bort en figur. |
| [remove_figures(figures)](#remove_figures_figures_27) | Tar bort figurer. |
| reset() | Tömmer grafikvägen och sätter [FillMode](/psd/python-net/aspose.psd/fillmode/) till [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Vänder ordningen på figurer, former och punkter i varje form i denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [transform(transform)](#transform_transform_28) | Tillämpar den angivna transformationen på formen. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | Lägger till en extra kontur till sökvägen. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Lägger till en extra kontur till [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Ersätter denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) med kurvor som omsluter området som fylls när denna sökväg ritas med den angivna pen. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initierar en ny instans av klassen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initierar en ny instans av klassen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Figurerna att initiera från. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initierar en ny instans av klassen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Figurerna att initiera från. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Fyllningsläget. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initierar en ny instans av klassen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Fyllningsläget. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Lägger till en ny figur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Figuren att lägga till. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Lägger till nya figurer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Figurerna att lägga till. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Lägger till den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) till denna sökväg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) att lägga till. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Lägger till den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) till denna sökväg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) att lägga till. |
| anslut | bool | Ett Boolean‑värde som anger om den första figuren i den tillagda banan är en del av den sista figuren i denna bana. Ett värde på true anger att den första figuren i den tillagda banan är en del av den sista figuren i denna bana. Ett värde på false anger att den första figuren i den tillagda banan är separat från den sista figuren i denna bana. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Utför en djup kloning av denna grafikväg.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | En djup klon av grafikbanan. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Tillämpar den angivna transformen och konverterar sedan varje kurva i denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) till en sekvens av sammanhängande linjesegment.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | En [Matrix](/psd/python-net/aspose.psd/matrix/) för att transformera denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) innan den plattas. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Konverterar varje kurva i denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) till en sekvens av sammanhängande linjesegment.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | En [Matrix](/psd/python-net/aspose.psd/matrix/) för att transformera denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) innan den plattas. |
| platthet | float | Anger det maximalt tillåtna felet mellan kurvan och dess plattade approximation. Ett värde på 0,25 är standard. Att minska platthetsvärdet kommer att öka antalet linjesegment i approximationen. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriserna som ska tillämpas innan gränser beräknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Det uppskattade objektets gränser. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriserna som ska tillämpas innan gränser beräknas. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Pennan som ska användas för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Det uppskattade objektets gränser. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | En [PointF](/psd/python-net/aspose.psd/pointf/) som anger platsen att testa. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Den [Pen](/psd/python-net/aspose.psd/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/); annars false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | En [PointF](/psd/python-net/aspose.psd/pointf/) som anger platsen att testa. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Den [Pen](/psd/python-net/aspose.psd/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/); annars false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/) och med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | En [PointF](/psd/python-net/aspose.psd/pointf/) som anger platsen att testa. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Den [Pen](/psd/python-net/aspose.psd/pen/) att testa. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Den [Graphics](/psd/python-net/aspose.psd/graphics/) för vilken man ska testa synlighet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/); annars false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/) och med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | En [PointF](/psd/python-net/aspose.psd/pointf/) som anger platsen att testa. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Den [Pen](/psd/python-net/aspose.psd/pen/) att testa. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Den [Graphics](/psd/python-net/aspose.psd/graphics/) för vilken man ska testa synlighet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/); annars false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Den [Pen](/psd/python-net/aspose.psd/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/); annars false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Den [Pen](/psd/python-net/aspose.psd/pen/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/); annars false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/) och med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Den [Pen](/psd/python-net/aspose.psd/pen/) att testa. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Den [Graphics](/psd/python-net/aspose.psd/graphics/) för vilken man ska testa synlighet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/); annars false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Anger om den angivna punkten ligger inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/) och med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Den [Pen](/psd/python-net/aspose.psd/pen/) att testa. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Den [Graphics](/psd/python-net/aspose.psd/graphics/) för vilken man ska testa synlighet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) när den ritas med den angivna [Pen](/psd/python-net/aspose.psd/pen/); annars false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | En [PointF](/psd/python-net/aspose.psd/pointf/) som representerar punkten att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); annars false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | En [PointF](/psd/python-net/aspose.psd/pointf/) som representerar punkten att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); annars false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | En [PointF](/psd/python-net/aspose.psd/pointf/) som representerar punkten att testa. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Den [Graphics](/psd/python-net/aspose.psd/graphics/) för vilken man ska testa synlighet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom detta; annars false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | En [PointF](/psd/python-net/aspose.psd/pointf/) som representerar punkten att testa. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Den [Graphics](/psd/python-net/aspose.psd/graphics/) för vilken man ska testa synlighet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom detta; annars false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); annars false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); annars false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) i den synliga klippningsregionen för den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Den [Graphics](/psd/python-net/aspose.psd/graphics/) för vilken man ska testa synlighet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); annars false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Anger om den angivna punkten ligger inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) i den synliga klippningsregionen för den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Den [Graphics](/psd/python-net/aspose.psd/graphics/) för vilken man ska testa synlighet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den angivna punkten finns inom denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); annars false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Tar bort en figur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Figuren att ta bort. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Tar bort figurer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Figurerna att ta bort. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Transformationen att tillämpa. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | En array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar ett parallellogram till vilket rektangeln som definieras av <paramref name="srcRect" /> transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, underförstås det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av <paramref name="destPoints" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | En array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar ett parallellogram till vilket rektangeln som definieras av <paramref name="srcRect" /> transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, underförstås det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | En [Matrix](/psd/python-net/aspose.psd/matrix/) som specificerar en geometrisk transformation att applicera på banan. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | En array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar ett parallellogram till vilket rektangeln definierad av <paramref name="srcRect" /> transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, underförstås det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | En [Matrix](/psd/python-net/aspose.psd/matrix/) som specificerar en geometrisk transformation att applicera på banan. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | En [WarpMode](/psd/python-net/aspose.psd/warpmode/) enumeration som specificerar om denna warp‑operation använder perspektiv‑ eller bilineärt läge. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | En array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar ett parallellogram till vilket rektangeln som definieras av <paramref name="srcRect" /> transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, underförstås det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | En [Matrix](/psd/python-net/aspose.psd/matrix/) som specificerar en geometrisk transformation att applicera på banan. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | En [WarpMode](/psd/python-net/aspose.psd/warpmode/) enumeration som specificerar om denna warp‑operation använder perspektiv‑ eller bilineärt läge. |
| flatness | float | Ett värde från 0 till 1 som anger hur platt den resulterande banan är. För mer information, se metoderna [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/). |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Lägger till en extra kontur till sökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | En [Pen](/psd/python-net/aspose.psd/pen/) som anger bredden mellan den ursprungliga konturen av banan och den nya kontur som denna metod skapar. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Lägger till en extra kontur till [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | En [Pen](/psd/python-net/aspose.psd/pen/) som anger bredden mellan den ursprungliga konturen av banan och den nya kontur som denna metod skapar. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | En [Matrix](/psd/python-net/aspose.psd/matrix/) som anger en transform att tillämpa på banan innan den breddas. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Ersätter denna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) med kurvor som omsluter området som fylls när denna sökväg ritas med den angivna pen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | En [Pen](/psd/python-net/aspose.psd/pen/) som anger bredden mellan den ursprungliga konturen av banan och den nya kontur som denna metod skapar. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | En [Matrix](/psd/python-net/aspose.psd/matrix/) som anger en transform att tillämpa på banan innan den breddas. |
| platthet | float | Ett värde som anger plattheten för kurvor. |

