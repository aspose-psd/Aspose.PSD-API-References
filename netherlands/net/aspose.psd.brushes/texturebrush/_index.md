---
title: Class TextureBrush
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Brushes.TextureBrush klas. Elke eigenschap van deTextureBrush klas is eenBrush object dat een afbeelding gebruikt om de binnenkant van een vorm te vullen. Deze klasse kan niet worden geërfd.
type: docs
weight: 210
url: /nl/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Elke eigenschap van de`TextureBrush` klas is een[`Brush`](../../aspose.psd/brush/) object dat een afbeelding gebruikt om de binnenkant van een vorm te vullen. Deze klasse kan niet worden geërfd.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Initialiseert een nieuw exemplaar van het`TextureBrush` klasse die de opgegeven afbeelding gebruikt. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Initialiseert een nieuw exemplaar van het`TextureBrush` klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Initialiseert een nieuw exemplaar van het`TextureBrush` klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Initialiseert een nieuw exemplaar van het`TextureBrush` klasse die de opgegeven afbeelding en wrap-modus gebruikt. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Initialiseert een nieuw exemplaar van het`TextureBrush` klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingsattributen gebruikt. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Initialiseert een nieuw exemplaar van het`TextureBrush` klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingsattributen gebruikt. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Initialiseert een nieuw exemplaar van het`TextureBrush`klasse die de opgegeven afbeelding, omloopmodus en omsluitende rechthoek gebruikt. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Initialiseert een nieuw exemplaar van het`TextureBrush`klasse die de opgegeven afbeelding, omloopmodus en omsluitende rechthoek gebruikt. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Krijgt de[`Image`](../../aspose.psd/image/) object dat hiermee verband houdt`TextureBrush` object. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Krijgt de[`ImageAttributes`](./imageattributes/) hiermee in verband gebracht`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Krijgt de[`Rectangle`](../../aspose.psd/rectangle/) hiermee in verband gebracht`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Krijgt een waarde die aangeeft of transformaties op een of andere manier zijn gewijzigd. Bijvoorbeeld het instellen van de transformatiematrix of het aanroepen van een van de methoden die de transformatiematrix wijzigen. De eigenschap is geïntroduceerd voor achterwaartse compatibiliteit met GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hiermee wordt de dekking van het penseel opgehaald of ingesteld. De waarde moet tussen 0 en 1 liggen. De waarde 0 betekent dat het penseel volledig zichtbaar is, de waarde 1 betekent dat het penseel volledig dekkend is. |
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

* class [TransformBrush](../transformbrush/)
* naamruimte [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* montage [Aspose.PSD](../../)


