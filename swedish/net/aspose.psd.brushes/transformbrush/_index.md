---
title: "Klass TransformBrush"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Brushes.TransformBrush-klass. En Brush med transformeringsegenskaper"
type: docs
weight: 220
url: /sv/net/aspose.psd.brushes/transformbrush/
---
{{< psd/tize >}}
## TransformBrush class

En [`Brush`](../../aspose.psd/brush/) med transformeringsegenskaper.

```csharp
public abstract class TransformBrush : Brush
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att sätta transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen infördes för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller anger penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Hämtar eller anger en kopia av [`Matrix`](../../aspose.psd/matrix/) som definierar en lokal geometrisk transformation för detta `TransformBrush`. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Hämtar eller anger en [`WrapMode`](../../aspose.psd/wrapmode/)‑enumeration som indikerar omslagsläget för detta `TransformBrush`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djupklon av den aktuella [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | Multiplicerar den [`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [`LinearGradientBrush`](../lineargradientbrush/) med den angivna [`Matrix`](../../aspose.psd/matrix/) genom att föra in den angivna [`Matrix`](../../aspose.psd/matrix/) i början. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplicerar den [`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [`LinearGradientBrush`](../lineargradientbrush/) med den angivna [`Matrix`](../../aspose.psd/matrix/) i den angivna ordningen. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Återställer egenskapen [`Transform`](./transform/) till identitet. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Roterar den lokala geometriska transformationen med den angivna mängden. Denna metod lägger rotationen först i transformationen. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod lägger till skalningsmatrisen först i transformationen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till translationen först i transformationen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |

### Se även

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


