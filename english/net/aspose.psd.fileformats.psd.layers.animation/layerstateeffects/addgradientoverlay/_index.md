---
title: LayerStateEffects.AddGradientOverlay
second_title: Aspose.PSD for .NET API Reference
description: LayerStateEffects method. Adds the gradient overlay effect
type: docs
weight: 50
url: /net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddGradientOverlay method

Adds the gradient overlay effect.

```csharp
public GradientOverlayEffect AddGradientOverlay()
```

### Return Value

The new instance of the [`GradientOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) class.

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

* class [GradientOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


