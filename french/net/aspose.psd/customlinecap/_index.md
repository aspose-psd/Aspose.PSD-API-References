---
title: "Classe CustomLineCap"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.CustomLineCap classe. Encapsule un bouchon de ligne personnalisé défini par l'utilisateur."
type: docs
weight: 710
url: /fr/net/aspose.psd/customlinecap/
---
{{< psd/tize >}}
## CustomLineCap class

Encapsule un bouchon de ligne personnalisé défini par l'utilisateur.

```csharp
public class CustomLineCap
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | Initialise une nouvelle instance de la classe `CustomLineCap` avec le contour et le remplissage spécifiés. |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | Initialise une nouvelle instance de la classe `CustomLineCap` à partir de l'énumération existante [`LineCap`](../linecap/) spécifiée, avec le contour et le remplissage spécifiés. |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | Initialise une nouvelle instance de la classe `CustomLineCap` à partir de l'énumération existante [`LineCap`](../linecap/) spécifiée, avec le contour, le remplissage et l'encoche spécifiés. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BaseCap](../../aspose.psd/customlinecap/basecap/) { get; set; } | Obtient ou définit l'énumération [`LineCap`](../linecap/) sur laquelle cette `CustomLineCap` est basée. |
| [BaseInset](../../aspose.psd/customlinecap/baseinset/) { get; set; } | Obtient ou définit la distance entre le bouchon et la ligne. |
| [FillPath](../../aspose.psd/customlinecap/fillpath/) { get; set; } | Obtient ou définit l'objet qui définit le remplissage du bouchon personnalisé. |
| [StrokeJoin](../../aspose.psd/customlinecap/strokejoin/) { get; set; } | Obtient ou définit l'énumération [`LineJoin`](../linejoin/) qui détermine comment les lignes qui composent cet objet `CustomLineCap` sont jointes. |
| [StrokePath](../../aspose.psd/customlinecap/strokepath/) { get; set; } | Obtient ou définit l'objet qui définit le contour du bouchon personnalisé. |
| [WidthScale](../../aspose.psd/customlinecap/widthscale/) { get; set; } | Obtient ou définit la quantité par laquelle mettre à l'échelle cet objet `CustomLineCap` Classe par rapport à la largeur de l'objet Pen. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetStrokeCaps](../../aspose.psd/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | Obtient les bouchons utilisés pour commencer et terminer les lignes qui composent ce bouchon personnalisé. |
| [SetStrokeCaps](../../aspose.psd/customlinecap/setstrokecaps/)(LineCap, LineCap) | Définit les bouchons utilisés pour commencer et terminer les lignes qui composent ce bouchon personnalisé. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


