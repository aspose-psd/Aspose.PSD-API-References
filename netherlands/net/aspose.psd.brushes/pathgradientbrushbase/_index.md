---
title: Class PathGradientBrushBase
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Brushes.PathGradientBrushBase klas. Vertegenwoordigt eenBrush met basispadverloopfunctionaliteit.
type: docs
weight: 180
url: /nl/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Vertegenwoordigt een[`Brush`](../../aspose.psd/brush/) met basispadverloopfunctionaliteit.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Haalt of stelt het middelpunt van de padgradiënt in. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Haalt of stelt het focuspunt in voor de gradiëntdaling. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Krijgt het grafische pad waarop dit penseel is gebouwd. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Krijgt een waarde die aangeeft of transformaties op een of andere manier zijn gewijzigd. Bijvoorbeeld het instellen van de transformatiematrix of het aanroepen van een van de methoden die de transformatiematrix wijzigen. De eigenschap is geïntroduceerd voor achterwaartse compatibiliteit met GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hiermee wordt de dekking van het penseel opgehaald of ingesteld. De waarde moet tussen 0 en 1 liggen. De waarde 0 betekent dat het penseel volledig zichtbaar is, de waarde 1 betekent dat het penseel volledig dekkend is. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Krijgt de padpunten waarop dit penseel is gebouwd. |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Vertaalt de lokale geometrische transformatie door de opgegeven dimensies. Deze methode voegt de vertaling toe aan de transformatie. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Vertaalt de lokale geometrische transformatie door de opgegeven dimensies in de opgegeven volgorde. |

### Opmerkingen

Houd er rekening mee dat bij het maken van de`PathGradientBrushBase` class moet het worden geïnitialiseerd met minimaal 2 punten. Het interne pad created zal altijd een gesloten figuur zijn, het laatste punt verbindt het eerste punt. Die vorm is hiermee gevuld`PathGradientBrushBase`. De GDI+-implementatie genereert eenOutOfMemoryException bij het passeren van lege arrays of puntenset met dezelfde coördinaten. The`PathGradientBrushBase` genereert een uitzondering wanneer de puntenreeks minder dan 2 punten bevat, deArgumentException is gegooid in plaats vanOutOfMemoryException wanneer puntenarray onaanvaardbaar is. Het middelpunt wordt standaard berekend als massamiddelpunt voor de doorgegeven punten. Een gebruiker kan dit punt later wijzigen. De focusschaal is standaard een leeg punt (0.0, 0.0).

### Zie ook

* class [TransformBrush](../transformbrush/)
* naamruimte [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* montage [Aspose.PSD](../../)


