---
title: "LayerStateEffects.Effects"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LayerStateEffects özelliği. Katman efektlerini alır"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/
---
{{< psd/tize >}}
## LayerStateEffects.Effects property

Katman efektlerini alır.

```csharp
public ILayerEffect[] Effects { get; }
```

## Örnekler

Aşağıdaki kod, Timeline çerçevelerindeki efekt desteğini gösterir.

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

### Ayrıca Bakınız

* interface [ILayerEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


