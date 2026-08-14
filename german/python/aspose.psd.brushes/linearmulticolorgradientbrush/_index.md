---
title: "LinearMulticolorGradientBrush Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/psd/python-net/aspose.psd/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse mit Standardparametern.<br/>            Die Startfarbe ist schwarz, die Endfarbe ist weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1). |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse mit den angegebenen Punkten. |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse mit den angegebenen Punkten. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| angle | float | r/w | Ruft den Gradientwinkel ab oder legt ihn fest. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| gamma_correction | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Gammakorrektur für dieses [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) aktiviert ist. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Ruft ein [ColorBlend](/psd/python-net/aspose.psd/colorblend/) ab oder legt es fest, das einen mehrfarbigen linearen Gradient definiert. |
| is_angle_scalable | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) während Transformationen mit diesem [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) geändert wird. |
| is_transform_changed | bool | r | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder<br/>            das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt. |
| Deckkraft | float | r/w | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Ruft einen rechteckigen Bereich ab oder legt ihn fest, der die Start- und Endpunkte des Gradienten definiert. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Ruft eine Kopie des [Matrix](/psd/python-net/aspose.psd/matrix/) ab oder legt sie fest, die eine lokale geometrische Transformation für diesen [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) definiert. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Ruft eine [WrapMode](/psd/python-net/aspose.psd/wrapmode/) Aufzählung ab oder legt sie fest, die den Wrap-Modus für diesen [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Erstellt einen neuen tiefen Klon des aktuellen [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multipliziert die [Matrix](/psd/python-net/aspose.psd/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/) durch Voranstellen der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multipliziert die [Matrix](/psd/python-net/aspose.psd/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/) in der angegebenen Reihenfolge. |
| reset_transform() | Setzt die Eigenschaft [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) auf die Identität zurück. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs‑Matrix der Transformation voran. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse mit Standardparametern.<br/>            Die Startfarbe ist schwarz, die Endfarbe ist weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1).

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse mit den angegebenen Punkten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Eine [Point](/psd/python-net/aspose.psd/point/)‑Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Eine [Point](/psd/python-net/aspose.psd/point/)‑Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse mit den angegebenen Punkten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Eine [Point](/psd/python-net/aspose.psd/point/)‑Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Eine [Point](/psd/python-net/aspose.psd/point/)‑Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x‑Achse, der Orientierungslinie des Farbverlaufs. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x‑Achse, der Orientierungslinie des Farbverlaufs. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x‑Achse, der Orientierungslinie des Farbverlaufs. |
| is_angle_scalable | bool | Wenn auf <c>true</c> gesetzt, wird der Winkel während Transformationen mit diesem [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) geändert. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Initialisiert eine neue Instanz der [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x‑Achse, der Orientierungslinie des Farbverlaufs. |
| is_angle_scalable | bool | Wenn auf <c>true</c> gesetzt, wird der Winkel während Transformationen mit diesem [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) geändert. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Erstellt einen neuen tiefen Klon des aktuellen [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Ein neuer [Brush](/psd/python-net/aspose.psd/brush/), der ein tiefer Klon dieser [Brush](/psd/python-net/aspose.psd/brush/)‑Instanz ist. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multipliziert die [Matrix](/psd/python-net/aspose.psd/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/) durch Voranstellen der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die [Matrix](/psd/python-net/aspose.psd/matrix/), mit der die geometrische Transformation multipliziert wird. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multipliziert die [Matrix](/psd/python-net/aspose.psd/matrix/), die die lokale geometrische Transformation dieses [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) darstellt, mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/) in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die [Matrix](/psd/python-net/aspose.psd/matrix/), mit der die geometrische Transformation multipliziert wird. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ein [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), der angibt, in welcher Reihenfolge die beiden Matrizen zu multiplizieren sind. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ein [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), der angibt, ob die Rotationsmatrix angehängt oder vorangestellt werden soll. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs‑Matrix der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y‑Richtung skaliert wird. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y‑Richtung skaliert wird. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ein [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), der angibt, ob die Skalierungs‑Matrix angehängt oder vorangestellt werden soll. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Die Reihenfolge (voranstellen oder anhängen), in der die Verschiebung angewendet wird. |

