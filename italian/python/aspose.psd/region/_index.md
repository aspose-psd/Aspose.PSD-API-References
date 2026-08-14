---
title: "Classe Region"
type: docs
weight: 3870
url: /it/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Region()](#Region__1) | Inizializza un nuovo [Region](/psd/python-net/aspose.psd/region/). |
| [Region(path)](#Region_path_2) | Inizializza un nuovo [Region](/psd/python-net/aspose.psd/region/) con il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato. |
| [Region(rect)](#Region_rect_3) | Inizializza un nuovo [Region](/psd/python-net/aspose.psd/region/) dalla struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [Region(rect)](#Region_rect_4) | Inizializza un nuovo [Region](/psd/python-net/aspose.psd/region/) dalla struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [complement(path)](#complement_path_1) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere la porzione del [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato che non interseca questo [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_2) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere la porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato che non interseca questo [Region](/psd/python-net/aspose.psd/region/). |
| [complement(rect)](#complement_rect_3) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere la porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato che non interseca questo [Region](/psd/python-net/aspose.psd/region/). |
| [complement(region)](#complement_region_4) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere la porzione del [Region](/psd/python-net/aspose.psd/region/) specificato che non interseca questo [Region](/psd/python-net/aspose.psd/region/). |
| [deep_clone()](#deep_clone__5) | Crea una copia profonda esatta di questo [Region](/psd/python-net/aspose.psd/region/). |
| [exclude(path)](#exclude_path_6) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere solo la porzione del suo interno che non interseca il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato. |
| [exclude(rect)](#exclude_rect_7) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [exclude(rect)](#exclude_rect_8) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [exclude(region)](#exclude_region_9) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere solo la porzione del suo interno che non interseca il [Region](/psd/python-net/aspose.psd/region/) specificato. |
| [intersect(path)](#intersect_path_10) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) all'intersezione di sé stesso con il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato. |
| [intersect(rect)](#intersect_rect_11) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) all'intersezione di sé stesso con la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [intersect(rect)](#intersect_rect_12) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) all'intersezione di sé stesso con la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [intersect(region)](#intersect_region_13) | Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) all'intersezione di sé stesso con il [Region](/psd/python-net/aspose.psd/region/) specificato. |
| [is_empty(g)](#is_empty_g_14) | Verifica se questo [Region](/psd/python-net/aspose.psd/region/) ha un interno vuoto sulla superficie di disegno specificata. |
| [is_infinite(g)](#is_infinite_g_15) | Verifica se questo [Region](/psd/python-net/aspose.psd/region/) ha un interno infinito sulla superficie di disegno specificata. |
| [is_visible(point)](#is_visible_point_16) | Verifica se la struttura [PointF](/psd/python-net/aspose.psd/pointf/) specificata è contenuta in questo [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point)](#is_visible_point_17) | Verifica se la struttura [PointF](/psd/python-net/aspose.psd/pointf/) specificata è contenuta in questo [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(point, g)](#is_visible_point_g_18) | Verifica se la struttura [PointF](/psd/python-net/aspose.psd/pointf/) specificata è contenuta in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato. |
| [is_visible(point, g)](#is_visible_point_g_19) | Verifica se la struttura [PointF](/psd/python-net/aspose.psd/pointf/) specificata è contenuta in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato. |
| [is_visible(rect)](#is_visible_rect_20) | Verifica se qualche porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato è contenuta in questo [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect)](#is_visible_rect_21) | Verifica se qualche porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato è contenuta in questo [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Verifica se qualche porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato è contenuta in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato. |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Verifica se qualche porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato è contenuta in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato. |
| [is_visible(x, y)](#is_visible_x_y_24) | Verifica se il punto specificato è contenuto in questo [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Verifica se il punto specificato è contenuto in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnato usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato. |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Verifica se il punto specificato è contenuto in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnato usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](/psd/python-net/aspose.psd/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata. |
| make_empty() | Inizializza questa [Region](/psd/python-net/aspose.psd/region/) con un interno vuoto. |
| make_infinite() | Inizializza questo oggetto [Region](/psd/python-net/aspose.psd/region/) con un interno infinito. |
| [transform(matrix)](#transform_matrix_31) | Trasforma questa [Region](/psd/python-net/aspose.psd/region/) mediante la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata. |
| [translate(dx, dy)](#translate_dx_dy_32) | Sposta le coordinate di questa [Region](/psd/python-net/aspose.psd/region/) dell'importo specificato. |
| [translate(dx, dy)](#translate_dx_dy_33) | Sposta le coordinate di questa [Region](/psd/python-net/aspose.psd/region/) dell'importo specificato. |
| [union(path)](#union_path_34) | Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione di sé stessa e della [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificata. |
| [union(rect)](#union_rect_35) | Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione di sé stessa e della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [union(rect)](#union_rect_36) | Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione di sé stessa e della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [union(region)](#union_region_37) | Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione di sé stessa e della [Region](/psd/python-net/aspose.psd/region/) specificata. |
| [xor(path)](#xor_path_38) | Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione meno l'intersezione di sé stessa con la [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificata. |
| [xor(rect)](#xor_rect_39) | Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione meno l'intersezione di sé stessa con la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [xor(rect)](#xor_rect_40) | Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione meno l'intersezione di sé stessa con la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [xor(region)](#xor_region_41) | Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione meno l'intersezione di sé stessa con la [Region](/psd/python-net/aspose.psd/region/) specificata. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Inizializza un nuovo [Region](/psd/python-net/aspose.psd/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Inizializza un nuovo [Region](/psd/python-net/aspose.psd/region/) con il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Una [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce la nuova [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Inizializza un nuovo [Region](/psd/python-net/aspose.psd/region/) dalla struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che definisce l'interno della nuova [Region](/psd/python-net/aspose.psd/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Inizializza un nuovo [Region](/psd/python-net/aspose.psd/region/) dalla struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che definisce l'interno della nuova [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere la porzione del [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato che non interseca questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | La [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) per completare questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere la porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato che non interseca questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) per completare questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere la porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato che non interseca questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) per completare questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere la porzione del [Region](/psd/python-net/aspose.psd/region/) specificato che non interseca questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | L'oggetto [Region](/psd/python-net/aspose.psd/region/) per completare questo oggetto [Region](/psd/python-net/aspose.psd/region/). |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Crea una copia profonda esatta di questo [Region](/psd/python-net/aspose.psd/region/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) che questo metodo crea. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere solo la porzione del suo interno che non interseca il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | La [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) da escludere da questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da escludere da questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da escludere da questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) per contenere solo la porzione del suo interno che non interseca il [Region](/psd/python-net/aspose.psd/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) da escludere da questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) all'intersezione di sé stesso con il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | La [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) da intersecare con questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) all'intersezione di sé stesso con la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da intersecare con questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) all'intersezione di sé stesso con la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da intersecare con questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Aggiorna questo [Region](/psd/python-net/aspose.psd/region/) all'intersezione di sé stesso con il [Region](/psd/python-net/aspose.psd/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | La [Region](/psd/python-net/aspose.psd/region/) da intersecare con questa [Region](/psd/python-net/aspose.psd/region/). |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Verifica se questo [Region](/psd/python-net/aspose.psd/region/) ha un interno vuoto sulla superficie di disegno specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Una [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta una superficie di disegno. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero se l'interno di questo [Region](/psd/python-net/aspose.psd/region/) è vuoto quando viene applicata la trasformazione associata a <paramref name="g" />; altrimenti, falso. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Verifica se questo [Region](/psd/python-net/aspose.psd/region/) ha un interno infinito sulla superficie di disegno specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Una [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta una superficie di disegno. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero se l'interno di questo [Region](/psd/python-net/aspose.psd/region/) è infinito quando viene applicata la trasformazione associata a <paramref name="g" />; altrimenti, falso. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Verifica se la struttura [PointF](/psd/python-net/aspose.psd/pointf/) specificata è contenuta in questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | La struttura [PointF](/psd/python-net/aspose.psd/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando <paramref name="point" /> è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Verifica se la struttura [PointF](/psd/python-net/aspose.psd/pointf/) specificata è contenuta in questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | La struttura [PointF](/psd/python-net/aspose.psd/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando <paramref name="point" /> è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Verifica se la struttura [PointF](/psd/python-net/aspose.psd/pointf/) specificata è contenuta in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | La struttura [PointF](/psd/python-net/aspose.psd/pointf/) da testare. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando <paramref name="point" /> è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Verifica se la struttura [PointF](/psd/python-net/aspose.psd/pointf/) specificata è contenuta in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | La struttura [PointF](/psd/python-net/aspose.psd/pointf/) da testare. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando <paramref name="point" /> è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Verifica se qualche porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato è contenuta in questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte di <paramref name="rect" /> è contenuta all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Verifica se qualche porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato è contenuta in questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte di <paramref name="rect" /> è contenuta all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Verifica se qualche porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato è contenuta in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da testare. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando <paramref name="rect" /> è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Verifica se qualche porzione del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato è contenuta in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da testare. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando <paramref name="rect" /> è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Verifica se il punto specificato è contenuto in questo [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Verifica se il punto specificato è contenuto in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnato usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Verifica se il punto specificato è contenuto in questo [Region](/psd/python-net/aspose.psd/region/) quando viene disegnato usando il [Graphics](/psd/python-net/aspose.psd/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| altezza | float | L'altezza del rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo oggetto [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| altezza | int | L'altezza del rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo oggetto [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| altezza | float | L'altezza del rettangolo da testare. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questa [Region](/psd/python-net/aspose.psd/region/) quando viene disegnata usando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| altezza | int | L'altezza del rettangolo da testare. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Un [Graphics](/psd/python-net/aspose.psd/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta all'interno di questo [Region](/psd/python-net/aspose.psd/region/); altrimenti, falso. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Trasforma questa [Region](/psd/python-net/aspose.psd/region/) mediante la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) con cui trasformare questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Sposta le coordinate di questa [Region](/psd/python-net/aspose.psd/region/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | La quantità di spostamento orizzontale di questo [Region](/psd/python-net/aspose.psd/region/). |
| dy | float | La quantità di spostamento verticale di questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Sposta le coordinate di questa [Region](/psd/python-net/aspose.psd/region/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | int | La quantità di spostamento orizzontale di questo [Region](/psd/python-net/aspose.psd/region/). |
| dy | int | La quantità di spostamento verticale di questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione di sé stessa e della [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) da unire a questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione di sé stessa e della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da unire a questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione di sé stessa e della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da unire a questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione di sé stessa e della [Region](/psd/python-net/aspose.psd/region/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Il [Region](/psd/python-net/aspose.psd/region/) da unire a questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione meno l'intersezione di sé stessa con la [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) da xor con questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione meno l'intersezione di sé stessa con la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da xor con questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione meno l'intersezione di sé stessa con la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da xor con questo [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Aggiorna questa [Region](/psd/python-net/aspose.psd/region/) all'unione meno l'intersezione di sé stessa con la [Region](/psd/python-net/aspose.psd/region/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Il [Region](/psd/python-net/aspose.psd/region/) da xor con questo [Region](/psd/python-net/aspose.psd/region/). |

