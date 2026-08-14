---
title: "Matrix-Klasse"
type: docs
weight: 3000
url: /de/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Matrix()](#Matrix__1) | Initialisiert eine neue Instanz der Matrix-Klasse als Einheitsmatrix. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Initialisiert eine neue Instanz der [Matrix](/psd/python-net/aspose.psd/matrix/) Klasse. |
| [Matrix(origin)](#Matrix_origin_3) | Erstellt eine Kopie der [Matrix](/psd/python-net/aspose.psd/matrix/) Klasse. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Initialisiert eine neue Instanz der [Matrix](/psd/python-net/aspose.psd/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Initialisiert eine neue Instanz der [Matrix](/psd/python-net/aspose.psd/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| TYPE_FLIP [statisch] | int | r | Dieses Flag‑Bit zeigt an, dass die durch dieses Objekt definierte Transformation<br/>            eine Spiegelbild‑Umkehr um eine Achse durchführt, die das<br/>            normalerweise rechtshändige Koordinatensystem in ein linkshändiges<br/>            System ändert, zusätzlich zu den Umwandlungen, die durch andere Flag‑Bits angegeben werden.<br/>            Ein rechtshändiges Koordinatensystem ist eines, bei dem die positive X‑Achse<br/>            gegen den Uhrzeigersinn rotiert, um die positive Y‑Achse zu überlagern,<br/>            ähnlich der Richtung, in die sich die Finger Ihrer rechten Hand<br/>            krümmen, wenn Sie Ihren Daumen frontal ansehen.<br/>            Ein linkshändiges Koordinatensystem ist eines, bei dem die positive X‑Achse<br/>            im Uhrzeigersinn rotiert, um die positive Y‑Achse zu überlagern, ähnlich<br/>            der Richtung, in die sich die Finger Ihrer linken Hand krümmen.<br/>            Es gibt keinen mathematischen Weg, den Winkel der<br/>            ursprünglichen Umkehr‑ oder Spiegelungs‑Transformation zu bestimmen, da alle Winkel<br/>            der Umkehr identisch sind, wenn eine geeignete korrigierende Rotation angewendet wird.<br/>            HINWEIS: TypeFlip wurde hinzugefügt, nachdem GENERAL_TRANSFORM öffentlich<br/>            verbreitet war und die Flag‑Bits nicht mehr bequem<br/>            neu nummeriert werden konnten, ohne binäre Inkompatibilität im externen<br/>            Code einzuführen. |
| TYPE_GENERAL_ROTATION [static] | int | r | Dieses flag bit zeigt an, dass die durch dieses Objekt definierte Transformation<br/>            eine Rotation um einen beliebigen Winkel zusätzlich zu den<br/>            von anderen flag bits angegebenen Konvertierungen durchführt.<br/>            Eine Rotation ändert die Winkel von Vektoren um denselben Betrag<br/>            unabhängig von der ursprünglichen Richtung des Vektors und ohne<br/>            die Länge des Vektors zu verändern.<br/>            Dieses flag bit ist wechselseitig exklusiv zu dem |
| TYPE_GENERAL_SCALE [static] | int | r | Eine allgemeine Skalierung multipliziert die Länge von Vektoren um unterschiedliche<br/>            Beträge in x‑ und y‑Richtung, ohne den Winkel<br/>            zwischen senkrechten Vektoren zu ändern.<br/>            Dieses flag bit ist wechselseitig exklusiv zu dem TypeUniformScale‑Flag. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Diese Konstante zeigt an, dass die durch dieses Objekt definierte Transformation<br/>            eine beliebige Umwandlung der Eingabekoordinaten durchführt.<br/>            Wenn diese Transformation durch eine der oben genannten Konstanten klassifiziert werden kann,<br/>            wird der Typ entweder die Konstante TypeIdentity sein oder ein<br/>            Kombination der entsprechenden flag bits für die verschiedenen Koordinaten‑<br/>            Umwandlungen, die diese Transformation durchführt. |
| TYPE_IDENTITY [static] | int | r | Eine Identitätstransformation ist eine, bei der die Ausgangskoordinaten<br/>            immer dieselben sind wie die Eingabekoordinaten.<br/>            Wenn diese Transformation etwas anderes als die Identitätstransformation ist,<br/>            wird der Typ entweder die Konstante GENERAL_TRANSFORM sein oder ein<br/>            Kombination der entsprechenden flag bits für die verschiedenen Koordinaten‑<br/>            Umwandlungen, die diese Transformation durchführt. |
| TYPE_MASK_ROTATION [static] | int | r | Diese Konstante ist eine Bitmaske für beliebige Rotations‑Flag‑Bits. |
| TYPE_MASK_SCALE [static] | int | r | Diese Konstante ist eine Bitmaske für beliebige Skalierungs‑Flag‑Bits. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Dieses flag bit zeigt an, dass die durch dieses Objekt definierte Transformation<br/>            eine Quadrantrotation um ein Vielfaches von 90 Grad zusätzlich zu den<br/>            von anderen flag bits angegebenen Konvertierungen durchführt.<br/>            Eine Rotation ändert die Winkel von Vektoren um denselben Betrag<br/>            unabhängig von der ursprünglichen Richtung des Vektors und ohne<br/>            die Länge des Vektors zu verändern.<br/>            Dieses flag bit ist wechselseitig exklusiv zu dem TypeGeneralRotation‑Flag. |
| TYPE_TRANSLATION [static] | int | r | Eine Translation verschiebt die Koordinaten um einen konstanten Betrag in x<br/>            und y, ohne die Länge oder den Winkel von Vektoren zu verändern. |
| TYPE_UNIFORM_SCALE [static] | int | r | Eine einheitliche Skalierung multipliziert die Länge von Vektoren um denselben Betrag<br/>            sowohl in x‑ als auch in y‑Richtung, ohne den Winkel zwischen<br/>            Vektoren zu ändern.<br/>            Dieses flag bit ist wechselseitig exklusiv zu dem TypeGeneralScale‑Flag. |
| elements | float | r | Ruft ein Array von Gleitkommawerten ab, das die Elemente dieser [Matrix](/psd/python-net/aspose.psd/matrix/) darstellt. |
| m11 | float | r | Liefert das Matrix-Element in der ersten Zeile, ersten Spalte. Stellt die Skalierung entlang der X-Achse dar. |
| m12 | float | r | Liefert das Matrix-Element in der ersten Zeile, zweiten Spalte. Stellt die Scherung entlang der Y-Achse dar. |
| m21 | float | r | Liefert das Matrix-Element in der zweiten Zeile, ersten Spalte. Stellt die Scherung entlang der X-Achse dar. |
| m22 | float | r | Liefert das Matrix-Element in der zweiten Zeile, zweiten Spalte. Stellt die Skalierung entlang der Y-Achse dar. |
| m31 | float | r | Liefert das Matrix-Element in der dritten Zeile, ersten Spalte. Stellt die Translation entlang der X-Achse dar. |
| m32 | float | r | Liefert das Matrix-Element in der dritten Zeile, ersten Spalte. Stellt die Translation entlang der Y-Achse dar. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_elements()](#get_elements__1) | Liefert eine Kopie der Matrix-Elemente. |
| [multiply(tx)](#multiply_tx_2) | Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix unter Verwendung der (Standard) Prepend‑Reihenfolge. |
| [multiply(tx, order)](#multiply_tx_order_3) | Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix und in der im Parameter order angegebenen Reihenfolge. |
| reset() | Setzt diese Matrix zurück, sodass sie die Elemente der Einheitsmatrix enthält. |
| [rotate(angle)](#rotate_angle_4) | Wendet eine im Parameter angle angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend)‑Reihenfolge an. |
| [rotate(angle, order)](#rotate_angle_order_5) | Wendet eine im Parameter angle angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend)‑Reihenfolge an. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese [Matrix](/psd/python-net/aspose.psd/matrix/) unter Verwendung der angegebenen Reihenfolge an. |
| [scale(sx, sy)](#scale_sx_sy_9) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (Standard) Prepend‑Reihenfolge an. |
| [transform_points(points)](#transform_points_points_10) | Wendet die von dieser [Matrix](/psd/python-net/aspose.psd/matrix/) dargestellte geometrische Transformation auf ein angegebenes Punktarray an. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an. |
| [translate(tx, ty)](#translate_tx_ty_12) | Wendet den angegebenen Translationsvektor auf diese [Matrix](/psd/python-net/aspose.psd/matrix/) unter Verwendung der (Standard) Prepend‑Reihenfolge an. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Initialisiert eine neue Instanz der Matrix-Klasse als Einheitsmatrix.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Initialisiert eine neue Instanz der [Matrix](/psd/python-net/aspose.psd/matrix/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| m11 | float | m00     M11     Skalierung X |
| m12 | float | m10     M12     Scheren Y |
| m21 | float | m01     M21     Scheren X |
| m22 | float | m11     M22     Skalierung Y |
| m31 | float | m02     M31     Verschieben X |
| m32 | float | m12     M32     Verschieben Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Erstellt eine Kopie der [Matrix](/psd/python-net/aspose.psd/matrix/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | Eine Basismatrix zum Kopieren |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Initialisiert eine neue Instanz der [Matrix](/psd/python-net/aspose.psd/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ein Array von drei [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Initialisiert eine neue Instanz der [Matrix](/psd/python-net/aspose.psd/matrix/) Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | Ein Array von drei [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Liefert eine Kopie der Matrix-Elemente.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Eine Kopie der Matrixelemente. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix unter Verwendung der (Standard) Prepend‑Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Die Matrix, mit der multipliziert wird. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix und in der im Parameter order angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Der tx. Der tx. Der tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Die Reihenfolge. Die Reihenfolge. Die Reihenfolge. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Wendet eine im Parameter angle angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend)‑Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Wendet eine im Parameter angle angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Die Matrixreihenfolge. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend)‑Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Winkel. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Der Punkt. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Winkel. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Der Punkt. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Die Reihenfolge. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese [Matrix](/psd/python-net/aspose.psd/matrix/) unter Verwendung der angegebenen Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scale_x | float | Die Skalierung X. |
| scale_y | float | Die Skalierung Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Die Reihenfolge. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (Standard) Prepend‑Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der sx. Der sx. Der sx. |
| sy | float | Der sy. Der sy. Der sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Wendet die von dieser [Matrix](/psd/python-net/aspose.psd/matrix/) dargestellte geometrische Transformation auf ein angegebenes Punktarray an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Die Punkte. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| offset_x | float | Der Versatz X. |
| offset_y | float | Der Versatz Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Die Reihenfolge. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Wendet den angegebenen Translationsvektor auf diese [Matrix](/psd/python-net/aspose.psd/matrix/) unter Verwendung der (Standard) Prepend‑Reihenfolge an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tx | float | Der tx. Der tx. Der tx. |
| ty | float | Der ty. Der ty. Der ty. |

