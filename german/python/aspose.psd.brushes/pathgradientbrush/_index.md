---
title: "PathGradientBrush Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit dem angegebenen Pfad. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten und dem WrapMode. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten und dem WrapMode. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Liest oder legt ein [Blend](/psd/python-net/aspose.psd/blend/) fest, das Positionen und Faktoren definiert, die einen benutzerdefinierten Abfall für den Verlauf bestimmen. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt die Farbe im Zentrum des Pfadverlaufs. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Liest oder setzt den Fokuspunkt für den Verlaufabfall. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Liest den Grafikpfad, auf dem dieser Pinsel aufgebaut ist. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Ruft ein [ColorBlend](/psd/python-net/aspose.psd/colorblend/) ab oder legt es fest, das einen mehrfarbigen linearen Gradient definiert. |
| is_transform_changed | bool | r | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder<br/>            das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt. |
| Deckkraft | float | r/w | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Liest die Pfadpunkte, auf denen dieser Pinsel aufgebaut ist. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt ein Array von Farben, das den Punkten im Pfad entspricht, den dieser [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) füllt. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Erstellt einen Verlauf mit einer Zentralfarbe und einem linearen Abfall zu einer umgebenden Farbe. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Erstellt einen Verlauf mit einer Zentralfarbe und einem linearen Abfall zu jeder umgebenden Farbe. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Erstellt einen Farbverlauf-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Erstellt einen Farbverlauf-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit dem angegebenen Pfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Der [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), der den von diesem [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) gefüllten Bereich definiert. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, das die Punkte darstellt, die die Eckpunkte des Pfades bilden. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, das die Punkte darstellt, die die Eckpunkte des Pfades bilden. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten und dem WrapMode.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, das die Punkte darstellt, die die Eckpunkte des Pfades bilden. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ein [WrapMode](/psd/python-net/aspose.psd/wrapmode/), der angibt, wie mit diesem [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) gezeichnete Füllungen gekachelt werden. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Initialisiert eine neue Instanz der [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) Klasse mit den angegebenen Punkten und dem WrapMode.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, das die Punkte darstellt, die die Eckpunkte des Pfades bilden. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ein [WrapMode](/psd/python-net/aspose.psd/wrapmode/), der angibt, wie mit diesem [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) gezeichnete Füllungen gekachelt werden. |

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

Erstellt einen Verlauf mit einer Zentralfarbe und einem linearen Abfall zu einer umgebenden Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfades bis zum Pfadrand die Zentralfarbe ihre höchste Intensität erreicht. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfades fest. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Erstellt einen Verlauf mit einer Zentralfarbe und einem linearen Abfall zu jeder umgebenden Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfades bis zum Pfadrand die Zentralfarbe ihre höchste Intensität erreicht. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfades fest. |
| scale | float | Ein Wert von 0 bis 1, der die maximale Intensität der Zentralfarbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 erzeugt die höchstmögliche Intensität der Zentralfarbe und ist der Standardwert. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Erstellt einen Farbverlauf-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfades bis zum Pfadrand die Zentralfarbe ihre höchste Intensität erreicht. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfades fest. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Erstellt einen Farbverlauf-Pinsel, der die Farbe vom Zentrum des Pfades nach außen bis zur Pfadrand ändert. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfades bis zum Pfadrand die Zentralfarbe ihre höchste Intensität erreicht. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfades fest. |
| scale | float | Ein Wert von 0 bis 1, der die maximale Intensität der Zentralfarbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 erzeugt die höchstmögliche Intensität der Zentralfarbe und ist der Standardwert. |

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

