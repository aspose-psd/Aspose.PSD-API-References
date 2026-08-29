---
title: "Matrix"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Ersetzt die GDI‑Matrix."
type: docs
weight: 69
url: /de/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Ersetzt die GDI+ Matrix.

Die meisten Algorithmen stammen aus Sun's AffineTransform.java. Java‑Namen für Matrix‑Elemente, die intern verwendet werden. Zuordnung von Java‑Namen zu .net‑Namen mit Beschreibung: m00 M11 Skalierung X m10 M12 Scherung Y m01 M21 Scherung X m11 M22 Skalierung Y m02 M31 Translation X m12 M32 Translation Y
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Matrix()](#Matrix--) | Initialisiert eine neue Instanz der Matrix‑Klasse als Einheitsmatrix. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Initialisiert eine neue Instanz der  Matrix  Klasse. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Erstellt eine Kopie der  Matrix  Klasse. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Initialisiert eine neue Instanz der  Aspose.Imaging.Matrix  Klasse für die geometrische Transformation, die durch das angegebene Rechteck und das Punkte‑Array definiert ist. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Initialisiert eine neue Instanz der  Aspose.Imaging.Matrix  Klasse für die geometrische Transformation, die durch das angegebene Rechteck und das Punkte‑Array definiert ist. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Dieses Flag‑Bit gibt an, dass die durch dieses Objekt definierte Transformation ein Spiegelbild um eine Achse erzeugt, das das normalerweise rechtshändige Koordinatensystem in ein linkshändiges System umwandelt, zusätzlich zu den durch andere Flag‑Bits angegebenen Konvertierungen. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Dieses Flag‑Bit gibt an, dass die durch dieses Objekt definierte Transformation eine Drehung um einen beliebigen Winkel ausführt, zusätzlich zu den durch andere Flag‑Bits angegebenen Konvertierungen. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Eine allgemeine Skalierung multipliziert die Länge von Vektoren um unterschiedliche Beträge in x‑ und y‑Richtung, ohne den Winkel zwischen senkrechten Vektoren zu ändern. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Diese Konstante gibt an, dass die durch dieses Objekt definierte Transformation eine beliebige Umwandlung der Eingabekoordinaten vornimmt. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Eine Identitätstransformation ist eine, bei der die Ausgabekoordinaten stets mit den Eingabekoordinaten übereinstimmen. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Diese Konstante ist eine Bitmaske für beliebige der Rotations‑Flag‑Bits. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Diese Konstante ist eine Bitmaske für beliebige der Skalierungs‑Flag‑Bits. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Dieses Flag‑Bit gibt an, dass die durch dieses Objekt definierte Transformation eine Quadrantendrehung um ein Vielfaches von 90 Grad ausführt, zusätzlich zu den durch andere Flag‑Bits angegebenen Konvertierungen. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Eine Translation verschiebt die Koordinaten um einen konstanten Betrag in x‑ und y‑Richtung, ohne die Länge oder den Winkel von Vektoren zu ändern. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Eine einheitliche Skalierung multipliziert die Länge von Vektoren um denselben Betrag in sowohl x‑ als auch y‑Richtung, ohne den Winkel zwischen den Vektoren zu ändern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Gibt eine Kopie der Matrixelemente zurück. |
| [getM11()](#getM11--) | Gibt das Matrixelement in der ersten Zeile, ersten Spalte zurück. |
| [getM12()](#getM12--) | Gibt das Matrixelement in der ersten Zeile, zweiten Spalte zurück. |
| [getM21()](#getM21--) | Gibt das Matrixelement in der zweiten Zeile, ersten Spalte zurück. |
| [getM22()](#getM22--) | Gibt das Matrixelement in der zweiten Zeile, zweiten Spalte zurück. |
| [getM31()](#getM31--) | Gibt das Matrixelement in der dritten Zeile, ersten Spalte zurück. |
| [getM32()](#getM32--) | Gibt das Matrixelement in der dritten Zeile, ersten Spalte zurück. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Bestimmt, ob zwei Matrizen gleich sind. |
| [isIdentity()](#isIdentity--) | Gibt `true` zurück, wenn dieses `AffineTransform` eine Identitätstransformation ist. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix und in der im Parameter order angegebenen Reihenfolge. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Setzt diese Matrix zurück, sodass sie die Elemente der Einheitsmatrix enthält. |
| [rotate(float angle)](#rotate-float-) | Wendet eine im Winkel‑Parameter angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend‑)Reihenfolge an. |
| [rotate(float angle, int order)](#rotate-float-int-) | Wendet eine im Winkel‑Parameter angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend‑)Reihenfolge an. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Wendet eine im Uhrzeigersinn gerichtete Drehung um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an. |
| [scale(float sx, float sy)](#scale-float-float-) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge an. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der angegebenen Reihenfolge an. |
| [toString()](#toString--) | Gibt einen  System.String  zurück, der diese Instanz darstellt. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Wendet die durch diese Matrix dargestellte geometrische Transformation auf ein angegebenes Punktarray an. |
| [translate(float tx, float ty)](#translate-float-float-) | Wendet den angegebenen Translationsvektor auf diese Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge an. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initialisiert eine neue Instanz der Matrix‑Klasse als Einheitsmatrix.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Initialisiert eine neue Instanz der  Matrix  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 Shear X |
| m22 | float | m11 M22 Scale Y |
| m31 | float | m02 M31 Translate X |
| m32 | float | m12 M32 Translate Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Erstellt eine Kopie der  Matrix  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | die Basis-Matrix für die Anpassung |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Matrix  Klasse für die geometrische Transformation, die durch das angegebene Rechteck und das Punkte‑Array definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Eine  Aspose.Imaging.RectangleF  Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Ein Array von drei  Aspose.Imaging.PointF  Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Matrix  Klasse für die geometrische Transformation, die durch das angegebene Rechteck und das Punkte‑Array definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Eine  Aspose.Imaging.Rectangle  Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Ein Array von drei  Aspose.Imaging.Point  Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Dieses Flag‑Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Spiegelbild‑Umkehr um eine Achse durchführt, wodurch das normalerweise rechtshändige Koordinatensystem in ein linkshändiges System umgewandelt wird, zusätzlich zu den von anderen Flag‑Bits angegebenen Umwandlungen. Ein rechtshändiges Koordinatensystem ist eines, bei dem die positive X‑Achse sich gegen den Uhrzeigersinn dreht, um die positive Y‑Achse zu überlagern, ähnlich der Richtung, in die sich die Finger Ihrer rechten Hand krümmen, wenn Sie Ihren Daumen frontal betrachten. Ein linkshändiges Koordinatensystem ist eines, bei dem die positive X‑Achse sich im Uhrzeigersinn dreht, um die positive Y‑Achse zu überlagern, ähnlich der Richtung, in die sich die Finger Ihrer linken Hand krümmen. Es gibt keinen mathematischen Weg, den Winkel der ursprünglichen Spiegel‑ oder Umkehrtransformation zu bestimmen, da alle Winkel der Umkehr bei einer geeigneten nachfolgenden Rotation identisch sind. NOTE: TypeFlip wurde hinzugefügt, nachdem GENERAL\_TRANSFORM bereits öffentlich verbreitet war, und die Flag‑Bits konnten nicht mehr bequem neu nummeriert werden, ohne binäre Inkompatibilität in externem Code einzuführen.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Dieses Flag‑Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Drehung um einen beliebigen Winkel ausführt, zusätzlich zu den von anderen Flag‑Bits angegebenen Umwandlungen. Eine Drehung ändert die Winkel von Vektoren um denselben Betrag, unabhängig von der ursprünglichen Richtung des Vektors, und ohne die Länge des Vektors zu verändern. Dieses Flag‑Bit ist gegenseitig ausschließend mit dem

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Eine allgemeine Skalierung multipliziert die Länge von Vektoren in x- und y-Richtung um unterschiedliche Beträge, ohne den Winkel zwischen senkrechten Vektoren zu ändern. Dieses Flag‑Bit ist gegenseitig ausschließend mit dem TypeUniformScale‑Flag.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Diese Konstante zeigt an, dass die durch dieses Objekt definierte Transformation eine beliebige Umwandlung der Eingabekoordinaten durchführt. Wenn diese Transformation durch eine der oben genannten Konstanten klassifiziert werden kann, ist der Typ entweder die Konstante TypeIdentity oder eine Kombination der entsprechenden Flag‑Bits für die verschiedenen Koordinatenumwandlungen, die diese Transformation ausführt.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Eine Identitätstransformation ist eine, bei der die Ausgabekoordinaten immer den Eingabekoordinaten entsprechen. Wenn diese Transformation etwas anderes als die Identitätstransformation ist, wird der Typ entweder die Konstante GENERAL\_TRANSFORM oder eine Kombination der entsprechenden Flag‑Bits für die verschiedenen Koordinatenumwandlungen, die diese Transformation ausführt, sein.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Diese Konstante ist eine Bitmaske für beliebige der Rotations‑Flag‑Bits.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Diese Konstante ist eine Bitmaske für beliebige der Skalierungs‑Flag‑Bits.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Dieses Flag‑Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Quadrant‑Drehung um ein Vielfaches von 90 Grad zusätzlich zu den von anderen Flag‑Bits angegebenen Umwandlungen durchführt. Eine Drehung ändert die Winkel von Vektoren um denselben Betrag, unabhängig von der ursprünglichen Richtung des Vektors, und ohne die Länge des Vektors zu verändern. Dieses Flag‑Bit ist gegenseitig ausschließend mit dem TypeGeneralRotation‑Flag.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Eine Translation verschiebt die Koordinaten um einen konstanten Betrag in x‑ und y‑Richtung, ohne die Länge oder den Winkel von Vektoren zu ändern.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Eine einheitliche Skalierung multipliziert die Länge von Vektoren in x- und y‑Richtung um denselben Betrag, ohne den Winkel zwischen den Vektoren zu ändern. Dieses Flag‑Bit ist gegenseitig ausschließend mit dem TypeGeneralScale‑Flag.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  System.Object  zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene  System.Object  dieser Instanz gleich ist; andernfalls  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


Gibt eine Kopie der Matrixelemente zurück.

**Returns:**
float[] – Eine Kopie der Matrixelemente.
### getM11() {#getM11--}
```
public float getM11()
```


Liefert das Matrixelement in der ersten Zeile, ersten Spalte. Stellt die Skalierung entlang der X‑Achse dar.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Liefert das Matrixelement in der ersten Zeile, zweiten Spalte. Stellt die Scherung entlang der Y‑Achse dar.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Liefert das Matrixelement in der zweiten Zeile, ersten Spalte. Stellt die Scherung entlang der X‑Achse dar.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Liefert das Matrixelement in der zweiten Zeile, zweiten Spalte. Stellt die Skalierung entlang der Y‑Achse dar.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Liefert das Matrixelement in der dritten Zeile, ersten Spalte. Stellt die Translation entlang der X‑Achse dar.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Liefert das Matrixelement in der dritten Zeile, ersten Spalte. Stellt die Translation entlang der Y‑Achse dar.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int - Ein Hashcode für diese Instanz, geeignet für die Verwendung in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Bestimmt, ob zwei Matrizen gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | Die erste Matrix zum Vergleichen. |
| b | [Matrix](../../com.aspose.psd/matrix) | Die zweite Matrix zum Vergleichen. |

**Returns:**
boolean – Wahr, wenn die Matrizen gleich sind.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Gibt `true` zurück, wenn dieses `AffineTransform` eine Identitätstransformation ist.

**Returns:**
boolean – `true`, wenn dieses `AffineTransform` eine Identitätstransformation ist; `false` sonst.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Die Matrix, mit der multipliziert wird. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix und in der im Parameter order angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Der tx. Der tx. Der tx. |
| Reihenfolge | int | Die Reihenfolge. Die Reihenfolge. Die Reihenfolge. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Setzt diese Matrix zurück, sodass sie die Elemente der Einheitsmatrix enthält.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Wendet eine im Winkel‑Parameter angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend‑)Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Wendet eine im Winkel‑Parameter angegebene Drehung im Uhrzeigersinn um den Ursprung (null x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |
| Reihenfolge | int | Die Matrixreihenfolge. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend‑)Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Winkel. |
| point | [PointF](../../com.aspose.psd/pointf) | Der Punkt. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Wendet eine im Uhrzeigersinn gerichtete Drehung um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Winkel. |
| point | [PointF](../../com.aspose.psd/pointf) | Der Punkt. |
| Reihenfolge | int | Die Reihenfolge. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der sx. Der sx. Der sx. |
| sy | float | Der sy. Der sy. Der sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der angegebenen Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | float | Der Skalierungsfaktor X. |
| scaleY | float | Der Skalierungsfaktor Y. |
| Reihenfolge | int | Die Reihenfolge. |

### toString() {#toString--}
```
public String toString()
```


Gibt einen  System.String  zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein  System.String  der diese Instanz darstellt.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Wendet die durch diese Matrix dargestellte geometrische Transformation auf ein angegebenes Punktarray an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Die Punkte. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Wendet den angegebenen Translationsvektor auf diese Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tx | float | Der tx. Der tx. Der tx. |
| ty | float | Der ty. Der ty. Der ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| offsetX | float | Der Versatz X. |
| offsetY | float | Der Versatz Y. |
| Reihenfolge | int | Die Reihenfolge. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

