---
title: "Klass LinearMulticolorGradientBrush"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Brushes.LinearMulticolorGradientBrush-klass. Representerar en pensel med linjär gradient definierad av flera färger och lämpliga positioner. Denna klass kan inte ärvas"
type: docs
weight: 160
url: /sv/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

Representerar en [`Brush`](../../aspose.psd/brush/) med linjär gradient definierad av flera färger och lämpliga positioner. Denna klass kan inte ärvas.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | Initierar en ny instans av klassen `LinearMulticolorGradientBrush` med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | Initierar en ny instans av klassen `LinearMulticolorGradientBrush` med de angivna punkterna. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | Initierar en ny instans av klassen `LinearMulticolorGradientBrush` med de angivna punkterna. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | Initierar en ny instans av klassen `LinearMulticolorGradientBrush` baserat på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | Initierar en ny instans av klassen `LinearMulticolorGradientBrush` baserat på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | Initierar en ny instans av klassen `LinearMulticolorGradientBrush` baserat på en rektangel och en orienteringsvinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | Initierar en ny instans av klassen `LinearMulticolorGradientBrush` baserat på en rektangel och en orienteringsvinkel. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Hämtar eller anger gradientvinkeln. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Hämtar eller anger ett värde som indikerar om gamma‑korrigering är aktiverad för denna [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | Hämtar eller anger en [`ColorBlend`](../../aspose.psd/colorblend/) som definierar ett flerfärgslinjärt gradient. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Hämtar eller anger ett värde som indikerar om [`Angle`](../lineargradientbrushbase/angle/) ändras under transformationer med denna [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att sätta transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen infördes för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller anger penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Hämtar eller anger ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Hämtar eller anger en kopia av [`Matrix`](../../aspose.psd/matrix/) som definierar en lokal geometrisk transformation för denna [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Hämtar eller anger en [`WrapMode`](../../aspose.psd/wrapmode/)‑enumeration som indikerar omslagsläget för denna [`TransformBrush`](../transformbrush/). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djupklon av den aktuella [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplicerar den [`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [`LinearGradientBrush`](../lineargradientbrush/) med den angivna [`Matrix`](../../aspose.psd/matrix/) genom att föra in den angivna [`Matrix`](../../aspose.psd/matrix/) i början. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplicerar den [`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [`LinearGradientBrush`](../lineargradientbrush/) med den angivna [`Matrix`](../../aspose.psd/matrix/) i den angivna ordningen. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Återställer egenskapen [`Transform`](../transformbrush/transform/) till identitet. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Roterar den lokala geometriska transformationen med den angivna mängden. Denna metod lägger rotationen först i transformationen. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod lägger till skalningsmatrisen först i transformationen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till translationen först i transformationen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |

### Se även

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


