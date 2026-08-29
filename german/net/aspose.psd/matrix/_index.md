---
title: "Klasse Matrix"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Matrix-Klasse. Ersetzt die GDI-Matrix"
type: docs
weight: 5580
url: /de/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

Ersetzt die GDI+ Matrix.

```csharp
public class Matrix
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Matrix](matrix/#constructor)() | Initialisiert eine neue Instanz der Matrix-Klasse als Einheitsmatrix. |
| [Matrix](matrix/#constructor_1)(Matrix) | Erstellt eine Kopie der `Matrix`-Klasse. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Initialisiert eine neue Instanz der `Matrix`-Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punktarray definiert ist. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Initialisiert eine neue Instanz der `Matrix`-Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Punktarray definiert ist. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Initialisiert eine neue Instanz der `Matrix`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Gibt ein Array von Gleitkommawerten zurück, das die Elemente dieser `Matrix` darstellt. |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Liefert das Matrix-Element in der ersten Zeile, ersten Spalte. Stellt die Skalierung entlang der X-Achse dar. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Liefert das Matrix-Element in der ersten Zeile, zweiten Spalte. Stellt die Scherung entlang der Y-Achse dar. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Liefert das Matrix-Element in der zweiten Zeile, ersten Spalte. Stellt die Scherung entlang der X-Achse dar. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Liefert das Matrix-Element in der zweiten Zeile, zweiten Spalte. Stellt die Skalierung entlang der Y-Achse dar. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Liefert das Matrix-Element in der dritten Zeile, ersten Spalte. Stellt die Translation entlang der X-Achse dar. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Liefert das Matrix-Element in der dritten Zeile, ersten Spalte. Stellt die Translation entlang der Y-Achse dar. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Bestimmt, ob das angegebene Objekt gleich dieser Instanz ist. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Gibt eine Kopie der Matrix-Elemente zurück. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Multipliziert diese Matrix mit der im Parameter matrix angegebenen Matrix und in der im Parameter order angegebenen Reihenfolge. |
| [Reset](../../aspose.psd/matrix/reset/)() | Setzt diese Matrix zurück, sodass sie die Elemente der Einheitsmatrix enthält. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Wendet eine im Winkel‑Parameter angegebene Drehung im Uhrzeigersinn um den Ursprung (Null‑x‑ und y‑Koordinaten) für diese Matrix in der Standard‑(Prepend‑)Reihenfolge an. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Wendet eine im Winkel‑Parameter angegebene Drehung im Uhrzeigersinn um den Ursprung (Null‑x‑ und y‑Koordinaten) für diese Matrix in der angegebenen Reihenfolge an. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der Standard‑(Prepend‑)Reihenfolge an. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Wendet eine Drehung im Uhrzeigersinn um den angegebenen Punkt auf diese Matrix in der angegebenen Reihenfolge an. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese Matrix unter Verwendung der (Standard‑)Prepend‑Reihenfolge an. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Wendet den angegebenen Skalierungsvektor (scaleX und scaleY) auf diese `Matrix` unter Verwendung der angegebenen Reihenfolge an. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Wendet die von dieser `Matrix` dargestellte geometrische Transformation auf ein angegebenes Punktarray an. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Wendet den angegebenen Translationsvektor auf diese `Matrix` unter Verwendung der (Standard‑)Prepend‑Reihenfolge an. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Wendet den angegebenen Translationsvektor auf diese Matrix in der angegebenen Reihenfolge an. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Bestimmt, ob zwei Matrizen gleich sind. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Dieses Flag‑Bit gibt an, dass die von diesem Objekt definierte Transformation eine Spiegelbild‑Umkehr um eine Achse durchführt, die das normalerweise rechtshändige Koordinatensystem in ein linkshändiges System ändert, zusätzlich zu den von anderen Flag‑Bits angegebenen Umwandlungen. Ein rechtshändiges Koordinatensystem ist eines, bei dem die positive X‑Achse gegen den Uhrzeigersinn rotiert, um die positive Y‑Achse zu überlagern, ähnlich der Richtung, in die sich die Finger Ihrer rechten Hand krümmen, wenn Sie Ihren Daumen frontal betrachten. Ein linkshändiges Koordinatensystem ist eines, bei dem die positive X‑Achse im Uhrzeigersinn rotiert, um die positive Y‑Achse zu überlagern, ähnlich der Richtung, in die sich die Finger Ihrer linken Hand krümmen. Es gibt keinen mathematischen Weg, den Winkel der ursprünglichen Umkehr‑ oder Spiegelungs‑Transformation zu bestimmen, da alle Umkehrwinkel identisch sind, wenn eine geeignete nachjustierende Rotation angewendet wird. HINWEIS: TypeFlip wurde hinzugefügt, nachdem GENERAL_TRANSFORM bereits öffentlich verbreitet war, und die Flag‑Bits konnten nicht mehr bequem neu nummeriert werden, ohne binäre Inkompatibilität in externem Code einzuführen. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Dieses Flag‑Bit gibt an, dass die von diesem Objekt definierte Transformation eine Rotation um einen beliebigen Winkel durchführt, zusätzlich zu den von anderen Flag‑Bits angegebenen Umwandlungen. Eine Rotation ändert die Winkel von Vektoren um denselben Betrag, unabhängig von der ursprünglichen Richtung des Vektors, und ohne die Länge des Vektors zu verändern. Dieses Flag‑Bit ist wechselseitig exklusiv mit dem |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Eine allgemeine Skalierung multipliziert die Länge von Vektoren in x‑ und y‑Richtung um unterschiedliche Beträge, ohne den Winkel zwischen senkrechten Vektoren zu ändern. Dieses Flag‑Bit ist wechselseitig exklusiv mit dem TypeUniformScale‑Flag. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Diese Konstante gibt an, dass die von diesem Objekt definierte Transformation eine beliebige Umwandlung der Eingabekoordinaten durchführt. Wenn diese Transformation durch eine der oben genannten Konstanten klassifiziert werden kann, ist der Typ entweder die Konstante TypeIdentity oder eine Kombination der entsprechenden Flag‑Bits für die verschiedenen Koordinatenumwandlungen, die diese Transformation ausführt. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Eine Identitätstransformation ist eine, bei der die Ausgabekoordinaten stets mit den Eingabekoordinaten übereinstimmen. Wenn diese Transformation etwas anderes als die Identitätstransformation ist, wird der Typ entweder die Konstante GENERAL_TRANSFORM oder eine Kombination der entsprechenden Flag‑Bits für die verschiedenen Koordinatenumwandlungen sein, die diese Transformation ausführt. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Diese Konstante ist eine Bitmaske für beliebige Rotations‑Flag‑Bits. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Diese Konstante ist eine Bitmaske für beliebige Skalierungs‑Flag‑Bits. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Dieses Flag‑Bit gibt an, dass die von diesem Objekt definierte Transformation eine Quadrant‑Rotation um ein Vielfaches von 90 Grad durchführt, zusätzlich zu den von anderen Flag‑Bits angegebenen Umwandlungen. Eine Rotation ändert die Winkel von Vektoren um denselben Betrag, unabhängig von der ursprünglichen Richtung des Vektors, und ohne die Länge des Vektors zu verändern. Dieses Flag‑Bit ist wechselseitig exklusiv mit dem TypeGeneralRotation‑Flag. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Eine Translation verschiebt die Koordinaten um einen konstanten Betrag in x und y, ohne die Länge oder den Winkel von Vektoren zu ändern. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Eine einheitliche Skalierung multipliziert die Länge von Vektoren um denselben Betrag in sowohl der x‑ als auch der y‑Richtung, ohne den Winkel zwischen den Vektoren zu ändern. Dieses Flag‑Bit ist wechselseitig exklusiv zum Flag TypeGeneralScale. |

## Hinweise

Die meisten Algorithmen stammen aus Sun's AffineTransform.java. Java‑Namen für Matrix‑Elemente werden intern verwendet. Zuordnung von Java‑Namen zu .net‑Namen mit Beschreibung: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y m02 M31 Translate X m12 M32 Translate Y

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


