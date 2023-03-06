---
title: Class PathGradientBrush
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Brushes.PathGradientBrush klas. Kapselt eenBrush object met een verloop. Deze klasse kan niet worden geërfd.
type: docs
weight: 170
url: /nl/net/aspose.psd.brushes/pathgradientbrush/
---
## PathGradientBrush class

Kapselt een[`Brush`](../../aspose.psd/brush/) object met een verloop. Deze klasse kan niet worden geërfd.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Initialiseert een nieuw exemplaar van het`PathGradientBrush` klasse met het opgegeven pad. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Initialiseert een nieuw exemplaar van het`PathGradientBrush` klasse met de opgegeven punten. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Initialiseert een nieuw exemplaar van het`PathGradientBrush` klasse met de opgegeven punten. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Initialiseert een nieuw exemplaar van het`PathGradientBrush` class met de gespecificeerde punten en wrap mode. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Initialiseert een nieuw exemplaar van het`PathGradientBrush` class met de gespecificeerde punten en wrap mode. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Haalt of zet a[`Blend`](../../aspose.psd/blend/) die posities en factoren specificeert die een aangepaste afname voor het verloop definiëren. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Hiermee wordt de kleur in het midden van het padverloop opgehaald of ingesteld. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Haalt of stelt het middelpunt van de padgradiënt in. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Haalt of stelt het focuspunt in voor de gradiëntdaling. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Krijgt het grafische pad waarop dit penseel is gebouwd. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Krijgt een waarde die aangeeft of transformaties op een of andere manier zijn gewijzigd. Bijvoorbeeld het instellen van de transformatiematrix of het aanroepen van een van de methoden die de transformatiematrix wijzigen. De eigenschap is geïntroduceerd voor achterwaartse compatibiliteit met GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hiermee wordt de dekking van het penseel opgehaald of ingesteld. De waarde moet tussen 0 en 1 liggen. De waarde 0 betekent dat het penseel volledig zichtbaar is, de waarde 1 betekent dat het penseel volledig dekkend is. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Krijgt de padpunten waarop dit penseel is gebouwd. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Hiermee wordt een reeks kleuren opgehaald of ingesteld die overeenkomen met de punten in het pad dit`PathGradientBrush` vullingen. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Haalt of stelt een kopie in[`Matrix`](../../aspose.psd/matrix/) die hiervoor een lokale geometrische transformatie definieert[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Haalt of zet a[`WrapMode`](../../aspose.psd/wrapmode/) opsomming die de wrap-modus hiervoor aangeeft[`TransformBrush`](../transformbrush/) . |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Maakt een nieuwe diepe kloon van de huidige[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Vermenigvuldigt de[`Matrix`](../../aspose.psd/matrix/) dat vertegenwoordigt de lokale geometrische transformatie hiervan[`LinearGradientBrush`](../lineargradientbrush/) door de opgegeven[`Matrix`](../../aspose.psd/matrix/) door het gespecificeerde vooraf te gaan[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Vermenigvuldigt de[`Matrix`](../../aspose.psd/matrix/) dat vertegenwoordigt de lokale geometrische transformatie hiervan[`LinearGradientBrush`](../lineargradientbrush/) door de opgegeven[`Matrix`](../../aspose.psd/matrix/) in de opgegeven volgorde. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Reset de[`Transform`](../transformbrush/transform/) eigendom tot identiteit. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Roteert de lokale geometrische transformatie met de gespecificeerde hoeveelheid. Deze methode voegt de rotatie toe aan de transformatie. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Schaalt de lokale geometrische transformatie met de gespecificeerde hoeveelheden. Deze methode voegt de schaalmatrix toe aan de transformatie. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Maakt een verloop met een middenkleur en een lineair verloop naar één omringende kleur. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Creëert een verloop met een middenkleur en een lineair verloop naar elke omringende kleur. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Maakt een verlooppenseel dat van kleur verandert vanaf het midden van het pad naar de rand van het pad. De overgang van de ene kleur naar de andere is gebaseerd op een klokvormige curve. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Maakt een verlooppenseel dat van kleur verandert vanaf het midden van het pad naar de rand van het pad. De overgang van de ene kleur naar de andere is gebaseerd op een klokvormige curve. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Vertaalt de lokale geometrische transformatie door de opgegeven dimensies. Deze methode voegt de vertaling toe aan de transformatie. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Vertaalt de lokale geometrische transformatie door de opgegeven dimensies in de opgegeven volgorde. |

### Opmerkingen

De middenkleur is standaard wit. Een gebruiker kan deze waarde op elk moment later wijzigen.

De array met surroundkleuren wordt standaard geïnitialiseerd door een enkel element met witte kleur. De surroundkleuren kunnen later worden gewijzigd, maar er is minimaal één element vereist bij het instellen van de surroundkleuren.

Zie de[`Blend`](./blend/) voor meer informatie over de initialisatie.

### Zie ook

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* naamruimte [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* montage [Aspose.PSD](../../)


