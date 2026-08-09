---
title: "Classe BezierShape"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Shapes.BezierShape. Représente une courbe de Bézier"
type: docs
weight: 5970
url: /fr/net/aspose.psd.shapes/beziershape/
---
{{< psd/tize >}}
## BezierShape class

Représente une spline de Bézier.

```csharp
public sealed class BezierShape : PolygonShape
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BezierShape](beziershape/#constructor)() | Initialise une nouvelle instance de la classe `BezierShape`. |
| [BezierShape](beziershape/#constructor_1)(PointF[]) | Initialise une nouvelle instance de la classe `BezierShape`. |
| [BezierShape](beziershape/#constructor_2)(PointF[], bool) | Initialise une nouvelle instance de la classe `BezierShape`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/beziershape/bounds/) { get; } | Obtient les limites de l'objet. |
| override [Center](../../aspose.psd.shapes/beziershape/center/) { get; } | Obtient le centre de la forme. |
| override [EndPoint](../../aspose.psd.shapes/beziershape/endpoint/) { get; } | Obtient le point final de la forme. |
| override [HasSegments](../../aspose.psd.shapes/beziershape/hassegments/) { get; } | Obtient une valeur indiquant si la forme possède des segments. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Obtient ou définit une valeur indiquant si la forme est fermée. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Obtient ou définit les points de la courbe. |
| override [Segments](../../aspose.psd.shapes/beziershape/segments/) { get; } | Obtient les segments de la forme. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Obtient le point de départ de la forme. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/beziershape/getbounds/#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd.shapes/beziershape/getbounds/#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Inverse l'ordre des points pour cette forme. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |

### Voir aussi

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


