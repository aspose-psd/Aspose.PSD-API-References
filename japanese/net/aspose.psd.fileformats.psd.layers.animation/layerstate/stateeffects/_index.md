---
title: LayerState.StateEffects
second_title: Aspose.PSD for .NET API リファレンス
description: LayerState 財産. レイヤー状態の効果を取得します
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

レイヤー状態の効果を取得します。

```csharp
public LayerStateEffects StateEffects { get; }
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

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* 組み立て [Aspose.PSD](../../../)


