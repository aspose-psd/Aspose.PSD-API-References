---
title: LayerStateEffects.AddInnerShadow
second_title: Aspose.PSD for .NET API リファレンス
description: LayerStateEffects 方法. インナー シャドウ効果を追加します
type: docs
weight: 60
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/
---
## LayerStateEffects.AddInnerShadow method

インナー シャドウ効果を追加します。

```csharp
public InnerShadowEffect AddInnerShadow()
```

### 戻り値

の新しいインスタンス[`InnerShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/)クラス。

### 例

次のコードは、タイムライン フレームでの効果のサポートを示しています。

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

### 関連項目

* class [InnerShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/)
* class [LayerStateEffects](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* 組み立て [Aspose.PSD](../../../)


