---
title: LayerStateEffects.Effects
second_title: Aspose.PSD for .NET API Reference
description: LayerStateEffects property. Gets the layer effects
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/
---
{{< psd/tize >}}
## LayerStateEffects.Effects property

Gets the layer effects.

```csharp
public ILayerEffect[] Effects { get; }
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

* interface [ILayerEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* assembly [Aspose.PSD](../../../)


