---
title: Class LinearMulticolorGradientBrush
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Brushes.LinearMulticolorGradientBrush klas. Vertegenwoordigt eenBrush met lineair verloop gedefinieerd door meerdere kleuren en geschikte posities. Deze klasse kan niet worden geërfd.
type: docs
weight: 160
url: /nl/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

Vertegenwoordigt een[`Brush`](../../aspose.psd/brush/) met lineair verloop gedefinieerd door meerdere kleuren en geschikte posities. Deze klasse kan niet worden geërfd.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | Initialiseert een nieuw exemplaar van het`LinearMulticolorGradientBrush` klasse met standaardparameters. De beginkleur is zwart, de eindkleur is wit, de hoek is 45 graden en de rechthoek bevindt zich in (0,0) met grootte (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | Initialiseert een nieuw exemplaar van het`LinearMulticolorGradientBrush` klasse met de opgegeven punten. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | Initialiseert een nieuw exemplaar van het`LinearMulticolorGradientBrush` klasse met de opgegeven punten. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | Initialiseert een nieuw exemplaar van het`LinearMulticolorGradientBrush` klasse gebaseerd op een rechthoek en een oriëntatiehoek. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | Initialiseert een nieuw exemplaar van het`LinearMulticolorGradientBrush` klasse gebaseerd op een rechthoek en een oriëntatiehoek. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | Initialiseert een nieuw exemplaar van het`LinearMulticolorGradientBrush` klasse gebaseerd op een rechthoek en een oriëntatiehoek. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | Initialiseert een nieuw exemplaar van het`LinearMulticolorGradientBrush` klasse gebaseerd op een rechthoek en een oriëntatiehoek. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Haalt of stelt de hellingshoek in. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Krijgt of stelt een waarde in die aangeeft of hiervoor gammacorrectie is ingeschakeld[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | Haalt of zet a[`ColorBlend`](../../aspose.psd/colorblend/) dat definieert een veelkleurig lineair verloop. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Haalt of stelt een waarde in die aangeeft of[`Angle`](../lineargradientbrushbase/angle/) wordt hiermee gewijzigd tijdens transformaties[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Krijgt een waarde die aangeeft of transformaties op een of andere manier zijn gewijzigd. Bijvoorbeeld het instellen van de transformatiematrix of het aanroepen van een van de methoden die de transformatiematrix wijzigen. De eigenschap is geïntroduceerd voor achterwaartse compatibiliteit met GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hiermee wordt de dekking van het penseel opgehaald of ingesteld. De waarde moet tussen 0 en 1 liggen. De waarde 0 betekent dat het penseel volledig zichtbaar is, de waarde 1 betekent dat het penseel volledig dekkend is. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Hiermee wordt een rechthoekig gebied opgehaald of ingesteld dat de begin- en eindpunten van het verloop definieert. |
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

### Zie ook

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* naamruimte [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* montage [Aspose.PSD](../../)


