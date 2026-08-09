---
title: "Classe CurveShape"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Shapes.CurveShape. Représente une forme de spline courbée"
type: docs
weight: 5980
url: /fr/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

Représente une forme de spline courbée.

```csharp
public sealed class CurveShape : PolygonShape
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Initialise une nouvelle instance de la classe `CurveShape`. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Initialise une nouvelle instance de la classe `CurveShape`. La tension par défaut de 0,5 est utilisée. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Initialise une nouvelle instance de la classe `CurveShape`. La tension par défaut de 0,5 est utilisée. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Initialise une nouvelle instance de la classe `CurveShape`. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Initialise une nouvelle instance de la classe `CurveShape`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Obtient les limites de l'objet. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Obtient le centre de la forme. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Obtient le point final de la forme. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Obtient une valeur indiquant si la forme possède des segments. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Obtient ou définit une valeur indiquant si la forme est fermée. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Obtient ou définit les points de la courbe. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Obtient les segments de la forme. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Obtient le point de départ de la forme. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Obtient ou définit la tension de la courbe. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Inverse l'ordre des points pour cette forme. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |

### Voir aussi

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


