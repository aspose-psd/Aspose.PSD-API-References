---
title: LayerStateEffects.Effects
second_title: Aspose.PSD for .NET API リファレンス
description: LayerStateEffects 財産. レイヤー効果を取得します
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/
---
## LayerStateEffects.Effects property

レイヤー効果を取得します。

```csharp
public ILayerEffect[] Effects { get; }
```

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

* interface [ILayerEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/)
* class [LayerStateEffects](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* 組み立て [Aspose.PSD](../../../)


