---
title: "PathGradientBrush Klasse"
type: docs
weight: 50
url: /nl/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met het opgegeven pad. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met de opgegeven punten. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met de opgegeven punten. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met de opgegeven punten en wrap-modus. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met de opgegeven punten en wrap-modus. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Haalt of stelt een [Blend](/psd/python-net/aspose.psd/blend/) in die posities en factoren specificeert die een aangepaste afname voor de gradiënt definiëren. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt op of stelt de kleur in het midden van de padgradient in. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Haalt op of stelt het middelpunt van de padgradiënt in. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Haalt op of stelt het focuspunt voor de gradiëntafname in. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Haalt het grafische pad op waarop deze penseel is gebouwd. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Haalt op of stelt een [ColorBlend](/psd/python-net/aspose.psd/colorblend/) in die een meerkleurige lineaire gradiënt definieert. |
| is_transform_changed | bool | r | Haalt een waarde op die aangeeft of transformaties op een of andere manier zijn gewijzigd. Bijvoorbeeld het instellen van de transformatie‑matrix of<br/>            het aanroepen van een van de methoden die de transformatie‑matrix wijzigen. De eigenschap is geïntroduceerd voor achterwaartse compatibiliteit met GDI+. |
| opacity | float | r/w | Haalt op of stelt de dekking van de penseel in. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Haalt de padpunten op waarop deze penseel is gebouwd. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Haalt op of stelt een array van kleuren in die overeenkomen met de punten in het pad dat deze [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) vult. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Maakt een gradient met een middenkleur en een lineaire afname naar één omringende kleur. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Maakt een gradient met een middenkleur en een lineaire afname naar elke omringende kleur. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Maakt een gradientkwast die de kleur verandert vanaf het midden van het pad naar de rand van het pad. De overgang van de ene kleur naar de andere is gebaseerd op een klokvormige curve. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Maakt een gradientkwast die de kleur verandert vanaf het midden van het pad naar de rand van het pad. De overgang van de ene kleur naar de andere is gebaseerd op een klokvormige curve. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met het opgegeven pad.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | De [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) die het gebied definieert dat door deze [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) wordt gevuld. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met de opgegeven punten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met de opgegeven punten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met de opgegeven punten en wrap-modus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Een [WrapMode](/psd/python-net/aspose.psd/wrapmode/) die specificeert hoe vullingen die met deze [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) worden getekend, worden getegeld. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Initialiseert een nieuw exemplaar van de [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) klasse met de opgegeven punten en wrap-modus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Een [WrapMode](/psd/python-net/aspose.psd/wrapmode/) die specificeert hoe vullingen die met deze [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) worden getekend, worden getegeld. |

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

Maakt een gradient met een middenkleur en een lineaire afname naar één omringende kleur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| focus | float | Een waarde van 0 tot 1 die aangeeft waar, langs elke radiaal van het midden van het pad tot de rand van het pad, de middenkleur de hoogste intensiteit heeft. Een waarde van 1 (de standaard) plaatst de hoogste intensiteit in het midden van het pad. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Maakt een gradient met een middenkleur en een lineaire afname naar elke omringende kleur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| focus | float | Een waarde van 0 tot 1 die aangeeft waar, langs elke radiaal van het midden van het pad tot de rand van het pad, de middenkleur de hoogste intensiteit heeft. Een waarde van 1 (de standaard) plaatst de hoogste intensiteit in het midden van het pad. |
| scale | float | Een waarde van 0 tot 1 die de maximale intensiteit van de middenkleur specificeert die wordt gemengd met de randkleur. Een waarde van 1 veroorzaakt de hoogst mogelijke intensiteit van de middenkleur, en dit is de standaardwaarde. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Maakt een gradientkwast die de kleur verandert vanaf het midden van het pad naar de rand van het pad. De overgang van de ene kleur naar de andere is gebaseerd op een klokvormige curve.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| focus | float | Een waarde van 0 tot 1 die aangeeft waar, langs elke radiaal van het midden van het pad tot de rand van het pad, de middenkleur de hoogste intensiteit heeft. Een waarde van 1 (de standaard) plaatst de hoogste intensiteit in het midden van het pad. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Maakt een gradientkwast die de kleur verandert vanaf het midden van het pad naar de rand van het pad. De overgang van de ene kleur naar de andere is gebaseerd op een klokvormige curve.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| focus | float | Een waarde van 0 tot 1 die aangeeft waar, langs elke radiaal van het midden van het pad tot de rand van het pad, de middenkleur de hoogste intensiteit heeft. Een waarde van 1 (de standaard) plaatst de hoogste intensiteit in het midden van het pad. |
| scale | float | Een waarde van 0 tot 1 die de maximale intensiteit van de middenkleur specificeert die wordt gemengd met de randkleur. Een waarde van 1 veroorzaakt de hoogst mogelijke intensiteit van de middenkleur, en dit is de standaardwaarde. |

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

