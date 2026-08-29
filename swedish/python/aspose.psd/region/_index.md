---
title: "Region-klass"
type: docs
weight: 3870
url: /sv/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Region()](#Region__1) | Initierar en ny [Region](/psd/python-net/aspose.psd/region/). |
| [Region(path)](#Region_path_2) | Initierar en ny [Region](/psd/python-net/aspose.psd/region/) med den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [Region(rect)](#Region_rect_3) | Initierar en ny [Region](/psd/python-net/aspose.psd/region/) från den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen. |
| [Region(rect)](#Region_rect_4) | Initierar en ny [Region](/psd/python-net/aspose.psd/region/) från den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [complement(path)](#complement_path_1) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det innehåller den del av den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) som inte skär sig med detta [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_2) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det innehåller den del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen som inte skär sig med detta [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_3) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det innehåller den del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen som inte skär sig med detta [Region](/psd/python-net/aspose.psd/region/). |
| [complement(region)](#complement_region_4) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det innehåller den del av den angivna [Region](/psd/python-net/aspose.psd/region/) som inte skär sig med detta [Region](/psd/python-net/aspose.psd/region/). |
| [deep_clone()](#deep_clone__5) | Skapar en exakt djupkopiering av detta [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det endast innehåller den del av dess inre som inte skär sig med den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [exclude(rect)](#exclude_rect_7) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det endast innehåller den del av dess inre som inte skär sig med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen. |
| [exclude(rect)](#exclude_rect_8) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det endast innehåller den del av dess inre som inte skär sig med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen. |
| [exclude(region)](#exclude_region_9) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det endast innehåller den del av dess inre som inte skär sig med den angivna [Region](/psd/python-net/aspose.psd/region/). |
| [intersect(path)](#intersect_path_10) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till skärningen av sig själv med den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [intersect(rect)](#intersect_rect_11) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till skärningen av sig själv med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen. |
| [intersect(rect)](#intersect_rect_12) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till skärningen av sig själv med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen. |
| [intersect(region)](#intersect_region_13) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till skärningen av sig själv med den angivna [Region](/psd/python-net/aspose.psd/region/). |
| [is_empty(g)](#is_empty_g_14) | Testar om detta [Region](/psd/python-net/aspose.psd/region/) har ett tomt inre på den angivna ritytan. |
| [is_infinite(g)](#is_infinite_g_15) | Testar om detta [Region](/psd/python-net/aspose.psd/region/) har ett oändligt inre på den angivna ritytan. |
| [is_visible(point)](#is_visible_point_16) | Testar om den angivna [PointF](/psd/python-net/aspose.psd/pointf/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point)](#is_visible_point_17) | Testar om den angivna [PointF](/psd/python-net/aspose.psd/pointf/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point, g)](#is_visible_point_g_18) | Testar om den angivna [PointF](/psd/python-net/aspose.psd/pointf/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point, g)](#is_visible_point_g_19) | Testar om den angivna [PointF](/psd/python-net/aspose.psd/pointf/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect)](#is_visible_rect_20) | Testar om någon del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect)](#is_visible_rect_21) | Testar om någon del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Testar om någon del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Testar om någon del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y)](#is_visible_x_y_24) | Testar om den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Testar om den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Testar om den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Testar om någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Testar om någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Testar om någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Testar om någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/). |
| make_empty() | Initierar detta [Region](/psd/python-net/aspose.psd/region/) till ett tomt inre. |
| make_infinite() | Initierar detta [Region](/psd/python-net/aspose.psd/region/)-objekt till ett oändligt inre. |
| [transform(matrix)](#transform_matrix_31) | Transformerar detta [Region](/psd/python-net/aspose.psd/region/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [translate(dx, dy)](#translate_dx_dy_32) | Förskjuter koordinaterna för detta [Region](/psd/python-net/aspose.psd/region/) med det angivna värdet. |
| [translate(dx, dy)](#translate_dx_dy_33) | Förskjuter koordinaterna för detta [Region](/psd/python-net/aspose.psd/region/) med det angivna värdet. |
| [union(path)](#union_path_34) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen av sig själv och den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [union(rect)](#union_rect_35) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen av sig själv och den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen. |
| [union(rect)](#union_rect_36) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen av sig själv och den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen. |
| [union(region)](#union_region_37) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen av sig själv och den angivna [Region](/psd/python-net/aspose.psd/region/). |
| [xor(path)](#xor_path_38) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen minus skärningen av sig själv med den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [xor(rect)](#xor_rect_39) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen minus skärningen av sig själv med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen. |
| [xor(rect)](#xor_rect_40) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen minus skärningen av sig själv med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen. |
| [xor(region)](#xor_region_41) | Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen minus skärningen av sig själv med den angivna [Region](/psd/python-net/aspose.psd/region/). |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Initierar en ny [Region](/psd/python-net/aspose.psd/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Initierar en ny [Region](/psd/python-net/aspose.psd/region/) med den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | En [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) som definierar den nya [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Initierar en ny [Region](/psd/python-net/aspose.psd/region/) från den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som definierar det inre av den nya [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Initierar en ny [Region](/psd/python-net/aspose.psd/region/) från den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som definierar det inre av den nya [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det innehåller den del av den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) som inte skär sig med detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) för att komplettera detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det innehåller den del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen som inte skär sig med detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att komplettera detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det innehåller den del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen som inte skär sig med detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att komplettera detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det innehåller den del av den angivna [Region](/psd/python-net/aspose.psd/region/) som inte skär sig med detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Det [Region](/psd/python-net/aspose.psd/region/)-objektet för att komplettera detta [Region](/psd/python-net/aspose.psd/region/)-objekt. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Skapar en exakt djupkopiering av detta [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | Den [Region](/psd/python-net/aspose.psd/region/) som denna metod skapar. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det endast innehåller den del av dess inre som inte skär sig med den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) att utesluta från detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det endast innehåller den del av dess inre som inte skär sig med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att utesluta från detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det endast innehåller den del av dess inre som inte skär sig med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att utesluta från detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) så att det endast innehåller den del av dess inre som inte skär sig med den angivna [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Den [Region](/psd/python-net/aspose.psd/region/) för att utesluta från detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till skärningen av sig själv med den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) för att intersektera med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till skärningen av sig själv med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att intersektera med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till skärningen av sig själv med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att intersektera med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till skärningen av sig själv med den angivna [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Den [Region](/psd/python-net/aspose.psd/region/) för att intersektera med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Testar om detta [Region](/psd/python-net/aspose.psd/region/) har ett tomt inre på den angivna ritytan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en ritningsyta. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true om innanmätet av detta [Region](/psd/python-net/aspose.psd/region/) är tomt när transformationen som är associerad med <paramref name="g" /> tillämpas; annars false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Testar om detta [Region](/psd/python-net/aspose.psd/region/) har ett oändligt inre på den angivna ritytan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en ritningsyta. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true om innanmätet av detta [Region](/psd/python-net/aspose.psd/region/) är oändligt när transformationen som är associerad med <paramref name="g" /> tillämpas; annars false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Testar om den angivna [PointF](/psd/python-net/aspose.psd/pointf/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Den [PointF](/psd/python-net/aspose.psd/pointf/) strukturen för att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när <paramref name="point" /> finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Testar om den angivna [PointF](/psd/python-net/aspose.psd/pointf/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Den [PointF](/psd/python-net/aspose.psd/pointf/) strukturen för att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när <paramref name="point" /> finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Testar om den angivna [PointF](/psd/python-net/aspose.psd/pointf/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Den [PointF](/psd/python-net/aspose.psd/pointf/) strukturen för att testa. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en grafikkontext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när <paramref name="point" /> finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Testar om den angivna [PointF](/psd/python-net/aspose.psd/pointf/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Den [PointF](/psd/python-net/aspose.psd/pointf/) strukturen för att testa. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en grafikkontext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när <paramref name="point" /> finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Testar om någon del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när någon del av <paramref name="rect" /> finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Testar om någon del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när någon del av <paramref name="rect" /> finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Testar om någon del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att testa. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en grafikkontext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när <paramref name="rect" /> finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Testar om någon del av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att testa. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en grafikkontext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när <paramref name="rect" /> finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Testar om den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant när den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Testar om den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en grafikkontext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant när den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Testar om den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en grafikkontext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant när den angivna punkten finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Testar om någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| width | float | Bredden på rektangeln som ska testas. |
| height | float | Höjden på rektangeln som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/) objekt; annars false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Testar om någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| width | int | Bredden på rektangeln som ska testas. |
| height | int | Höjden på rektangeln som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/) objekt; annars false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Testar om någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| width | float | Bredden på rektangeln som ska testas. |
| height | float | Höjden på rektangeln som ska testas. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en grafikkontext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Testar om någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/) när den ritas med den angivna [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska testas. |
| width | int | Bredden på rektangeln som ska testas. |
| height | int | Höjden på rektangeln som ska testas. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | En [Graphics](/psd/python-net/aspose.psd/graphics/) som representerar en grafikkontext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true när någon del av den angivna rektangeln finns inom detta [Region](/psd/python-net/aspose.psd/region/); annars false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Transformerar detta [Region](/psd/python-net/aspose.psd/region/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Den [Matrix](/psd/python-net/aspose.psd/matrix/) som ska användas för att transformera detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Förskjuter koordinaterna för detta [Region](/psd/python-net/aspose.psd/region/) med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Mängden för att förskjuta detta [Region](/psd/python-net/aspose.psd/region/) horisontellt. |
| dy | float | Mängden för att förskjuta detta [Region](/psd/python-net/aspose.psd/region/) vertikalt. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Förskjuter koordinaterna för detta [Region](/psd/python-net/aspose.psd/region/) med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | int | Mängden för att förskjuta detta [Region](/psd/python-net/aspose.psd/region/) horisontellt. |
| dy | int | Mängden för att förskjuta detta [Region](/psd/python-net/aspose.psd/region/) vertikalt. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen av sig själv och den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) för att förena med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen av sig själv och den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att förena med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen av sig själv och den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen för att förena med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen av sig själv och den angivna [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Den [Region](/psd/python-net/aspose.psd/region/) för att förena med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen minus skärningen av sig själv med den angivna [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) för att xor:a med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen minus skärningen av sig själv med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) för att xor:a med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen minus skärningen av sig själv med den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) för att xor:a med detta [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Uppdaterar detta [Region](/psd/python-net/aspose.psd/region/) till unionen minus skärningen av sig själv med den angivna [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Den [Region](/psd/python-net/aspose.psd/region/) för att xor:a med detta [Region](/psd/python-net/aspose.psd/region/). |

