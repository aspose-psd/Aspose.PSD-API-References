---
title: LayerStateEffects.AddOuterGlow
second_title: Aspose.PSD for .NET API Reference
description: LayerStateEffects method. Adds the outer glow effect
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/
---
{{< psd/tize >}}
## LayerStateEffects.AddOuterGlow method

Adds the outer glow effect.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Return Value

The new instance of the [`OuterGlowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) class.

## Examples

The following code demonstrates support of effects in Timeline frames.

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

### See Also

* class [OuterGlowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* assembly [Aspose.PSD](../../../)


