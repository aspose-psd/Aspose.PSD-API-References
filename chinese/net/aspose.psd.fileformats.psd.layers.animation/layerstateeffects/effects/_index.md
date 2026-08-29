---
title: "LayerStateEffects.Effects"
second_title: "Aspose.PSD for .NET API 参考"
description: "LayerStateEffects 属性。获取图层效果"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/
---
{{< psd/tize >}}
## LayerStateEffects.Effects property

获取图层效果。

```csharp
public ILayerEffect[] Effects { get; }
```

## 示例

以下代码演示了在 Timeline 帧中对效果的支持。

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

### 另请参阅

* interface [ILayerEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


