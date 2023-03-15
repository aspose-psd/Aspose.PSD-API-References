---
title: LayerStateEffects.AddStroke
second_title: Aspose.PSD for .NET API リファレンス
description: LayerStateEffects 方法. ストローク効果を追加します
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
## LayerStateEffects.AddStroke method

ストローク効果を追加します。

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fillType | FillType | タイプ ストローク フィル。 |

### 戻り値

の新しいインスタンス[`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)クラス。

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* 組み立て [Aspose.PSD](../../../)


