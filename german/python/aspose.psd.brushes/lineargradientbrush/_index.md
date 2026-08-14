---
title: "LinearGradientBrush‑Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse mit Standardparametern.<br/>            Die Startfarbe ist Schwarz, die Endfarbe ist Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse basierend auf einem Rechteck, Start‑ und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse basierend auf einem Rechteck, Start‑ und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse basierend auf einem Rechteck, Start‑ und Endfarben sowie einem Orientierungswinkel. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse basierend auf einem Rechteck, Start‑ und Endfarben sowie einem Orientierungswinkel. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| angle | float | r/w | Ruft den Gradientwinkel ab oder legt ihn fest. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Liest oder legt ein [Blend](/psd/python-net/aspose.psd/blend/) fest, das Positionen und Faktoren definiert, die einen benutzerdefinierten Abfall für den Verlauf bestimmen. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder legt die Endfarbe des Verlaufs fest. |
| gamma_correction | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Gammakorrektur für dieses [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) aktiviert ist. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Ruft ein [ColorBlend](/psd/python-net/aspose.psd/colorblend/) ab oder legt es fest, das einen mehrfarbigen linearen Gradient definiert. |
| is_angle_scalable | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) während Transformationen mit diesem [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) geändert wird. |
| is_transform_changed | bool | r | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder<br/>            das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Liest oder legt die Start‑ und Endfarben des Verlaufs fest. |
| Deckkraft | float | r/w | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Ruft einen rechteckigen Bereich ab oder legt ihn fest, der die Start- und Endpunkte des Gradienten definiert. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder legt die Startfarbe des Verlaufs fest. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Erstellt einen linearen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Erstellt einen linearen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Erstellt einen Verlauf‑Abfall basierend auf einer glockenförmigen Kurve. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Erstellt einen Verlauf‑Abfall basierend auf einer glockenförmigen Kurve. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse mit Standardparametern.<br/>            Die Startfarbe ist Schwarz, die Endfarbe ist Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse mit den angegebenen Punkten und Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Eine [Point](/psd/python-net/aspose.psd/point/)‑Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Eine [Point](/psd/python-net/aspose.psd/point/)‑Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Startfarbe des linearen Farbverlaufs darstellt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse mit den angegebenen Punkten und Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Eine [Point](/psd/python-net/aspose.psd/point/)‑Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Eine [Point](/psd/python-net/aspose.psd/point/)‑Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Startfarbe des linearen Farbverlaufs darstellt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse basierend auf einem Rechteck, Start‑ und Endfarben sowie einem Orientierungswinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x‑Achse, der Orientierungslinie des Farbverlaufs. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse basierend auf einem Rechteck, Start‑ und Endfarben sowie einem Orientierungswinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x‑Achse, der Orientierungslinie des Farbverlaufs. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse basierend auf einem Rechteck, Start‑ und Endfarben sowie einem Orientierungswinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x‑Achse, der Orientierungslinie des Farbverlaufs. |
| is_angle_scalable | bool | Wenn auf <c>true</c> gesetzt, wird der Winkel während Transformationen mit diesem [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) geändert. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initialisiert eine neue Instanz der [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)‑Klasse basierend auf einem Rechteck, Start‑ und Endfarben sowie einem Orientierungswinkel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Eine [Color](/psd/python-net/aspose.psd/color/) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x‑Achse, der Orientierungslinie des Farbverlaufs. |
| is_angle_scalable | bool | Wenn auf <c>true</c> gesetzt, wird der Winkel während Transformationen mit diesem [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) geändert. |

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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Erstellt einen linearen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Erstellt einen linearen Verlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |
| scale | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben von der Startfarbe zur <paramref name="focus" /> (Endfarbe) abfallen. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Erstellt einen Verlauf‑Abfall basierend auf einer glockenförmigen Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem die Start- und Endfarbe zu gleichen Teilen gemischt werden). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Erstellt einen Verlauf‑Abfall basierend auf einer glockenförmigen Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |
| scale | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben von der <paramref name="focus" /> abfallen. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


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

