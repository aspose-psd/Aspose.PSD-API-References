---
title: "LayerStateEffects.AddColorOverlay"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerStateEffects メソッド。カラーオーバーレイ効果を追加します"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddColorOverlay method

カラーオーバーレイ効果を追加します。

```csharp
public ColorOverlayEffect AddColorOverlay()
```

### 戻り値

新しいインスタンスの[`ColorOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/)クラスです。

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

* class [ColorOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


