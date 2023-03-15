---
title: Class Matrix
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Matrix klas. Ersetzt die GDIMatrix.
type: docs
weight: 5090
url: /de/net/aspose.psd/matrix/
---
## Matrix class

Ersetzt die GDI+-Matrix.

```csharp
public class Matrix
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Matrix](matrix/#constructor)() | Initialisiert eine neue Instanz der Matrix-Klasse als Identitätsmatrix. |
| [Matrix](matrix/#constructor_1)(Matrix) | Erstellt eine Kopie der`Matrix` Klasse. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Initialisiert eine neue Instanz von`Matrix` Klasse in die geometrische Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Initialisiert eine neue Instanz von`Matrix` Klasse in die geometrische Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Initialisiert eine neue Instanz von`Matrix` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Ruft ein Array von Fließkommawerten ab, das die Elemente davon darstellt`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Ruft das Matrixelement in der ersten Zeile der ersten Spalte ab. Stellt den Maßstab entlang der X-Achse dar. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Ruft das Matrixelement in der ersten Zeile und zweiten Spalte ab. Stellt Scherung entlang der Y-Achse dar. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Ruft das Matrixelement in der ersten Spalte der zweiten Zeile ab. Stellt Scherung entlang der X-Achse dar. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Ruft das Matrixelement in der zweiten Zeile und zweiten Spalte ab. Stellt die Skalierung entlang der Y-Achse dar. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Ruft das Matrixelement in der ersten Spalte der dritten Zeile ab. Stellt die Verschiebung entlang der X-Achse dar. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Ruft das Matrixelement in der ersten Spalte der dritten Zeile ab. Stellt die Verschiebung entlang der Y-Achse dar. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Bestimmt, ob die angegebeneObject ist gleich dieser Instanz. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Ruft die Kopie der Matrixelemente ab. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Gibt einen Hash-Code für diese Instanz zurück. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Multipliziert diese Matrix mit der im Matrixparameter angegebenen Matrix unter Verwendung von (Standard) Prepend order. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Multipliziert diese Matrix mit der im matrix-Parameter angegebenen Matrix und in der im order-Parameter angegebenen Reihenfolge. |
| [Reset](../../aspose.psd/matrix/reset/)() | Setzt diese Matrix zurück, um die Elemente der Identitätsmatrix zu haben. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Wendet eine Drehung im Uhrzeigersinn um einen im Winkelparameter angegebenen Betrag um den Ursprung (null x- und y-Koordinaten) für diese Matrix in der Standardreihenfolge (Prepend) an. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Wendet eine Drehung im Uhrzeigersinn um einen im Winkelparameter angegebenen Betrag um den Ursprung (null x- und y-Koordinaten) für diese Matrix in der angegebenen Reihenfolge an. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standardreihenfolge (Prepend) an. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix an, wobei (Standard) Prepend order verwendet wird. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) darauf an`Matrix` unter Verwendung der angegebenen Reihenfolge. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Wendet die hier dargestellte geometrische Transformation an`Matrix` zu einem bestimmten Array von Punkten. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Wendet den angegebenen Übersetzungsvektor darauf an`Matrix` using (default) Prepend order. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Wendet den angegebenen Translationsvektor in der angegebenen Reihenfolge auf diese Matrix an. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Bestimmt, ob zwei Matrizen gleich sind. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Dieses Flag-Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Spiegelbilddrehung um eine Achse durchführt, die das normalerweise rechtshändige Koordinatensystem in ein linkshändiges -System ändert, zusätzlich zu den Umwandlungen, die durch andere Flag-Bits angezeigt werden. Ein rechtshändiges Koordinatensystem ist eines, bei dem sich die positive X -Achse gegen den Uhrzeigersinn dreht, um die positive Y-Achse zu überlagern, ähnlich der Richtung, in der sich die Finger Ihrer rechten Hand krümmen, wenn Sie auf Ihren Daumen starren. Ein linkshändiges Koordinatensystem ist eines, in dem sich die positive X -Achse dreht im Uhrzeigersinn, um die positive Y-Achse ähnlich der Richtung zu überlagern, in der sich die Finger Ihrer linken Hand krümmen. Es gibt keinen mathematischen Weg, um den Winkel der ursprünglichen Spiegel- oder Spiegeltransformation zu bestimmen, da alle Winkel des Kippens bei einer entsprechenden Anpassungsdrehung identisch sind. HINWEIS: TypeFlip wurde nach GENERAL_TRANSFORM hinzugefügt war im öffentlichen -Umlauf und die Flag-Bits konnten nicht mehr bequem neu nummeriert werden, ohne eine binäre Inkompatibilität in den Outside -Code einzuführen. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Dieses Flag-Bit zeigt an, dass die durch dieses Objekt definierte Transformation zusätzlich zu den von anderen Flag-Bits angezeigten -Konvertierungen eine Drehung um einen beliebigen Winkel durchführt. Eine Drehung ändert die Winkel von Vektoren um denselben Betrag , unabhängig von der ursprünglichen Richtung des Vektors und ohne die Länge des Vektors zu ändern. Dieses Flag-Bit schließt sich gegenseitig mit dem aus |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Eine allgemeine Skala multipliziert die Länge von Vektoren mit unterschiedlichen Beträgen in x- und y-Richtung, ohne den Winkel zwischen rechtwinkligen Vektoren zu ändern. Dieses Flag-Bit schließt sich gegenseitig mit dem TypeUniformScale-Flag aus. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Diese Konstante gibt an, dass die durch dieses Objekt definierte Transformation eine willkürliche Konvertierung der Eingabekoordinaten durchführt. Wenn diese Transformation durch eine der oben genannten Konstanten klassifiziert werden kann, ist der Typ entweder die Konstante TypeIdentity oder eine Kombination des entsprechenden Flags Bits für die verschiedenen Koordinaten -Konvertierungen, die diese Transformation durchführt. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Eine Identitätstransformation ist eine, bei der die Ausgabekoordinaten immer die gleichen wie die Eingabekoordinaten sind. Wenn diese Transformation etwas anderes als die Identitätstransformation ist, ist der Typ entweder die Konstante GENERAL_TRANSFORM oder eine Kombination der entsprechenden Flag-Bits für die verschiedenen Koordinaten -Konvertierungen, die diese Transformation durchführt. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Diese Konstante ist eine Bitmaske für eines der Rotations-Flag-Bits. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Diese Konstante ist eine Bitmaske für jedes der Skalierungs-Flag-Bits. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Dieses Flag-Bit zeigt an, dass die durch dieses Objekt definierte Transformation eine Quadrantendrehung um ein Vielfaches von 90 Grad in zusätzlich zu den durch andere Flag-Bits angezeigten Konvertierungen durchführt. Eine Drehung ändert die Winkel von Vektoren unabhängig von der ursprünglichen Richtung um denselben Betrag des Vektors und ohne die Länge des Vektors zu ändern. Dieses Flag-Bit schließt sich gegenseitig mit dem TypeGeneralRotation-Flag aus. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Eine Translation verschiebt die Koordinaten um einen konstanten Betrag in x und y, ohne die Länge oder den Winkel von Vektoren zu ändern. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Eine einheitliche Skalierung multipliziert die Länge der Vektoren mit dem gleichen Betrag in x- und y-Richtung, ohne den Winkel zwischen Vektoren zu ändern. Dieses Flag-Bit schließt sich gegenseitig mit dem TypeGeneralScale-Flag aus. |

### Bemerkungen

Die meisten Algorithmen stammen aus AffineTransform.java von Sun. Intern verwendete Java-Namen für Matrixelemente. Zuordnung von Java-Namen zu .net-Namen zur Beschreibung: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M201 Shear X m01 M201 M201 Y_ m03 Scaled Y_ m03 X übersetzen m12 M32 Y übersetzen

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


