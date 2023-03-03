---
title: Class LayerStateEffects
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerStateEffects クラス. レイヤー状態の効果.
type: docs
weight: 1870
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---
## LayerStateEffects class

レイヤー状態の効果.

```csharp
public class LayerStateEffects
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/) { get; } | レイヤー効果を取得します。 |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/isvisible/) { get; set; } | このインスタンスが表示されるかどうかを示す値を取得または設定します. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/)() | カラー オーバーレイ効果を追加します。 |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/)() | ドロップ シャドウ効果を追加します。 |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/)() | グラデーション オーバーレイ効果を追加します。 |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/)() | インナー シャドウ効果を追加します。 |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/)() | 外側のグロー効果を追加します。 |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/)() | パターン オーバーレイ効果を追加します。 |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/)(FillType) | ストローク効果を追加します。 |
| [ClearLayerStyle](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/clearlayerstyle/)() | すべてのレイヤー スタイル効果をクリアします。 |
| [RemoveEffectAt](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/removeeffectat/)(int) | 特定のインデックスでレイヤー効果を削除します. |

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

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* 組み立て [Aspose.PSD](../../)


