---
title: "Klass PathGradientBrush"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Brushes.PathGradientBrush-klass. Inkapslar ett Brush-objekt med en gradient. Denna klass kan inte ärvas."
type: docs
weight: 170
url: /sv/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

Inkapslar ett [`Brush`](../../aspose.psd/brush/)‑objekt med en gradient. Denna klass kan inte ärvas.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Initierar en ny instans av klassen `PathGradientBrush` med den angivna sökvägen. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna och omslagsläget. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Initierar en ny instans av klassen `PathGradientBrush` med de angivna punkterna och omslagsläget. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Hämtar eller anger en [`Blend`](../../aspose.psd/blend/) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Hämtar eller anger färgen i mitten av sökvägsgradienten. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Hämtar eller anger centrumpunkten för bangradienten. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Hämtar eller anger fokuspunkten för gradientens avtagande. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Hämtar grafikbanan som denna pensel byggdes på. |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | Hämtar eller anger en [`ColorBlend`](../../aspose.psd/colorblend/) som definierar ett flerfärgslinjärt gradient. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att sätta transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen infördes för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller anger penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Hämtar banpunkterna som denna pensel byggdes på. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Hämtar eller anger en array av färger som motsvarar punkterna i den sökväg som denna `PathGradientBrush` fyller. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Skapar en gradient med en mittfärg och ett linjärt avtagande till en omgivande färg. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Skapar en gradient med en mittfärg och ett linjärt avtagande till varje omgivande färg. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Skapar en gradientpensel som ändrar färg från mitten av sökvägen utåt till sökvägens gräns. Övergången från en färg till en annan baseras på en klockformad kurva. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Skapar en gradientpensel som ändrar färg från mitten av sökvägen utåt till sökvägens gräns. Övergången från en färg till en annan baseras på en klockformad kurva. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till translationen först i transformationen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |

## Anmärkningar

Centerfärgen är vit som standard. En användare kan ändra detta värde när som helst senare.

Omringningsfärgerna initieras med ett enda element som innehåller vit färg som standard. Omringningsfärgerna kan ändras senare, men minst ett element krävs när omringningsfärgerna ställs in.

Se [`Blend`](./blend/) för mer detaljer om dess initiering.

### Se även

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


