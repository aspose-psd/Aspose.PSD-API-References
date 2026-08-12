---
title: "Klass TextureBrush"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Brushes.TextureBrush-klass. Varje egenskap i TextureBrush-klassen är ett Brush-objekt som använder en bild för att fylla insidan av en form. Denna klass kan inte ärvas"
type: docs
weight: 210
url: /sv/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

Varje egenskap i `TextureBrush`-klassen är ett [`Brush`](../../aspose.psd/brush/)‑objekt som använder en bild för att fylla insidan av en form. Denna klass kan inte ärvas.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Initierar en ny instans av `TextureBrush`-klassen som använder den angivna bilden. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Initierar en ny instans av `TextureBrush`-klassen som använder den angivna bilden och den avgränsande rektangeln. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Initierar en ny instans av `TextureBrush`-klassen som använder den angivna bilden och den avgränsande rektangeln. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Initierar en ny instans av `TextureBrush`-klassen som använder den angivna bilden och omslagsläget. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Initierar en ny instans av `TextureBrush`-klassen som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Initierar en ny instans av `TextureBrush`-klassen som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Initierar en ny instans av `TextureBrush`-klassen som använder den angivna bilden, omslagsläget och den avgränsande rektangeln. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Initierar en ny instans av `TextureBrush`-klassen som använder den angivna bilden, omslagsläget och den avgränsande rektangeln. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Hämtar [`Image`](../../aspose.psd/image/)-objektet som är associerat med detta `TextureBrush`-objekt. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Hämtar [`ImageAttributes`](./imageattributes/)-objektet som är associerat med detta `TextureBrush`. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Hämtar [`Rectangle`](../../aspose.psd/rectangle/)-objektet som är associerat med detta `TextureBrush`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att sätta transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen infördes för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller anger penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |
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

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


