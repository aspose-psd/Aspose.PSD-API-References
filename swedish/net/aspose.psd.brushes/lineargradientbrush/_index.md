---
title: Class LinearGradientBrush
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Brushes.LinearGradientBrush klass. Kapslar in enBrush med en linjär gradient. Denna klass kan inte ärvas.
type: docs
weight: 140
url: /sv/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Kapslar in en[`Brush`](../../aspose.psd/brush/) med en linjär gradient. Denna klass kan inte ärvas.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Initierar en ny instans av`LinearGradientBrush` klass med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Initierar en ny instans av`LinearGradientBrush` klass med de angivna punkterna och färgerna. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Initierar en ny instans av`LinearGradientBrush` klass med de angivna punkterna och färgerna. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Initierar en ny instans av`LinearGradientBrush` klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Initierar en ny instans av`LinearGradientBrush` klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Initierar en ny instans av`LinearGradientBrush` klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Initierar en ny instans av`LinearGradientBrush` klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Hämtar eller ställer in gradientvinkeln. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Hämtar eller sätter en[`Blend`](../../aspose.psd/blend/) som anger positioner och faktorer som definierar en anpassad falloff för gradienten. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Hämtar eller ställer in slutgradientfärgen. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om gammakorrigering är aktiverad för detta[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Hämtar eller ställer in ett värde som anger om[`Angle`](../lineargradientbrushbase/angle/) ändras vid omvandlingar med detta[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Hämtar eller ställer in ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Hämtar eller ställer in startgradientfärgen. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Hämtar eller ställer in en kopia[`Matrix`](../../aspose.psd/matrix/) som definierar en lokal geometrisk transformation för detta[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Hämtar eller sätter en[`WrapMode`](../../aspose.psd/wrapmode/) uppräkning som anger lindningsläget för detta[`TransformBrush`](../transformbrush/) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djup klon av strömmen[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplicerar[`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen av detta`LinearGradientBrush` av den angivna[`Matrix`](../../aspose.psd/matrix/) genom att föregå det angivna[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplicerar[`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen av detta`LinearGradientBrush` av den angivna[`Matrix`](../../aspose.psd/matrix/) i angiven ordning. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Återställer[`Transform`](../transformbrush/transform/) egenskap till identitet. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Roterar den lokala geometriska transformationen med angivet belopp. Denna metod förutsätter rotationen till transformationen. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med angivet belopp i angiven ordning. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skalar den lokala geometriska transformationen med de angivna mängderna. Den här metoden lägger in skalningsmatrisen i transformationen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna mängderna i angiven ordning. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Skapar en linjär gradient med en mittfärg och en linjär nedgång till en enda färg i båda ändar. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Skapar en linjär gradient med en mittfärg och en linjär nedgång till en enda färg i båda ändar. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Skapar en gradientnedgång baserat på en klockformad kurva. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Skapar en gradientnedgång baserat på en klockformad kurva. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Se även

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namnutrymme [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* hopsättning [Aspose.PSD](../../)


