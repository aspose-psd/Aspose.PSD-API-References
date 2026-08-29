---
title: "Klass LinearGradientBrush"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Brushes.LinearGradientBrush-klass. Inkapslar en Brush med en linjär gradient. Denna klass kan inte ärvas"
type: docs
weight: 140
url: /sv/net/aspose.psd.brushes/lineargradientbrush/
---
{{< psd/tize >}}
## LinearGradientBrush class

Inkapslar en [`Brush`](../../aspose.psd/brush/) med en linjär gradient. Denna klass kan inte ärvas.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Initierar en ny instans av `LinearGradientBrush`‑klassen med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storleken (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Initierar en ny instans av klassen `LinearGradientBrush` med de angivna punkterna och färgerna. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Initierar en ny instans av klassen `LinearGradientBrush` med de angivna punkterna och färgerna. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Initierar en ny instans av klassen `LinearGradientBrush` baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Initierar en ny instans av klassen `LinearGradientBrush` baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Initierar en ny instans av klassen `LinearGradientBrush` baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Initierar en ny instans av klassen `LinearGradientBrush` baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Hämtar eller anger gradientvinkeln. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Hämtar eller anger en [`Blend`](../../aspose.psd/blend/) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Hämtar eller anger den avslutande gradientfärgen. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Hämtar eller anger ett värde som indikerar om gamma‑korrigering är aktiverad för denna [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/lineargradientbrush/interpolationcolors/) { get; set; } | Hämtar eller anger en [`ColorBlend`](../../aspose.psd/colorblend/) som definierar ett flerfärgslinjärt gradient. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Hämtar eller anger ett värde som indikerar om [`Angle`](../lineargradientbrushbase/angle/) ändras under transformationer med denna [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att sätta transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen infördes för bakåtkompatibilitet med GDI+. |
| [LinearColors](../../aspose.psd.brushes/lineargradientbrush/linearcolors/) { get; set; } | Hämtar eller anger start- och slutfärgerna för gradienten. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller anger penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Hämtar eller anger ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Hämtar eller anger den startande gradientfärgen. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Hämtar eller anger en kopia av [`Matrix`](../../aspose.psd/matrix/) som definierar en lokal geometrisk transformation för denna [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Hämtar eller anger en [`WrapMode`](../../aspose.psd/wrapmode/)‑enumeration som indikerar omslagsläget för denna [`TransformBrush`](../transformbrush/). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djupklon av den aktuella [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplicerar den [`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformen för denna `LinearGradientBrush` med den angivna [`Matrix`](../../aspose.psd/matrix/) genom att föregå den angivna [`Matrix`](../../aspose.psd/matrix/). |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplicerar den [`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformen för denna `LinearGradientBrush` med den angivna [`Matrix`](../../aspose.psd/matrix/) i den angivna ordningen. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Återställer egenskapen [`Transform`](../transformbrush/transform/) till identitet. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Roterar den lokala geometriska transformationen med den angivna mängden. Denna metod lägger rotationen först i transformationen. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod lägger till skalningsmatrisen först i transformationen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till translationen först i transformationen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |

### Se även

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


