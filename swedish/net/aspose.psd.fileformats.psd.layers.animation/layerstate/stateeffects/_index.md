---
title: "LayerState.StateEffects"
second_title: "Aspose.PSD för .NET API‑referens"
description: "LayerState-egenskap. Hämtar lagerstatusens effekter"
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
{{< psd/tize >}}
## LayerState.StateEffects property

Hämtar lagrets tillståndseffekter.

```csharp
public LayerStateEffects StateEffects { get; }
```

## Exempel

Följande kod demonstrerar stöd för effekter i Timeline-ramar.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### Se även

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


