---
title: Region Class
type: docs
weight: 3800
url: /python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Region()](#Region__1) | Initializes a new [Region](/psd/python-net/aspose.psd/region/). |
| [Region(path)](#Region_path_2) | Initializes a new [Region](/psd/python-net/aspose.psd/region/) with the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [Region(rect)](#Region_rect_3) | Initializes a new [Region](/psd/python-net/aspose.psd/region/) from the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [Region(rect)](#Region_rect_4) | Initializes a new [Region](/psd/python-net/aspose.psd/region/) from the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [complement(path)](#complement_path_1) | Updates this [Region](/psd/python-net/aspose.psd/region/) to contain the portion of the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) that does not intersect with this [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_2) | Updates this [Region](/psd/python-net/aspose.psd/region/) to contain the portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that does not intersect with this [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_3) | Updates this [Region](/psd/python-net/aspose.psd/region/) to contain the portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that does not intersect with this [Region](/psd/python-net/aspose.psd/region/). |
| [complement(region)](#complement_region_4) | Updates this [Region](/psd/python-net/aspose.psd/region/) to contain the portion of the specified [Region](/psd/python-net/aspose.psd/region/) that does not intersect with this [Region](/psd/python-net/aspose.psd/region/). |
| [deep_clone()](#deep_clone__5) | Creates an exact deep copy of this [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | Updates this [Region](/psd/python-net/aspose.psd/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [exclude(rect)](#exclude_rect_7) | Updates this [Region](/psd/python-net/aspose.psd/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [exclude(rect)](#exclude_rect_8) | Updates this [Region](/psd/python-net/aspose.psd/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [exclude(region)](#exclude_region_9) | Updates this [Region](/psd/python-net/aspose.psd/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/psd/python-net/aspose.psd/region/). |
| [intersect(path)](#intersect_path_10) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the intersection of itself with the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [intersect(rect)](#intersect_rect_11) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the intersection of itself with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [intersect(rect)](#intersect_rect_12) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the intersection of itself with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [intersect(region)](#intersect_region_13) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the intersection of itself with the specified [Region](/psd/python-net/aspose.psd/region/). |
| [is_empty(g)](#is_empty_g_14) | Tests whether this [Region](/psd/python-net/aspose.psd/region/) has an empty interior on the specified drawing surface. |
| [is_infinite(g)](#is_infinite_g_15) | Tests whether this [Region](/psd/python-net/aspose.psd/region/) has an infinite interior on the specified drawing surface. |
| [is_visible(point)](#is_visible_point_16) | Tests whether the specified [PointF](/psd/python-net/aspose.psd/pointf/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point)](#is_visible_point_17) | Tests whether the specified [PointF](/psd/python-net/aspose.psd/pointf/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point, g)](#is_visible_point_g_18) | Tests whether the specified [PointF](/psd/python-net/aspose.psd/pointf/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point, g)](#is_visible_point_g_19) | Tests whether the specified [PointF](/psd/python-net/aspose.psd/pointf/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect)](#is_visible_rect_20) | Tests whether any portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect)](#is_visible_rect_21) | Tests whether any portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Tests whether any portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Tests whether any portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y)](#is_visible_x_y_24) | Tests whether the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Tests whether the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Tests whether the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Tests whether any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Tests whether any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Tests whether any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Tests whether any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/). |
| make_empty() | Initializes this [Region](/psd/python-net/aspose.psd/region/) to an empty interior. |
| make_infinite() | Initializes this [Region](/psd/python-net/aspose.psd/region/) object to an infinite interior. |
| [transform(matrix)](#transform_matrix_31) | Transforms this [Region](/psd/python-net/aspose.psd/region/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [translate(dx, dy)](#translate_dx_dy_32) | Offsets the coordinates of this [Region](/psd/python-net/aspose.psd/region/) by the specified amount. |
| [translate(dx, dy)](#translate_dx_dy_33) | Offsets the coordinates of this [Region](/psd/python-net/aspose.psd/region/) by the specified amount. |
| [union(path)](#union_path_34) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the union of itself and the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [union(rect)](#union_rect_35) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the union of itself and the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [union(rect)](#union_rect_36) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the union of itself and the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [union(region)](#union_region_37) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the union of itself and the specified [Region](/psd/python-net/aspose.psd/region/). |
| [xor(path)](#xor_path_38) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [xor(rect)](#xor_rect_39) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the union minus the intersection of itself with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [xor(rect)](#xor_rect_40) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the union minus the intersection of itself with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [xor(region)](#xor_region_41) | Updates this [Region](/psd/python-net/aspose.psd/region/) to the union minus the intersection of itself with the specified [Region](/psd/python-net/aspose.psd/region/). |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Initializes a new [Region](/psd/python-net/aspose.psd/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Initializes a new [Region](/psd/python-net/aspose.psd/region/) with the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | A [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) that defines the new [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Initializes a new [Region](/psd/python-net/aspose.psd/region/) from the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that defines the interior of the new [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Initializes a new [Region](/psd/python-net/aspose.psd/region/) from the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that defines the interior of the new [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to contain the portion of the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) that does not intersect with this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to complement this [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to contain the portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that does not intersect with this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to complement this [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to contain the portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that does not intersect with this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to complement this [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to contain the portion of the specified [Region](/psd/python-net/aspose.psd/region/) that does not intersect with this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | The [Region](/psd/python-net/aspose.psd/region/) object to complement this [Region](/psd/python-net/aspose.psd/region/) object. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Creates an exact deep copy of this [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| Type | Description |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | The [Region](/psd/python-net/aspose.psd/region/) that this method creates. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to exclude from this [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to exclude from this [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to exclude from this [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | The [Region](/psd/python-net/aspose.psd/region/) to exclude from this [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the intersection of itself with the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to intersect with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the intersection of itself with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to intersect with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the intersection of itself with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to intersect with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the intersection of itself with the specified [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | The [Region](/psd/python-net/aspose.psd/region/) to intersect with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Tests whether this [Region](/psd/python-net/aspose.psd/region/) has an empty interior on the specified drawing surface.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a drawing surface. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the interior of this [Region](/psd/python-net/aspose.psd/region/) is empty when the transformation associated with <paramref name="g" /> is applied; otherwise, false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Tests whether this [Region](/psd/python-net/aspose.psd/region/) has an infinite interior on the specified drawing surface.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a drawing surface. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the interior of this [Region](/psd/python-net/aspose.psd/region/) is infinite when the transformation associated with <paramref name="g" /> is applied; otherwise, false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Tests whether the specified [PointF](/psd/python-net/aspose.psd/pointf/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Tests whether the specified [PointF](/psd/python-net/aspose.psd/pointf/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | The [PointF](/psd/python-net/aspose.psd/pointf/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Tests whether the specified [PointF](/psd/python-net/aspose.psd/pointf/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) structure to test. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Tests whether the specified [PointF](/psd/python-net/aspose.psd/pointf/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | The [PointF](/psd/python-net/aspose.psd/pointf/) structure to test. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="point" /> is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Tests whether any portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of <paramref name="rect" /> is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Tests whether any portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of <paramref name="rect" /> is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Tests whether any portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to test. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="rect" /> is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Tests whether any portion of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to test. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when <paramref name="rect" /> is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Tests whether the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Tests whether the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True when the specified point is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/) object; otherwise, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/) object; otherwise, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | float | The width of the rectangle to test. |
| height | float | The height of the rectangle to test. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Tests whether any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/) when drawn using the specified [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the upper-left corner of the rectangle to test. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to test. |
| width | int | The width of the rectangle to test. |
| height | int | The height of the rectangle to test. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | A [Graphics](/psd/python-net/aspose.psd/graphics/) that represents a graphics context. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true when any portion of the specified rectangle is contained within this [Region](/psd/python-net/aspose.psd/region/); otherwise, false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Transforms this [Region](/psd/python-net/aspose.psd/region/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) by which to transform this [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Offsets the coordinates of this [Region](/psd/python-net/aspose.psd/region/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The amount to offset this [Region](/psd/python-net/aspose.psd/region/) horizontally. |
| dy | float | The amount to offset this [Region](/psd/python-net/aspose.psd/region/) vertically. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Offsets the coordinates of this [Region](/psd/python-net/aspose.psd/region/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | int | The amount to offset this [Region](/psd/python-net/aspose.psd/region/) horizontally. |
| dy | int | The amount to offset this [Region](/psd/python-net/aspose.psd/region/) vertically. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the union of itself and the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to unite with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the union of itself and the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to unite with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the union of itself and the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to unite with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the union of itself and the specified [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | The [Region](/psd/python-net/aspose.psd/region/) to unite with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to xor with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the union minus the intersection of itself with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to xor with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the union minus the intersection of itself with the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to xor with this [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Updates this [Region](/psd/python-net/aspose.psd/region/) to the union minus the intersection of itself with the specified [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | The [Region](/psd/python-net/aspose.psd/region/) to xor with this [Region](/psd/python-net/aspose.psd/region/). |

