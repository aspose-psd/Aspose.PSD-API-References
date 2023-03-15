---
title: Class LinearGradientBrushBase
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Brushes.LinearGradientBrushBase klass. Representerar enBrush med gradientfunktioner och lämpliga egenskaper.
type: docs
weight: 150
url: /sv/net/aspose.psd.brushes/lineargradientbrushbase/
---
## LinearGradientBrushBase class

Representerar en[`Brush`](../../aspose.psd/brush/) med gradientfunktioner och lämpliga egenskaper.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Hämtar eller ställer in gradientvinkeln. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om gammakorrigering är aktiverad för detta`LinearGradientBrushBase` . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Hämtar eller ställer in ett värde som anger om[`Angle`](./angle/) ändras vid omvandlingar med detta`LinearGradientBrushBase` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Hämtar eller ställer in ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Hämtar eller ställer in en kopia[`Matrix`](../../aspose.psd/matrix/) som definierar en lokal geometrisk transformation för detta[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Hämtar eller sätter en[`WrapMode`](../../aspose.psd/wrapmode/) uppräkning som anger lindningsläget för detta[`TransformBrush`](../transformbrush/) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djup klon av strömmen[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplicerar[`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen av detta[`LinearGradientBrush`](../lineargradientbrush/) av den angivna[`Matrix`](../../aspose.psd/matrix/) genom att föregå det angivna[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplicerar[`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen av detta[`LinearGradientBrush`](../lineargradientbrush/) av den angivna[`Matrix`](../../aspose.psd/matrix/) i angiven ordning. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Återställer[`Transform`](../transformbrush/transform/) egenskap till identitet. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Roterar den lokala geometriska transformationen med angivet belopp. Denna metod förutsätter rotationen till transformationen. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med angivet belopp i angiven ordning. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skalar den lokala geometriska transformationen med de angivna mängderna. Den här metoden lägger in skalningsmatrisen i transformationen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna mängderna i angiven ordning. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Se även

* class [TransformBrush](../transformbrush/)
* namnutrymme [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* hopsättning [Aspose.PSD](../../)


