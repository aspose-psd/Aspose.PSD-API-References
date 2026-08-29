---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerStateEffects メソッド。ストローク効果を追加します"
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

ストローク効果を追加します。

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillType | FillType | タイプはstroke fillです。 |

### 戻り値

新しいインスタンスの[`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)クラスです。

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


