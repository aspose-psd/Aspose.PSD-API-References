---
title: GraphicsPath Class
type: docs
weight: 1560
url: /python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Initializes a new instance of the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) class. |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Initializes a new instance of the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) class. |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Initializes a new instance of the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) class. |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Initializes a new instance of the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets or sets the object's bounds. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Gets the path figures. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Gets or sets a [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeration that determines how the interiors of shapes in this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) are filled. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Adds a new figure. |
| [add_figures(figures)](#add_figures_figures_2) | Adds new figures. |
| [add_path(adding_path)](#add_path_adding_path_3) | Appends the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to this path. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Appends the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to this path. |
| [deep_clone()](#deep_clone__5) | Performs a deep clone of this graphics path. |
| flatten() | Converts each curve in this path into a sequence of connected line segments. |
| [flatten(matrix)](#flatten_matrix_6) | Applies the specified transform and then converts each curve in this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) into a sequence of connected line segments. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Converts each curve in this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) into a sequence of connected line segments. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Gets the object's bounds. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/) and using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/) and using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/) and using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/) and using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point)](#is_visible_point_18) | Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in the visible clip region of the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in the visible clip region of the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_26) | Removes a figure. |
| [remove_figures(figures)](#remove_figures_figures_27) | Removes figures. |
| reset() | Empties the graphics path and sets the [FillMode](/psd/python-net/aspose.psd/fillmode/) to [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Reverses the order of figures, shapes, and points in each shape of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [transform(transform)](#transform_transform_28) | Applies the specified transformation to the shape. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | Adds an additional outline to the path. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Adds an additional outline to the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Replaces this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) with curves that enclose the area that is filled when this path is drawn by the specified pen. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Initializes a new instance of the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) class.

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Initializes a new instance of the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | The figures to initialize from. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Initializes a new instance of the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | The figures to initialize from. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | The fill mode. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Initializes a new instance of the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | The fill mode. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Adds a new figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | The figure to add. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Adds new figures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | The figures to add. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Appends the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to this path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to add. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Appends the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to this path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to add. |
| connect | bool | A Boolean value that specifies whether the first figure in the added path is part of the last figure in this path. A value of true specifies that the first figure in the added path is part of the last figure in this path. A value of false specifies that the first figure in the added path is separate from the last figure in this path. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Performs a deep clone of this graphics path.

**Returns**

| Type | Description |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | A deep clone of the graphics path. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Applies the specified transform and then converts each curve in this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) into a sequence of connected line segments.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | A [Matrix](/psd/python-net/aspose.psd/matrix/) by which to transform this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) before flattening. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Converts each curve in this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) into a sequence of connected line segments.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | A [Matrix](/psd/python-net/aspose.psd/matrix/) by which to transform this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) before flattening. |
| flatness | float | Specifies the maximum permitted error between the curve and its flattened approximation. A value of 0.25 is the default. Reducing the flatness value will increase the number of line segments in the approximation. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The estimated object's bounds. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The estimated object's bounds. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | A [PointF](/psd/python-net/aspose.psd/pointf/) that specifies the location to test. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The [Pen](/psd/python-net/aspose.psd/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/); otherwise, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | A [PointF](/psd/python-net/aspose.psd/pointf/) that specifies the location to test. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The [Pen](/psd/python-net/aspose.psd/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/); otherwise, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/) and using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | A [PointF](/psd/python-net/aspose.psd/pointf/) that specifies the location to test. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The [Pen](/psd/python-net/aspose.psd/pen/) to test. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | The [Graphics](/psd/python-net/aspose.psd/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) as drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/); otherwise, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/) and using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | A [PointF](/psd/python-net/aspose.psd/pointf/) that specifies the location to test. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The [Pen](/psd/python-net/aspose.psd/pen/) to test. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | The [Graphics](/psd/python-net/aspose.psd/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) as drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/); otherwise, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The [Pen](/psd/python-net/aspose.psd/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/); otherwise, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The [Pen](/psd/python-net/aspose.psd/pen/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/); otherwise, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/) and using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The [Pen](/psd/python-net/aspose.psd/pen/) to test. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | The [Graphics](/psd/python-net/aspose.psd/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) as drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/); otherwise, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indicates whether the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) when drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/) and using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | The [Pen](/psd/python-net/aspose.psd/pen/) to test. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | The [Graphics](/psd/python-net/aspose.psd/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within (under) the outline of this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) as drawn with the specified [Pen](/psd/python-net/aspose.psd/pen/); otherwise, false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | A [PointF](/psd/python-net/aspose.psd/pointf/) that represents the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); otherwise, false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | A [PointF](/psd/python-net/aspose.psd/pointf/) that represents the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); otherwise, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | A [PointF](/psd/python-net/aspose.psd/pointf/) that represents the point to test. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | The [Graphics](/psd/python-net/aspose.psd/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this; otherwise, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | A [PointF](/psd/python-net/aspose.psd/pointf/) that represents the point to test. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | The [Graphics](/psd/python-net/aspose.psd/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this; otherwise, false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); otherwise, false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); otherwise, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in the visible clip region of the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | The [Graphics](/psd/python-net/aspose.psd/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); otherwise, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Indicates whether the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in the visible clip region of the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | The [Graphics](/psd/python-net/aspose.psd/graphics/) for which to test visibility. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the specified point is contained within this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); otherwise, false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Removes a figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | The figure to remove. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Removes figures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | The figures to remove. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | The transformation to apply. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define a parallelogram to which the rectangle defined by <paramref name="srcRect" /> is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) that represents the rectangle that is transformed to the parallelogram defined by <paramref name="destPoints" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define a parallelogram to which the rectangle defined by <paramref name="srcRect" /> is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) that represents the rectangle that is transformed to the parallelogram defined by <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | A [Matrix](/psd/python-net/aspose.psd/matrix/) that specifies a geometric transform to apply to the path. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that defines a parallelogram to which the rectangle defined by <paramref name="srcRect" /> is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) that represents the rectangle that is transformed to the parallelogram defined by <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | A [Matrix](/psd/python-net/aspose.psd/matrix/) that specifies a geometric transform to apply to the path. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | A [WarpMode](/psd/python-net/aspose.psd/warpmode/) enumeration that specifies whether this warp operation uses perspective or bilinear mode. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Applies a warp transform, defined by a rectangle and a parallelogram, to this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define a parallelogram to which the rectangle defined by <paramref name="srcRect" /> is transformed. The array can contain either three or four elements. If the array contains three elements, the lower-right corner of the parallelogram is implied by the first three points. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) that represents the rectangle that is transformed to the parallelogram defined by <paramref name="destPoints" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | A [Matrix](/psd/python-net/aspose.psd/matrix/) that specifies a geometric transform to apply to the path. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | A [WarpMode](/psd/python-net/aspose.psd/warpmode/) enumeration that specifies whether this warp operation uses perspective or bilinear mode. |
| flatness | float | A value from 0 through 1 that specifies how flat the resulting path is. For more information, see the [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) methods. |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Adds an additional outline to the path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | A [Pen](/psd/python-net/aspose.psd/pen/) that specifies the width between the original outline of the path and the new outline this method creates. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Adds an additional outline to the [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | A [Pen](/psd/python-net/aspose.psd/pen/) that specifies the width between the original outline of the path and the new outline this method creates. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | A [Matrix](/psd/python-net/aspose.psd/matrix/) that specifies a transform to apply to the path before widening. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Replaces this [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) with curves that enclose the area that is filled when this path is drawn by the specified pen.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | A [Pen](/psd/python-net/aspose.psd/pen/) that specifies the width between the original outline of the path and the new outline this method creates. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | A [Matrix](/psd/python-net/aspose.psd/matrix/) that specifies a transform to apply to the path before widening. |
| flatness | float | A value that specifies the flatness for curves. |

