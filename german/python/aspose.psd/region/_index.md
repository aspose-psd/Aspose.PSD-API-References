---
title: "Region‑Klasse"
type: docs
weight: 3870
url: /de/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Region()](#Region__1) | Initialisiert ein neues [Region](/psd/python-net/aspose.psd/region/). |
| [Region(path)](#Region_path_2) | Initialisiert ein neues [Region](/psd/python-net/aspose.psd/region/) mit dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [Region(rect)](#Region_rect_3) | Initialisiert ein neues [Region](/psd/python-net/aspose.psd/region/) aus der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur. |
| [Region(rect)](#Region_rect_4) | Initialisiert ein neues [Region](/psd/python-net/aspose.psd/region/) aus der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [complement(path)](#complement_path_1) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/), sodass es den Teil des angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) enthält, der nicht mit diesem [Region](/psd/python-net/aspose.psd/region/) überschneidet. |
| [complement(rect)](#complement_rect_2) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/), sodass es den Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur enthält, der nicht mit diesem [Region](/psd/python-net/aspose.psd/region/) überschneidet. |
| [complement(rect)](#complement_rect_3) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/), sodass es den Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur enthält, der nicht mit diesem [Region](/psd/python-net/aspose.psd/region/) überschneidet. |
| [complement(region)](#complement_region_4) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/), sodass es den Teil des angegebenen [Region](/psd/python-net/aspose.psd/region/) enthält, der nicht mit diesem [Region](/psd/python-net/aspose.psd/region/) überschneidet. |
| [deep_clone()](#deep_clone__5) | Erstellt eine exakte Deep‑Copy dieses [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) so, dass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) überschneidet. |
| [exclude(rect)](#exclude_rect_7) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) so, dass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur überschneidet. |
| [exclude(rect)](#exclude_rect_8) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) so, dass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur überschneidet. |
| [exclude(region)](#exclude_region_9) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) so, dass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen [Region](/psd/python-net/aspose.psd/region/) überschneidet. |
| [intersect(path)](#intersect_path_10) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) auf die Schnittmenge mit dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [intersect(rect)](#intersect_rect_11) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) auf die Schnittmenge mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| [intersect(rect)](#intersect_rect_12) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) auf die Schnittmenge mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| [intersect(region)](#intersect_region_13) | Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) auf die Schnittmenge mit dem angegebenen [Region](/psd/python-net/aspose.psd/region/). |
| [is_empty(g)](#is_empty_g_14) | Prüft, ob dieses [Region](/psd/python-net/aspose.psd/region/) auf der angegebenen Zeichenfläche ein leeres Inneres hat. |
| [is_infinite(g)](#is_infinite_g_15) | Prüft, ob dieses [Region](/psd/python-net/aspose.psd/region/) auf der angegebenen Zeichenfläche ein unendliches Inneres hat. |
| [is_visible(point)](#is_visible_point_16) | Prüft, ob die angegebene [PointF](/psd/python-net/aspose.psd/pointf/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt. |
| [is_visible(point)](#is_visible_point_17) | Prüft, ob die angegebene [PointF](/psd/python-net/aspose.psd/pointf/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt. |
| [is_visible(point, g)](#is_visible_point_g_18) | Prüft, ob die angegebene [PointF](/psd/python-net/aspose.psd/pointf/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn sie mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird. |
| [is_visible(point, g)](#is_visible_point_g_19) | Prüft, ob die angegebene [PointF](/psd/python-net/aspose.psd/pointf/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn sie mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird. |
| [is_visible(rect)](#is_visible_rect_20) | Prüft, ob irgendein Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt. |
| [is_visible(rect)](#is_visible_rect_21) | Prüft, ob irgendein Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt. |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Prüft, ob irgendein Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn sie mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird. |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Prüft, ob irgendein Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn sie mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird. |
| [is_visible(x, y)](#is_visible_x_y_24) | Prüft, ob der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt. |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Prüft, ob der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn er mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird. |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Prüft, ob der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn er mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn er mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn er mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird. |
| make_empty() | Initialisiert dieses [Region](/psd/python-net/aspose.psd/region/) mit einem leeren Inneren. |
| make_infinite() | Initialisiert dieses [Region](/psd/python-net/aspose.psd/region/) Objekt mit einem unendlichen Inneren. |
| [transform(matrix)](#transform_matrix_31) | Transformiert diese [Region](/psd/python-net/aspose.psd/region/) mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [translate(dx, dy)](#translate_dx_dy_32) | Verschiebt die Koordinaten dieser [Region](/psd/python-net/aspose.psd/region/) um den angegebenen Betrag. |
| [translate(dx, dy)](#translate_dx_dy_33) | Verschiebt die Koordinaten dieser [Region](/psd/python-net/aspose.psd/region/) um den angegebenen Betrag. |
| [union(path)](#union_path_34) | Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung von sich selbst und dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [union(rect)](#union_rect_35) | Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung von sich selbst und der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| [union(rect)](#union_rect_36) | Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung von sich selbst und der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| [union(region)](#union_region_37) | Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung von sich selbst und der angegebenen [Region](/psd/python-net/aspose.psd/region/). |
| [xor(path)](#xor_path_38) | Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung minus der Schnittmenge von sich selbst mit dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [xor(rect)](#xor_rect_39) | Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung minus der Schnittmenge von sich selbst mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| [xor(rect)](#xor_rect_40) | Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung minus der Schnittmenge von sich selbst mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| [xor(region)](#xor_region_41) | Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung minus der Schnittmenge von sich selbst mit der angegebenen [Region](/psd/python-net/aspose.psd/region/). |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Initialisiert ein neues [Region](/psd/python-net/aspose.psd/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Initialisiert ein neues [Region](/psd/python-net/aspose.psd/region/) mit dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ein [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), der die neue [Region](/psd/python-net/aspose.psd/region/) definiert. |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Initialisiert ein neues [Region](/psd/python-net/aspose.psd/region/) aus der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das Innere der neuen [Region](/psd/python-net/aspose.psd/region/) definiert. |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Initialisiert ein neues [Region](/psd/python-net/aspose.psd/region/) aus der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das Innere der neuen [Region](/psd/python-net/aspose.psd/region/) definiert. |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/), sodass es den Teil des angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) enthält, der nicht mit diesem [Region](/psd/python-net/aspose.psd/region/) überschneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Der [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) zur Ergänzung dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/), sodass es den Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur enthält, der nicht mit diesem [Region](/psd/python-net/aspose.psd/region/) überschneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zur Ergänzung dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/), sodass es den Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur enthält, der nicht mit diesem [Region](/psd/python-net/aspose.psd/region/) überschneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zur Ergänzung dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/), sodass es den Teil des angegebenen [Region](/psd/python-net/aspose.psd/region/) enthält, der nicht mit diesem [Region](/psd/python-net/aspose.psd/region/) überschneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Das [Region](/psd/python-net/aspose.psd/region/) Objekt zur Ergänzung dieses [Region](/psd/python-net/aspose.psd/region/) Objekts. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Erstellt eine exakte Deep‑Copy dieses [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | Die [Region](/psd/python-net/aspose.psd/region/), die diese Methode erstellt. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) so, dass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) überschneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Der [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) zum Ausschließen aus dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) so, dass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur überschneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zum Ausschließen aus dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) so, dass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur überschneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zum Ausschließen aus dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) so, dass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen [Region](/psd/python-net/aspose.psd/region/) überschneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Die [Region](/psd/python-net/aspose.psd/region/) zum Ausschließen aus dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) auf die Schnittmenge mit dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Der [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) zum Schneiden mit dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) auf die Schnittmenge mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zum Schneiden mit dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) auf die Schnittmenge mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zum Schneiden mit dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Aktualisiert dieses [Region](/psd/python-net/aspose.psd/region/) auf die Schnittmenge mit dem angegebenen [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Die [Region](/psd/python-net/aspose.psd/region/) zum Schneiden mit dieser [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Prüft, ob dieses [Region](/psd/python-net/aspose.psd/region/) auf der angegebenen Zeichenfläche ein leeres Inneres hat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das eine Zeichenfläche darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn das Innere dieser [Region](/psd/python-net/aspose.psd/region/) leer ist, wenn die mit <paramref name="g" /> verbundene Transformation angewendet wird; andernfalls false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Prüft, ob dieses [Region](/psd/python-net/aspose.psd/region/) auf der angegebenen Zeichenfläche ein unendliches Inneres hat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das eine Zeichenfläche darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn das Innere dieses [Region](/psd/python-net/aspose.psd/region/) unendlich ist, wenn die mit <paramref name="g" /> verbundene Transformation angewendet wird; andernfalls false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Prüft, ob die angegebene [PointF](/psd/python-net/aspose.psd/pointf/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Die [PointF](/psd/python-net/aspose.psd/pointf/) Struktur zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn <paramref name="point" /> innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Prüft, ob die angegebene [PointF](/psd/python-net/aspose.psd/pointf/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Die [PointF](/psd/python-net/aspose.psd/pointf/) Struktur zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn <paramref name="point" /> innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Prüft, ob die angegebene [PointF](/psd/python-net/aspose.psd/pointf/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn sie mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Die [PointF](/psd/python-net/aspose.psd/pointf/) Struktur zum Testen. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das einen Grafik-Kontext darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn <paramref name="point" /> innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Prüft, ob die angegebene [PointF](/psd/python-net/aspose.psd/pointf/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn sie mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Die [PointF](/psd/python-net/aspose.psd/pointf/) Struktur zum Testen. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das einen Grafik-Kontext darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn <paramref name="point" /> innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Prüft, ob irgendein Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn irgendein Teil von <paramref name="rect" /> innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Prüft, ob irgendein Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn irgendein Teil von <paramref name="rect" /> innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Prüft, ob irgendein Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn sie mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zum Testen. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das einen Grafik-Kontext darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn <paramref name="rect" /> innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Prüft, ob irgendein Teil der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn sie mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zum Testen. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das einen Grafik-Kontext darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn <paramref name="rect" /> innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Prüft, ob der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Prüft, ob der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn er mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das einen Grafik-Kontext darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Prüft, ob der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn er mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das einen Grafik-Kontext darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn der angegebene Punkt innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| width | float | Die Breite des zu testenden Rechtecks. |
| height | float | Die Höhe des zu testenden Rechtecks. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) Objekts enthalten ist; andernfalls false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| width | int | Die Breite des zu testenden Rechtecks. |
| height | int | Die Höhe des zu testenden Rechtecks. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) Objekts enthalten ist; andernfalls false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn er mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| width | float | Die Breite des zu testenden Rechtecks. |
| height | float | Die Höhe des zu testenden Rechtecks. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das einen Grafik-Kontext darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Prüft, ob irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) liegt, wenn er mit dem angegebenen [Graphics](/psd/python-net/aspose.psd/graphics/) gezeichnet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| width | int | Die Breite des zu testenden Rechtecks. |
| height | int | Die Höhe des zu testenden Rechtecks. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Ein [Graphics](/psd/python-net/aspose.psd/graphics/), das einen Grafik-Kontext darstellt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses [Region](/psd/python-net/aspose.psd/region/) enthalten ist; andernfalls false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Transformiert diese [Region](/psd/python-net/aspose.psd/region/) mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die [Matrix](/psd/python-net/aspose.psd/matrix/), mit der dieses [Region](/psd/python-net/aspose.psd/region/) transformiert wird. |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Verschiebt die Koordinaten dieser [Region](/psd/python-net/aspose.psd/region/) um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Betrag, um den dieses [Region](/psd/python-net/aspose.psd/region/) horizontal verschoben wird. |
| dy | float | Der Betrag, um den dieses [Region](/psd/python-net/aspose.psd/region/) vertikal verschoben wird. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Verschiebt die Koordinaten dieser [Region](/psd/python-net/aspose.psd/region/) um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | int | Der Betrag, um den dieses [Region](/psd/python-net/aspose.psd/region/) horizontal verschoben wird. |
| dy | int | Der Betrag, um den dieses [Region](/psd/python-net/aspose.psd/region/) vertikal verschoben wird. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung von sich selbst und dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Der [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), der mit diesem [Region](/psd/python-net/aspose.psd/region/) vereinigt wird. |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung von sich selbst und der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die mit diesem [Region](/psd/python-net/aspose.psd/region/) vereinigt wird. |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung von sich selbst und der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die mit diesem [Region](/psd/python-net/aspose.psd/region/) vereinigt wird. |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung von sich selbst und der angegebenen [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Das [Region](/psd/python-net/aspose.psd/region/), das mit diesem [Region](/psd/python-net/aspose.psd/region/) vereinigt wird. |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung minus der Schnittmenge von sich selbst mit dem angegebenen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Der [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), der mit diesem [Region](/psd/python-net/aspose.psd/region/) XOR-verknüpft wird. |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung minus der Schnittmenge von sich selbst mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die mit diesem [Region](/psd/python-net/aspose.psd/region/) XOR-verknüpft wird. |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung minus der Schnittmenge von sich selbst mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die mit diesem [Region](/psd/python-net/aspose.psd/region/) XOR-verknüpft wird. |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Aktualisiert diese [Region](/psd/python-net/aspose.psd/region/) zur Vereinigung minus der Schnittmenge von sich selbst mit der angegebenen [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Das [Region](/psd/python-net/aspose.psd/region/), das mit diesem [Region](/psd/python-net/aspose.psd/region/) XOR-verknüpft wird. |

