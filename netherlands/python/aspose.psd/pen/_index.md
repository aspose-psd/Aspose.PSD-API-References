---
title: "Pen Klasse"
type: docs
weight: 3360
url: /nl/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Initialiseert een nieuw exemplaar van de [Pen](/psd/python-net/aspose.psd/pen/) klasse met de opgegeven [Pen.brush](/psd/python-net/aspose.psd/pen/). |
| [Pen(brush, width)](#Pen_brush_width_2) | Initialiseert een nieuw exemplaar van de [Pen](/psd/python-net/aspose.psd/pen/) klasse met de opgegeven [Pen.brush](/psd/python-net/aspose.psd/pen/) en [Pen.width](/psd/python-net/aspose.psd/pen/). |
| [Pen(color)](#Pen_color_3) | Initialiseert een nieuw exemplaar van de [Pen](/psd/python-net/aspose.psd/pen/) klasse met de opgegeven kleur. |
| [Pen(color, width)](#Pen_color_width_4) | Initialiseert een nieuw exemplaar van de [Pen](/psd/python-net/aspose.psd/pen/) klasse met de opgegeven [Pen.color](/psd/python-net/aspose.psd/pen/) en [Pen.width](/psd/python-net/aspose.psd/pen/) eigenschappen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Haalt op of stelt de uitlijning in voor deze [Pen](/psd/python-net/aspose.psd/pen/). |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Haalt op of stelt de [Pen.brush](/psd/python-net/aspose.psd/pen/) in die de attributen van deze [Pen](/psd/python-net/aspose.psd/pen/) bepaalt. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt op of stelt de kleur van deze [Pen](/psd/python-net/aspose.psd/pen/) in. |
| compound_array | float | r/w | Haalt op of stelt een array van waarden in die een samengestelde pen specificeert. Een samengestelde pen tekent een samengestelde lijn bestaande uit parallelle lijnen en spaties. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Haalt op of stelt een aangepast uiteinde in dat wordt gebruikt aan het einde van lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) worden getekend. |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Haalt op of stelt een aangepast uiteinde in dat wordt gebruikt aan het begin van lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) worden getekend. |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Haalt op of stelt de capstijl in die wordt gebruikt aan het einde van de streepjes die gestippelde lijnen vormen die met deze [Pen](/psd/python-net/aspose.psd/pen/) worden getekend. |
| dash_offset | float | r/w | Haalt op of stelt de afstand in van het begin van een lijn tot het begin van een streepjespatroon. |
| dash_pattern | float | r/w | Haalt op of stelt een array van aangepaste streepjes en spaties in. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Haalt op of stelt de stijl in die wordt gebruikt voor gestippelde lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) worden getekend. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Haalt op of stelt de capstijl in die wordt gebruikt aan het einde van lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) worden getekend. |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Haalt op of stelt de verbindingsstijl in voor de uiteinden van twee opeenvolgende lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) worden getekend. |
| miter_limit | float | r/w | Haalt op of stelt de limiet van de dikte van de verbinding op een afgeschuinde hoek in. |
| opacity | float | r/w | Haalt de opacity van het object op of stelt deze in. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat het object volledig zichtbaar is, een waarde van 1 betekent dat het object volledig ondoorzichtig is. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Haalt de stijl op van lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) worden getekend. |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Haalt op of stelt de capstijl in die wordt gebruikt aan het begin van lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) worden getekend. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Haalt op of stelt een kopie van de geometrische transformatie voor deze [Pen](/psd/python-net/aspose.psd/pen/) in. |
| width | float | r/w | Haalt op of stelt de breedte van deze [Pen](/psd/python-net/aspose.psd/pen/) in, in eenheden van het Graphics-object dat voor het tekenen wordt gebruikt. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Vermenigvuldigt de transformatie-matrix voor deze [Pen](/psd/python-net/aspose.psd/pen/) met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Vermenigvuldigt de transformatie-matrix voor deze [Pen](/psd/python-net/aspose.psd/pen/) met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) in de opgegeven volgorde. |
| reset_transform() | Stelt de geometrische transformatie-matrix voor deze [Pen](/psd/python-net/aspose.psd/pen/) opnieuw in op de identiteit. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Draait de lokale geometrische transformatie met de opgegeven hoek. Deze methode plaatst de rotatie vooraan in de transformatie. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Draait de lokale geometrische transformatie met de opgegeven hoek in de opgegeven volgorde. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Schaalt de lokale geometrische transformatie met de opgegeven factoren. Deze methode plaatst de schaalmatrix vóór de transformatie. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Schaalt de lokale geometrische transformatie met de opgegeven factoren in de opgegeven volgorde. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Stelt de waarden in die de stijl van de cap bepalen die wordt gebruikt om lijnen die door deze [Pen](/psd/python-net/aspose.psd/pen/) zijn getekend te beëindigen. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Verschuift de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Verschuift de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Initialiseert een nieuw exemplaar van de [Pen](/psd/python-net/aspose.psd/pen/) klasse met de opgegeven [Pen.brush](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Een [Pen.brush](/psd/python-net/aspose.psd/pen/) die de vul-eigenschappen van deze [Pen](/psd/python-net/aspose.psd/pen/) bepaalt. |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Initialiseert een nieuw exemplaar van de [Pen](/psd/python-net/aspose.psd/pen/) klasse met de opgegeven [Pen.brush](/psd/python-net/aspose.psd/pen/) en [Pen.width](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Een [Pen.brush](/psd/python-net/aspose.psd/pen/) die de kenmerken van deze [Pen](/psd/python-net/aspose.psd/pen/) bepaalt. |
| width | float | De breedte van de nieuwe [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Initialiseert een nieuw exemplaar van de [Pen](/psd/python-net/aspose.psd/pen/) klasse met de opgegeven kleur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Een [Pen.color](/psd/python-net/aspose.psd/pen/) structuur die de kleur van deze [Pen](/psd/python-net/aspose.psd/pen/) aangeeft. |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Initialiseert een nieuw exemplaar van de [Pen](/psd/python-net/aspose.psd/pen/) klasse met de opgegeven [Pen.color](/psd/python-net/aspose.psd/pen/) en [Pen.width](/psd/python-net/aspose.psd/pen/) eigenschappen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Een [Pen.color](/psd/python-net/aspose.psd/pen/) structuur die de kleur van deze [Pen](/psd/python-net/aspose.psd/pen/) aangeeft. |
| width | float | Een waarde die de breedte van deze [Pen](/psd/python-net/aspose.psd/pen/) aangeeft. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Vermenigvuldigt de transformatie-matrix voor deze [Pen](/psd/python-net/aspose.psd/pen/) met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Het [Matrix](/psd/python-net/aspose.psd/matrix/) object waarmee de transformatie-matrix moet worden vermenigvuldigd. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Vermenigvuldigt de transformatie-matrix voor deze [Pen](/psd/python-net/aspose.psd/pen/) met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee de transformatie-matrix moet worden vermenigvuldigd. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde waarin de vermenigvuldigingsbewerking moet worden uitgevoerd. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Draait de lokale geometrische transformatie met de opgegeven hoek. Deze methode plaatst de rotatie vooraan in de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Draait de lokale geometrische transformatie met de opgegeven hoek in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert of de rotatiematrix moet worden toegevoegd of vooraf moet worden geplaatst. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Schaalt de lokale geometrische transformatie met de opgegeven factoren. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De factor waarmee de transformatie in de x-as wordt geschaald. |
| sy | float | De factor waarmee de transformatie in de y-as wordt geschaald. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Schaalt de lokale geometrische transformatie met de opgegeven factoren in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De factor waarmee de transformatie in de x-as wordt geschaald. |
| sy | float | De factor waarmee de transformatie in de y-as wordt geschaald. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert of de schaalmatrix moet worden toegevoegd of vooraf moet worden geplaatst. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Stelt de waarden in die de stijl van de cap bepalen die wordt gebruikt om lijnen die door deze [Pen](/psd/python-net/aspose.psd/pen/) zijn getekend te beëindigen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Een [LineCap](/psd/python-net/aspose.psd/linecap/) die de cap-stijl vertegenwoordigt die moet worden gebruikt aan het begin van lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) zijn getekend. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Een [LineCap](/psd/python-net/aspose.psd/linecap/) die de cap-stijl vertegenwoordigt die moet worden gebruikt aan het einde van lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) zijn getekend. |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | Een [LineCap](/psd/python-net/aspose.psd/linecap/) die de cap-stijl vertegenwoordigt die moet worden gebruikt aan het begin of einde van gestreepte lijnen die met deze [Pen](/psd/python-net/aspose.psd/pen/) zijn getekend. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Verschuift de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Verschuift de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde (voorgaan of toevoegen) waarin de translatie moet worden toegepast. |

