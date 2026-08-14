---
title: "Pen Klasse"
type: docs
weight: 3360
url: /de/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Initialisiert eine neue Instanz der [Pen](/psd/python-net/aspose.psd/pen/) Klasse mit dem angegebenen [Pen.brush](/psd/python-net/aspose.psd/pen/). |
| [Pen(brush, width)](#Pen_brush_width_2) | Initialisiert eine neue Instanz der [Pen](/psd/python-net/aspose.psd/pen/) Klasse mit dem angegebenen [Pen.brush](/psd/python-net/aspose.psd/pen/) und [Pen.width](/psd/python-net/aspose.psd/pen/). |
| [Pen(color)](#Pen_color_3) | Initialisiert eine neue Instanz der [Pen](/psd/python-net/aspose.psd/pen/) Klasse mit der angegebenen Farbe. |
| [Pen(color, width)](#Pen_color_width_4) | Initialisiert eine neue Instanz der [Pen](/psd/python-net/aspose.psd/pen/) Klasse mit den angegebenen [Pen.color](/psd/python-net/aspose.psd/pen/) und [Pen.width](/psd/python-net/aspose.psd/pen/) Eigenschaften. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Liest oder setzt die Ausrichtung für dieses [Pen](/psd/python-net/aspose.psd/pen/). |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Liest oder setzt den [Pen.brush](/psd/python-net/aspose.psd/pen/), der die Attribute dieses [Pen](/psd/python-net/aspose.psd/pen/) bestimmt. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt die Farbe dieses [Pen](/psd/python-net/aspose.psd/pen/). |
| compound_array | float | r/w | Liest oder setzt ein Array von Werten, das einen zusammengesetzten Stift spezifiziert. Ein zusammengesetzter Stift zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Lücken besteht. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Liest oder setzt eine benutzerdefinierte Kappe, die am Ende von Linien verwendet wird, die mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet werden. |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Liest oder setzt eine benutzerdefinierte Kappe, die am Anfang von Linien verwendet wird, die mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet werden. |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Liest oder setzt den Kappenstil, der am Ende der Striche verwendet wird, aus denen gestrichelte Linien, die mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet werden, bestehen. |
| dash_offset | float | r/w | Liest oder setzt den Abstand vom Anfang einer Linie bis zum Beginn eines Strichmusters. |
| dash_pattern | float | r/w | Liest oder setzt ein Array von benutzerdefinierten Strichen und Lücken. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Liest oder setzt den Stil, der für gestrichelte Linien verwendet wird, die mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet werden. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Liest oder setzt den Kappenstil, der am Ende von Linien verwendet wird, die mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet werden. |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Liest oder setzt den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet werden. |
| miter_limit | float | r/w | Liest oder setzt die Grenze der Dicke der Verbindung an einer Gehrungsecke. |
| Deckkraft | float | r/w | Liest oder setzt die Deckkraft des Objekts. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass das Objekt vollständig sichtbar ist, ein Wert von 1 bedeutet, dass das Objekt vollständig undurchsichtig ist. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Liest den Stil der mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichneten Linien. |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Liest oder setzt den Kappenstil, der am Anfang von Linien verwendet wird, die mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet werden. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Liest oder setzt eine Kopie der geometrischen Transformation für dieses [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | r/w | Liest oder setzt die Breite dieses [Pen](/psd/python-net/aspose.psd/pen/), in Einheiten des zum Zeichnen verwendeten Graphics-Objekts. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Multipliziert die Transformationsmatrix für diesen [Pen](/psd/python-net/aspose.psd/pen/) mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Multipliziert die Transformationsmatrix für diesen [Pen](/psd/python-net/aspose.psd/pen/) mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/) in der angegebenen Reihenfolge. |
| reset_transform() | Setzt die geometrische Transformationsmatrix für diesen [Pen](/psd/python-net/aspose.psd/pen/) auf die Identität zurück. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Dreht die lokale geometrische Transformation um den angegebenen Winkel. Diese Methode fügt die Rotation der Transformation voran. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. Diese Methode fügt die Skalierungsmatrix der Transformation voran. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Legt die Werte fest, die den Stil der Endkappe bestimmen, die für von diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnete Linien verwendet wird. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Initialisiert eine neue Instanz der [Pen](/psd/python-net/aspose.psd/pen/) Klasse mit dem angegebenen [Pen.brush](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Ein [Pen.brush](/psd/python-net/aspose.psd/pen/), das die Fülleigenschaften dieses [Pen](/psd/python-net/aspose.psd/pen/) bestimmt. |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Initialisiert eine neue Instanz der [Pen](/psd/python-net/aspose.psd/pen/) Klasse mit dem angegebenen [Pen.brush](/psd/python-net/aspose.psd/pen/) und [Pen.width](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Ein [Pen.brush](/psd/python-net/aspose.psd/pen/), das die Eigenschaften dieses [Pen](/psd/python-net/aspose.psd/pen/) bestimmt. |
| width | float | Die Breite des neuen [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Initialisiert eine neue Instanz der [Pen](/psd/python-net/aspose.psd/pen/) Klasse mit der angegebenen Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Eine [Pen.color](/psd/python-net/aspose.psd/pen/)-Struktur, die die Farbe dieses [Pen](/psd/python-net/aspose.psd/pen/) angibt. |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Initialisiert eine neue Instanz der [Pen](/psd/python-net/aspose.psd/pen/) Klasse mit den angegebenen [Pen.color](/psd/python-net/aspose.psd/pen/) und [Pen.width](/psd/python-net/aspose.psd/pen/) Eigenschaften.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Eine [Pen.color](/psd/python-net/aspose.psd/pen/)-Struktur, die die Farbe dieses [Pen](/psd/python-net/aspose.psd/pen/) angibt. |
| width | float | Ein Wert, der die Breite dieses [Pen](/psd/python-net/aspose.psd/pen/) angibt. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Multipliziert die Transformationsmatrix für diesen [Pen](/psd/python-net/aspose.psd/pen/) mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Das [Matrix](/psd/python-net/aspose.psd/matrix/)-Objekt, mit dem die Transformationsmatrix multipliziert wird. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Multipliziert die Transformationsmatrix für diesen [Pen](/psd/python-net/aspose.psd/pen/) mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/) in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die [Matrix](/psd/python-net/aspose.psd/matrix/), mit der die Transformationsmatrix multipliziert wird. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Die Reihenfolge, in der die Multiplikationsoperation ausgeführt wird. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Dreht die lokale geometrische Transformation um den angegebenen Winkel. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ein [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), der angibt, ob die Rotationsmatrix angehängt oder vorangestellt werden soll. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. Diese Methode fügt die Skalierungsmatrix der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Faktor, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Faktor, um den die Transformation in y-Richtung skaliert wird. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Faktor, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Faktor, um den die Transformation in y-Richtung skaliert wird. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ein [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), der angibt, ob die Skalierungs‑Matrix angehängt oder vorangestellt werden soll. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Legt die Werte fest, die den Stil der Endkappe bestimmen, die für von diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnete Linien verwendet wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Ein [LineCap](/psd/python-net/aspose.psd/linecap/), der den Kappenstil darstellt, der am Anfang von mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichneten Linien verwendet wird. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Ein [LineCap](/psd/python-net/aspose.psd/linecap/), der den Kappenstil darstellt, der am Ende von mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichneten Linien verwendet wird. |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | Ein [LineCap](/psd/python-net/aspose.psd/linecap/), der den Kappenstil darstellt, der am Anfang oder Ende von gestrichelten Linien, die mit diesem [Pen](/psd/python-net/aspose.psd/pen/) gezeichnet werden, verwendet wird. |

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

