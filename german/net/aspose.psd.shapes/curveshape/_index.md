---
title: "Klasse CurveShape"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Shapes.CurveShape Klasse. Stellt eine gekrümmte Spline-Form dar."
type: docs
weight: 5980
url: /de/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

Stellt eine gekrümmte Spline-Form dar.

```csharp
public sealed class CurveShape : PolygonShape
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Initialisiert eine neue Instanz der `CurveShape` Klasse. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Initialisiert eine neue Instanz der `CurveShape` Klasse. Die Standardspannung von 0,5 wird verwendet. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Initialisiert eine neue Instanz der `CurveShape` Klasse. Die Standardspannung von 0,5 wird verwendet. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Initialisiert eine neue Instanz der `CurveShape` Klasse. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Initialisiert eine neue Instanz der `CurveShape` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Liest die Begrenzungen des Objekts. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Liest das Zentrum der Form. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Liest den Endpunkt der Form. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Liest einen Wert, der angibt, ob die Form Segmente hat. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, ob die Form geschlossen ist. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Ruft die Kurvenpunkte ab oder legt sie fest. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Liest die Segmente der Form. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Ruft den Startpunkt der Form ab. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Ruft die Kurvenspannung ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Liest die Begrenzungen des Objekts. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Liest die Begrenzungen des Objekts. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Wendet die angegebene Transformation auf die Form an. |

### Siehe auch

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


