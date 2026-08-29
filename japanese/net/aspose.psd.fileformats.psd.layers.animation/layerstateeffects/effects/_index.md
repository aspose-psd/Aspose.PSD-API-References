---
title: "LayerStateEffects.Effects"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerStateEffects プロパティ。レイヤー効果を取得します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/
---
{{< psd/tize >}}
## LayerStateEffects.Effects property

レイヤーエフェクトを取得します。

```csharp
public ILayerEffect[] Effects { get; }
```

## 例

次のコードは、Timeline フレームにおけるエフェクトのサポートを示しています。

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

### 関連項目

* interface [ILayerEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


