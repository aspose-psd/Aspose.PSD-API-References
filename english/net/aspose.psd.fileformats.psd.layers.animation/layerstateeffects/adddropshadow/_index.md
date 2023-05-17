---
title: LayerStateEffects.AddDropShadow
second_title: Aspose.PSD for .NET API Reference
description: LayerStateEffects method. Adds the drop shadow effect
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
{{< psd/tize >}}
## LayerStateEffects.AddDropShadow method

Adds the drop shadow effect.

```csharp
public DropShadowEffect AddDropShadow()
```

### Return Value

The new instance of the [`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) class.

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

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* assembly [Aspose.PSD](../../../)


