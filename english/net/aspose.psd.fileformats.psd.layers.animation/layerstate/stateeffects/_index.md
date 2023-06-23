---
title: LayerState.StateEffects
second_title: Aspose.PSD for .NET API Reference
description: LayerState property. Gets the layer state effects
type: docs
weight: 90
url: /net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
{{< psd/tize >}}
## LayerState.StateEffects property

Gets the layer state effects.

```csharp
public LayerStateEffects StateEffects { get; }
```

## Examples

The following code demonstrates support of effects in Timeline frames.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### See Also

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


