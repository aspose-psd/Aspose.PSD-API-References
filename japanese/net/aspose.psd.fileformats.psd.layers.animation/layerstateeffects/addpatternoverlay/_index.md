---
title: "LayerStateEffects.AddPatternOverlay"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerStateEffects メソッド。パターンオーバーレイ効果を追加します"
type: docs
weight: 80
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddPatternOverlay method

パターンオーバーレイ効果を追加します。

```csharp
public PatternOverlayEffect AddPatternOverlay()
```

### 戻り値

新しいインスタンスは [`PatternOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) クラスです。

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

* class [PatternOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


