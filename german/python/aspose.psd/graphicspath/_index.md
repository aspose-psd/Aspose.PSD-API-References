---
title: "GraphicsPath Klasse"
type: docs
weight: 1570
url: /de/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initialisiert eine neue Instanz der Klasse [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initialisiert eine neue Instanz der Klasse [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initialisiert eine neue Instanz der Klasse [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initialisiert eine neue Instanz der Klasse [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Liest oder setzt die Grenzen des Objekts. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Liest die Pfadfiguren. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Liest oder setzt eine [FillMode](/psd/python-net/aspose.psd/fillmode/) Aufzählung, die bestimmt, wie die Innenbereiche von Formen in diesem [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) gefüllt werden. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Fügt eine neue Figur hinzu. |
| [add_figures(figures)](#add_figures_figures_2) | Fügt neue Figuren hinzu. |
| [add_path(adding_path)](#add_path_adding_path_3) | Hängt den angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an diesen Pfad an. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Hängt den angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an diesen Pfad an. |
| [deep_clone()](#deep_clone__5) | Führt eine tiefe Kopie dieses Grafikpfads aus. |
| flatten() | Wandelt jede Kurve in diesem Pfad in eine Sequenz verbundener Liniensegmente um. |
| [flatten(matrix)](#flatten_matrix_6) | Wendet die angegebene Transformation an und wandelt dann jede Kurve in diesem [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in eine Sequenz verbundener Liniensegmente um. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Wandelt jede Kurve in diesem [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in eine Sequenz verbundener Liniensegmente um. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Liest die Begrenzungen des Objekts. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird und das angegebene [Graphics](/psd/python-net/aspose.psd/graphics/) verwendet wird. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird und das angegebene [Graphics](/psd/python-net/aspose.psd/graphics/) verwendet wird. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird und das angegebene [Graphics](/psd/python-net/aspose.psd/graphics/) verwendet wird. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird und das angegebene [Graphics](/psd/python-net/aspose.psd/graphics/) verwendet wird. |
| [is_visible(point)](#is_visible_point_18) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt. |
| [is_visible(point)](#is_visible_point_19) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt. |
| [is_visible(x, y)](#is_visible_x_y_22) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt. |
| [is_visible(x, y)](#is_visible_x_y_23) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) liegt. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) liegt. |
| [remove_figure(figure)](#remove_figure_figure_26) | Entfernt eine Figur. |
| [remove_figures(figures)](#remove_figures_figures_27) | Entfernt Figuren. |
| reset() | Leert den Grafikpfad und setzt die [FillMode](/psd/python-net/aspose.psd/fillmode/) auf [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Kehrt die Reihenfolge von Figuren, Formen und Punkten in jeder Form dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) um. |
| [transform(transform)](#transform_transform_28) | Wendet die angegebene Transformation auf die Form an. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an. |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an. |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an. |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an. |
| [widen(pen)](#widen_pen_33) | Fügt dem Pfad eine zusätzliche Kontur hinzu. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Fügt dem [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) eine zusätzliche Kontur hinzu. |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Ersetzt diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initialisiert eine neue Instanz der Klasse [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initialisiert eine neue Instanz der Klasse [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Die Figuren, von denen initialisiert werden soll. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initialisiert eine neue Instanz der Klasse [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Die Figuren, von denen initialisiert werden soll. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Der Füllmodus. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initialisiert eine neue Instanz der Klasse [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Der Füllmodus. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Fügt eine neue Figur hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Die hinzuzufügende Figur. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Fügt neue Figuren hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Die hinzuzufügenden Figuren. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Hängt den angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an diesen Pfad an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den hinzuzufügenden [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Hängt den angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an diesen Pfad an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den hinzuzufügenden [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| verbinden | bool | Ein boolescher Wert, der angibt, ob die erste Figur im hinzugefügten Pfad Teil der letzten Figur in diesem Pfad ist. Der Wert true gibt an, dass die erste Figur im hinzugefügten Pfad Teil der letzten Figur in diesem Pfad ist. Der Wert false gibt an, dass die erste Figur im hinzugefügten Pfad von der letzten Figur in diesem Pfad getrennt ist. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Führt eine tiefe Kopie dieses Grafikpfads aus.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ein tiefer Klon des Grafikpfads. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Wendet die angegebene Transformation an und wandelt dann jede Kurve in diesem [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in eine Sequenz verbundener Liniensegmente um.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Eine [Matrix](/psd/python-net/aspose.psd/matrix/), mit der dieser [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) vor dem Flachlegen transformiert wird. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Wandelt jede Kurve in diesem [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in eine Sequenz verbundener Liniensegmente um.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Eine [Matrix](/psd/python-net/aspose.psd/matrix/), mit der dieser [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) vor dem Flachlegen transformiert wird. |
| Flachheit | float | Gibt den maximal zulässigen Fehler zwischen der Kurve und ihrer abgeflachten Annäherung an. Der Standardwert ist 0,25. Eine Verringerung des Flachheitswerts erhöht die Anzahl der Liniensegmente in der Annäherung. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die Matrix, die vor der Begrenzung angewendet wird, wird berechnet. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die geschätzten Begrenzungen des Objekts. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die Matrix, die vor der Begrenzung angewendet wird, wird berechnet. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Objektbegrenzungen beeinflussen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die geschätzten Begrenzungen des Objekts. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der zu testende [Pen](/psd/python-net/aspose.psd/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der zu testende [Pen](/psd/python-net/aspose.psd/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird und das angegebene [Graphics](/psd/python-net/aspose.psd/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der zu testende [Pen](/psd/python-net/aspose.psd/pen/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Das [Graphics](/psd/python-net/aspose.psd/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird und das angegebene [Graphics](/psd/python-net/aspose.psd/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), der den zu testenden Ort angibt. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der zu testende [Pen](/psd/python-net/aspose.psd/pen/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Das [Graphics](/psd/python-net/aspose.psd/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der zu testende [Pen](/psd/python-net/aspose.psd/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der zu testende [Pen](/psd/python-net/aspose.psd/pen/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird und das angegebene [Graphics](/psd/python-net/aspose.psd/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der zu testende [Pen](/psd/python-net/aspose.psd/pen/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Das [Graphics](/psd/python-net/aspose.psd/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird; andernfalls false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wenn er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird und das angegebene [Graphics](/psd/python-net/aspose.psd/graphics/) verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der zu testende [Pen](/psd/python-net/aspose.psd/pen/). |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Das [Graphics](/psd/python-net/aspose.psd/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt, wie er mit dem angegebenen [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet wird; andernfalls false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), der den zu testenden Punkt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt; andernfalls false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), der den zu testenden Punkt darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt; andernfalls false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), der den zu testenden Punkt darstellt. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Das [Graphics](/psd/python-net/aspose.psd/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses liegt; andernfalls false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), der den zu testenden Punkt darstellt. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Das [Graphics](/psd/python-net/aspose.psd/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses liegt; andernfalls false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt; andernfalls false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt; andernfalls false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Das [Graphics](/psd/python-net/aspose.psd/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt; andernfalls false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Gibt an, ob der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) im sichtbaren Clip-Bereich des angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Das [Graphics](/psd/python-net/aspose.psd/graphics/), für das die Sichtbarkeit getestet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) liegt; andernfalls false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Entfernt eine Figur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Die zu entfernende Figur. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Entfernt Figuren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Die zu entfernenden Figuren. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Wendet die angegebene Transformation auf die Form an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Die anzuwendende Transformation. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das durch <paramref name=\"srcRect\" /> definierte Rechteck transformiert wird. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein [RectangleF](/psd/python-net/aspose.psd/rectanglef/), das das Rechteck darstellt, das in das durch <paramref name=\"destPoints\" /> definierte Parallelogramm transformiert wird. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das durch <paramref name=\"srcRect\" /> definierte Rechteck transformiert wird. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein [RectangleF](/psd/python-net/aspose.psd/rectanglef/), das das Rechteck darstellt, das in das durch <paramref name=\"destPoints\" /> definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Eine [Matrix](/psd/python-net/aspose.psd/matrix/), die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, das ein Parallelogramm definiert, zu dem das durch <paramref name=\"srcRect\" /> definierte Rechteck transformiert wird. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein [RectangleF](/psd/python-net/aspose.psd/rectanglef/), das das Rechteck darstellt, das in das durch <paramref name=\"destPoints\" /> definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Eine [Matrix](/psd/python-net/aspose.psd/matrix/), die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Eine [WarpMode](/psd/python-net/aspose.psd/warpmode/) Aufzählung, die angibt, ob dieser Verzerrungsvorgang die Perspektiv- oder die bilineare Methode verwendet. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das durch <paramref name=\"srcRect\" /> definierte Rechteck transformiert wird. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein [RectangleF](/psd/python-net/aspose.psd/rectanglef/), das das Rechteck darstellt, das in das durch <paramref name=\"destPoints\" /> definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Eine [Matrix](/psd/python-net/aspose.psd/matrix/), die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Eine [WarpMode](/psd/python-net/aspose.psd/warpmode/) Aufzählung, die angibt, ob dieser Verzerrungsvorgang die Perspektiv- oder die bilineare Methode verwendet. |
| flatness | float | Ein Wert von 0 bis 1, der angibt, wie flach der resultierende Pfad ist. Weitere Informationen finden Sie in den [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) Methoden. |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Fügt dem Pfad eine zusätzliche Kontur hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ein [Pen](/psd/python-net/aspose.psd/pen/), der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Fügt dem [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) eine zusätzliche Kontur hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ein [Pen](/psd/python-net/aspose.psd/pen/), der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Eine [Matrix](/psd/python-net/aspose.psd/matrix/), die eine Transformation angibt, die vor dem Verbreitern auf den Pfad angewendet wird. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Ersetzt diesen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ein [Pen](/psd/python-net/aspose.psd/pen/), der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Eine [Matrix](/psd/python-net/aspose.psd/matrix/), die eine Transformation angibt, die vor dem Verbreitern auf den Pfad angewendet wird. |
| Flachheit | float | Ein Wert, der die Flachheit für Kurven angibt. |

