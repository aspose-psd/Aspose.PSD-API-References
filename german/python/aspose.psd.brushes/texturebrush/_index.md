---
title: "TextureBrush Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild verwendet. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild und den WrapMode verwendet. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild, den WrapMode und das Begrenzungsrechteck verwendet. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild, den WrapMode und das Begrenzungsrechteck verwendet. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Liest das [Image](/psd/python-net/aspose.psd/image/) Objekt, das mit diesem [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Objekt verknüpft ist. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Liest die [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) die mit diesem [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) verknüpft ist. |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gibt das [Rectangle](/psd/python-net/aspose.psd/rectangle/) zurück, das mit diesem [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) verknüpft ist. |
| is_transform_changed | bool | r | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder<br/>            das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt. |
| Deckkraft | float | r/w | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
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


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das [Image](/psd/python-net/aspose.psd/image/)‑Objekt, mit dem dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt Innenflächen füllt. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das [Image](/psd/python-net/aspose.psd/image/)‑Objekt, mit dem dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt Innenflächen füllt. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur, die das Begrenzungsrechteck für dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt darstellt. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das [Image](/psd/python-net/aspose.psd/image/)‑Objekt, mit dem dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt Innenflächen füllt. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur, die das Begrenzungsrechteck für dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt darstellt. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das [Image](/psd/python-net/aspose.psd/image/)‑Objekt, mit dem dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt Innenflächen füllt. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur, die das Begrenzungsrechteck für dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt darstellt. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Ein [ImageAttributes](/psd/python-net/aspose.psd.imageattributes/)-Objekt, das zusätzliche Informationen über das von diesem [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt verwendete Bild enthält. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das [Image](/psd/python-net/aspose.psd/image/)‑Objekt, mit dem dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt Innenflächen füllt. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur, die das Begrenzungsrechteck für dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt darstellt. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Ein [ImageAttributes](/psd/python-net/aspose.psd.imageattributes/)-Objekt, das zusätzliche Informationen über das von diesem [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt verwendete Bild enthält. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild und den WrapMode verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das [Image](/psd/python-net/aspose.psd/image/)‑Objekt, mit dem dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Eine [WrapMode](/psd/python-net/aspose.psd/wrapmode/)-Aufzählung, die angibt, wie dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt gekachelt wird. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild, den WrapMode und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das [Image](/psd/python-net/aspose.psd/image/)‑Objekt, mit dem dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Eine [WrapMode](/psd/python-net/aspose.psd/wrapmode/)-Aufzählung, die angibt, wie dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt gekachelt wird. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur, die das Begrenzungsrechteck für dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt darstellt. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialisiert eine neue Instanz der [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) Klasse, die das angegebene Bild, den WrapMode und das Begrenzungsrechteck verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das [Image](/psd/python-net/aspose.psd/image/)‑Objekt, mit dem dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt Innenflächen füllt. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Eine [WrapMode](/psd/python-net/aspose.psd/wrapmode/)-Aufzählung, die angibt, wie dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt gekachelt wird. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur, die das Begrenzungsrechteck für dieses [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑Objekt darstellt. |

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

