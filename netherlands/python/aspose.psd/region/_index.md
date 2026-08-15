---
title: "Region-klasse"
type: docs
weight: 3870
url: /nl/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Region()](#Region__1) | Initialiseert een nieuwe [Region](/psd/python-net/aspose.psd/region/). |
| [Region(path)](#Region_path_2) | Initialiseert een nieuwe [Region](/psd/python-net/aspose.psd/region/) met het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [Region(rect)](#Region_rect_3) | Initialiseert een nieuwe [Region](/psd/python-net/aspose.psd/region/) vanuit de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-structuur. |
| [Region(rect)](#Region_rect_4) | Initialiseert een nieuwe [Region](/psd/python-net/aspose.psd/region/) vanuit de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-structuur. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [complement(path)](#complement_path_1) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het het gedeelte van het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevat dat niet intersecteert met dit [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_2) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het het gedeelte van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur bevat dat niet intersecteert met dit [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_3) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het het gedeelte van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur bevat dat niet intersecteert met dit [Region](/psd/python-net/aspose.psd/region/). |
| [complement(region)](#complement_region_4) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het het gedeelte van het opgegeven [Region](/psd/python-net/aspose.psd/region/) bevat dat niet intersecteert met dit [Region](/psd/python-net/aspose.psd/region/). |
| [deep_clone()](#deep_clone__5) | Maakt een exacte diepe kopie van dit [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het alleen het gedeelte van zijn binnenkant bevat dat niet intersecteert met het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [exclude(rect)](#exclude_rect_7) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het alleen het gedeelte van zijn binnenkant bevat dat niet intersecteert met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [exclude(rect)](#exclude_rect_8) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het alleen het gedeelte van zijn binnenkant bevat dat niet intersecteert met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [exclude(region)](#exclude_region_9) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het alleen het gedeelte van zijn binnenkant bevat dat niet intersecteert met het opgegeven [Region](/psd/python-net/aspose.psd/region/). |
| [intersect(path)](#intersect_path_10) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij tot de intersectie van zichzelf met het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [intersect(rect)](#intersect_rect_11) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij tot de intersectie van zichzelf met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [intersect(rect)](#intersect_rect_12) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij tot de intersectie van zichzelf met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [intersect(region)](#intersect_region_13) | Werk dit [Region](/psd/python-net/aspose.psd/region/) bij tot de intersectie van zichzelf met het opgegeven [Region](/psd/python-net/aspose.psd/region/). |
| [is_empty(g)](#is_empty_g_14) | Test of dit [Region](/psd/python-net/aspose.psd/region/) een lege binnenkant heeft op het opgegeven tekenoppervlak. |
| [is_infinite(g)](#is_infinite_g_15) | Test of dit [Region](/psd/python-net/aspose.psd/region/) een oneindige binnenkant heeft op het opgegeven tekenoppervlak. |
| [is_visible(point)](#is_visible_point_16) | Test of de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point)](#is_visible_point_17) | Test of de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point, g)](#is_visible_point_g_18) | Test of de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point, g)](#is_visible_point_g_19) | Test of de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect)](#is_visible_rect_20) | Test of een deel van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect)](#is_visible_rect_21) | Test of een deel van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Test of een deel van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Test of een deel van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y)](#is_visible_x_y_24) | Test of het opgegeven punt zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Test of het opgegeven punt zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Test of het opgegeven punt zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Test of een deel van de opgegeven rechthoek zich bevindt binnen deze [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Test of een deel van de opgegeven rechthoek zich bevindt binnen deze [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Test of een deel van de opgegeven rechthoek zich bevindt binnen deze [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Test of een deel van de opgegeven rechthoek zich bevindt binnen deze [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/). |
| make_empty() | Initialiseert deze [Region](/psd/python-net/aspose.psd/region/) tot een lege binnenkant. |
| make_infinite() | Initialiseert dit [Region](/psd/python-net/aspose.psd/region/) object tot een oneindige binnenkant. |
| [transform(matrix)](#transform_matrix_31) | Transformeert deze [Region](/psd/python-net/aspose.psd/region/) met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [translate(dx, dy)](#translate_dx_dy_32) | Verschuift de coördinaten van deze [Region](/psd/python-net/aspose.psd/region/) met de opgegeven hoeveelheid. |
| [translate(dx, dy)](#translate_dx_dy_33) | Verschuift de coördinaten van deze [Region](/psd/python-net/aspose.psd/region/) met de opgegeven hoeveelheid. |
| [union(path)](#union_path_34) | Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie van zichzelf en de opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [union(rect)](#union_rect_35) | Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie van zichzelf en de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [union(rect)](#union_rect_36) | Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie van zichzelf en de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [union(region)](#union_region_37) | Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie van zichzelf en de opgegeven [Region](/psd/python-net/aspose.psd/region/). |
| [xor(path)](#xor_path_38) | Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie min de intersectie van zichzelf met de opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [xor(rect)](#xor_rect_39) | Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie min de intersectie van zichzelf met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [xor(rect)](#xor_rect_40) | Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie min de intersectie van zichzelf met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [xor(region)](#xor_region_41) | Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie min de intersectie van zichzelf met de opgegeven [Region](/psd/python-net/aspose.psd/region/). |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Initialiseert een nieuwe [Region](/psd/python-net/aspose.psd/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Initialiseert een nieuwe [Region](/psd/python-net/aspose.psd/region/) met het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Een [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) die de nieuwe [Region](/psd/python-net/aspose.psd/region/) definieert. |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Initialiseert een nieuwe [Region](/psd/python-net/aspose.psd/region/) vanuit de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de binnenkant van de nieuwe [Region](/psd/python-net/aspose.psd/region/) definieert. |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Initialiseert een nieuwe [Region](/psd/python-net/aspose.psd/region/) vanuit de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de binnenkant van de nieuwe [Region](/psd/python-net/aspose.psd/region/) definieert. |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het het gedeelte van het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) bevat dat niet intersecteert met dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | De [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om deze [Region](/psd/python-net/aspose.psd/region/) aan te vullen. |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het het gedeelte van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur bevat dat niet intersecteert met dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om deze [Region](/psd/python-net/aspose.psd/region/) aan te vullen. |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het het gedeelte van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur bevat dat niet intersecteert met dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om deze [Region](/psd/python-net/aspose.psd/region/) aan te vullen. |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het het gedeelte van het opgegeven [Region](/psd/python-net/aspose.psd/region/) bevat dat niet intersecteert met dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Het [Region](/psd/python-net/aspose.psd/region/) object om dit [Region](/psd/python-net/aspose.psd/region/) object aan te vullen. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Maakt een exacte diepe kopie van dit [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | De [Region](/psd/python-net/aspose.psd/region/) die deze methode maakt. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het alleen het gedeelte van zijn binnenkant bevat dat niet intersecteert met het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | De [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om uit te sluiten van deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het alleen het gedeelte van zijn binnenkant bevat dat niet intersecteert met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om uit te sluiten van deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het alleen het gedeelte van zijn binnenkant bevat dat niet intersecteert met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om uit te sluiten van deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij zodat het alleen het gedeelte van zijn binnenkant bevat dat niet intersecteert met het opgegeven [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | De [Region](/psd/python-net/aspose.psd/region/) om uit te sluiten van deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij tot de intersectie van zichzelf met het opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | De [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om te intersecteren met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij tot de intersectie van zichzelf met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te intersecteren met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij tot de intersectie van zichzelf met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te intersecteren met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Werk dit [Region](/psd/python-net/aspose.psd/region/) bij tot de intersectie van zichzelf met het opgegeven [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | De [Region](/psd/python-net/aspose.psd/region/) om te intersecteren met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Test of dit [Region](/psd/python-net/aspose.psd/region/) een lege binnenkant heeft op het opgegeven tekenoppervlak.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een tekenoppervlak vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true als het binnenste van deze [Region](/psd/python-net/aspose.psd/region/) leeg is wanneer de transformatie die gekoppeld is aan <paramref name="g" /> wordt toegepast; anders false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Test of dit [Region](/psd/python-net/aspose.psd/region/) een oneindige binnenkant heeft op het opgegeven tekenoppervlak.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een tekenoppervlak vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true als het binnenste van deze [Region](/psd/python-net/aspose.psd/region/) oneindig is wanneer de transformatie die gekoppeld is aan <paramref name="g" /> wordt toegepast; anders false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Test of de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | De [PointF](/psd/python-net/aspose.psd/pointf/) structuur om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer <paramref name="point" /> zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Test of de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | De [PointF](/psd/python-net/aspose.psd/pointf/) structuur om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer <paramref name="point" /> zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Test of de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | De [PointF](/psd/python-net/aspose.psd/pointf/) structuur om te testen. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een grafische context vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer <paramref name="point" /> zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Test of de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | De [PointF](/psd/python-net/aspose.psd/pointf/) structuur om te testen. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een grafische context vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer <paramref name="point" /> zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Test of een deel van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer een deel van <paramref name="rect" /> zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Test of een deel van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer een deel van <paramref name="rect" /> zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Test of een deel van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te testen. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een grafische context vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer <paramref name="rect" /> zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Test of een deel van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te testen. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een grafische context vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer <paramref name="rect" /> zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Test of het opgegeven punt zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het te testen punt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True wanneer het opgegeven punt zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Test of het opgegeven punt zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het te testen punt. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een grafische context vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True wanneer het opgegeven punt zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Test of het opgegeven punt zich bevindt binnen dit [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van het te testen punt. |
| y | int | De y-coördinaat van het te testen punt. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een grafische context vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True wanneer het opgegeven punt zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Test of een deel van de opgegeven rechthoek zich bevindt binnen deze [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| width | float | De breedte van de te testen rechthoek. |
| hoogte | float | De hoogte van de te testen rechthoek. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer een deel van de opgegeven rechthoek zich binnen dit [Region](/psd/python-net/aspose.psd/region/) object bevindt; anders false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Test of een deel van de opgegeven rechthoek zich bevindt binnen deze [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| width | int | De breedte van de te testen rechthoek. |
| hoogte | int | De hoogte van de te testen rechthoek. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer een deel van de opgegeven rechthoek zich binnen dit [Region](/psd/python-net/aspose.psd/region/) object bevindt; anders false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Test of een deel van de opgegeven rechthoek zich bevindt binnen deze [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| width | float | De breedte van de te testen rechthoek. |
| hoogte | float | De hoogte van de te testen rechthoek. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een grafische context vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer een deel van de opgegeven rechthoek zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Test of een deel van de opgegeven rechthoek zich bevindt binnen deze [Region](/psd/python-net/aspose.psd/region/) wanneer getekend met de opgegeven [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te testen rechthoek. |
| width | int | De breedte van de te testen rechthoek. |
| hoogte | int | De hoogte van de te testen rechthoek. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Een [Graphics](/psd/python-net/aspose.psd/graphics/) die een grafische context vertegenwoordigt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true wanneer een deel van de opgegeven rechthoek zich binnen deze [Region](/psd/python-net/aspose.psd/region/) bevindt; anders false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Transformeert deze [Region](/psd/python-net/aspose.psd/region/) met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee deze [Region](/psd/python-net/aspose.psd/region/) getransformeerd wordt. |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Verschuift de coördinaten van deze [Region](/psd/python-net/aspose.psd/region/) met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De hoeveelheid om deze [Region](/psd/python-net/aspose.psd/region/) horizontaal te verschuiven. |
| dy | float | De hoeveelheid om deze [Region](/psd/python-net/aspose.psd/region/) verticaal te verschuiven. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Verschuift de coördinaten van deze [Region](/psd/python-net/aspose.psd/region/) met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | int | De hoeveelheid om deze [Region](/psd/python-net/aspose.psd/region/) horizontaal te verschuiven. |
| dy | int | De hoeveelheid om deze [Region](/psd/python-net/aspose.psd/region/) verticaal te verschuiven. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie van zichzelf en de opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Het [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om te combineren met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie van zichzelf en de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te combineren met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie van zichzelf en de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te combineren met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie van zichzelf en de opgegeven [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | De [Region](/psd/python-net/aspose.psd/region/) om te combineren met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie min de intersectie van zichzelf met de opgegeven [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Het [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om te xor-en met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie min de intersectie van zichzelf met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te xor-en met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie min de intersectie van zichzelf met de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur om te xor-en met deze [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Werkt deze [Region](/psd/python-net/aspose.psd/region/) bij naar de unie min de intersectie van zichzelf met de opgegeven [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | De [Region](/psd/python-net/aspose.psd/region/) om te xor-en met deze [Region](/psd/python-net/aspose.psd/region/). |

