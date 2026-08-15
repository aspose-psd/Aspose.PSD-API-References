---
title: "LinearGradientBrush Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse met standaardparameters.<br/>            De startkleur is zwart, de eindkleur is wit, de hoek is 45 graden en de rechthoek bevindt zich op (0,0) met grootte (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse met de opgegeven punten en kleuren. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse met de opgegeven punten en kleuren. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| hoek | float | r/w | Haalt op of stelt de gradiënthoek in. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Haalt of stelt een [Blend](/psd/python-net/aspose.psd/blend/) in die posities en factoren specificeert die een aangepaste afname voor de gradiënt definiëren. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt of stelt de eindkleur van de gradiënt in. |
| gamma_correction | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of gamma-correctie is ingeschakeld voor deze [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Haalt op of stelt een [ColorBlend](/psd/python-net/aspose.psd/colorblend/) in die een meerkleurige lineaire gradiënt definieert. |
| is_angle_scalable | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) wordt gewijzigd tijdens transformaties met deze [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Haalt een waarde op die aangeeft of transformaties op een of andere manier zijn gewijzigd. Bijvoorbeeld het instellen van de transformatie‑matrix of<br/>            het aanroepen van een van de methoden die de transformatie‑matrix wijzigen. De eigenschap is geïntroduceerd voor achterwaartse compatibiliteit met GDI+. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Haalt of stelt de start- en eindkleuren van de gradiënt in. |
| opacity | float | r/w | Haalt op of stelt de dekking van de penseel in. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Haalt op of stelt een rechthoekig gebied in dat de start- en eindpunten van de gradiënt definieert. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt of stelt de startkleur van de gradiënt in. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Haalt op of stelt een kopie van de [Matrix](/psd/python-net/aspose.psd/matrix/) in die een lokale geometrische transformatie definieert voor deze [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Haalt op of stelt een [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeratie in die de wrap-modus aangeeft voor deze [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Maakt een nieuwe diepe kloon van de huidige [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) weergeeft met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) door de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) voor te voegen. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) weergeeft met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) in de opgegeven volgorde. |
| reset_transform() | Stelt de [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) eigenschap in op de identiteit. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode plaatst de rotatie vóór de transformatie. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Schaalt de lokale geometrische transformatie met de opgegeven waarden. Deze methode plaatst de schaalmatrix vóór de transformatie. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Schaalt de lokale geometrische transformatie met de opgegeven waarden in de opgegeven volgorde. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Creëert een lineaire gradiënt met een middenkleur en een lineaire afname naar één kleur aan beide uiteinden. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Creëert een lineaire gradiënt met een middenkleur en een lineaire afname naar één kleur aan beide uiteinden. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Creëert een gradiëntafname gebaseerd op een klokvormige curve. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Creëert een gradiëntafname gebaseerd op een klokvormige curve. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse met standaardparameters.<br/>            De startkleur is zwart, de eindkleur is wit, de hoek is 45 graden en de rechthoek bevindt zich op (0,0) met grootte (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse met de opgegeven punten en kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Een [Point](/psd/python-net/aspose.psd/point/) structuur die het startpunt van de lineaire gradiënt vertegenwoordigt. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Een [Point](/psd/python-net/aspose.psd/point/) structuur die het eindpunt van de lineaire gradiënt vertegenwoordigt. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de startkleur van de lineaire gradiënt vertegenwoordigt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de eindkleur van de lineaire gradiënt vertegenwoordigt. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse met de opgegeven punten en kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Een [Point](/psd/python-net/aspose.psd/point/) structuur die het startpunt van de lineaire gradiënt vertegenwoordigt. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Een [Point](/psd/python-net/aspose.psd/point/) structuur die het eindpunt van de lineaire gradiënt vertegenwoordigt. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de startkleur van de lineaire gradiënt vertegenwoordigt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de eindkleur van de lineaire gradiënt vertegenwoordigt. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de grenzen van de lineaire gradiënt specificeert. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de startkleur voor de gradiënt vertegenwoordigt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de eindkleur voor de gradient weergeeft. |
| hoek | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de grenzen van de lineaire gradiënt specificeert. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de startkleur voor de gradiënt vertegenwoordigt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de eindkleur voor de gradient weergeeft. |
| hoek | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de grenzen van de lineaire gradiënt specificeert. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de startkleur voor de gradiënt vertegenwoordigt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de eindkleur voor de gradient weergeeft. |
| hoek | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |
| is_angle_scalable | bool | indien ingesteld op <c>true</c> wordt de hoek gewijzigd tijdens transformaties met deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialiseert een nieuw exemplaar van de [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de grenzen van de lineaire gradiënt specificeert. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de startkleur voor de gradiënt vertegenwoordigt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Een [Color](/psd/python-net/aspose.psd/color/) structuur die de eindkleur voor de gradient weergeeft. |
| hoek | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |
| is_angle_scalable | bool | indien ingesteld op <c>true</c> wordt de hoek gewijzigd tijdens transformaties met deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Maakt een nieuwe diepe kloon van de huidige [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Een nieuwe [Brush](/psd/python-net/aspose.psd/brush/) die de diepe kloon is van deze [Brush](/psd/python-net/aspose.psd/brush/) instantie. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) weergeeft met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) door de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) voor te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee de geometrische transformatie moet worden vermenigvuldigd. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) weergeeft met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee de geometrische transformatie moet worden vermenigvuldigd. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert in welke volgorde de twee matrices moeten worden vermenigvuldigd. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode plaatst de rotatie vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert of de rotatiematrix moet worden toegevoegd of vooraf moet worden geplaatst. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Schaalt de lokale geometrische transformatie met de opgegeven waarden. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De hoeveelheid waarmee de transformatie langs de x-as moet worden geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie langs de y-as moet worden geschaald. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Schaalt de lokale geometrische transformatie met de opgegeven waarden in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De hoeveelheid waarmee de transformatie langs de x-as moet worden geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie langs de y-as moet worden geschaald. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert of de schaalmatrix moet worden toegevoegd of vooraf moet worden geplaatst. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Creëert een lineaire gradiënt met een middenkleur en een lineaire afname naar één kleur aan beide uiteinden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| focus | float | Een waarde van 0 tot 1 die het midden van de gradient specificeert (het punt waarop de gradient uitsluitend uit de eindkleur bestaat). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Creëert een lineaire gradiënt met een middenkleur en een lineaire afname naar één kleur aan beide uiteinden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| focus | float | Een waarde van 0 tot 1 die het midden van de gradient specificeert (het punt waarop de gradient uitsluitend uit de eindkleur bestaat). |
| scale | float | Een waarde van 0 tot 1 die aangeeft hoe snel de kleuren afnemen van de startkleur naar <paramref name="focus" /> (eindkleur). |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Creëert een gradiëntafname gebaseerd op een klokvormige curve.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| focus | float | Een waarde van 0 tot 1 die het midden van de gradient specificeert (het punt waarop de startkleur en eindkleur gelijkmatig worden gemengd). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Creëert een gradiëntafname gebaseerd op een klokvormige curve.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| focus | float | Een waarde van 0 tot 1 die het midden van de gradient specificeert (het punt waarop de gradient uitsluitend uit de eindkleur bestaat). |
| scale | float | Een waarde van 0 tot 1 die aangeeft hoe snel de kleuren afnemen vanaf de <paramref name="focus" />. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde (voorgaan of toevoegen) waarin de translatie moet worden toegepast. |

