---
title: Class TimeLine
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine クラス. タイムライン オプション モデル.
type: docs
weight: 1880
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

タイムライン オプション モデル.

```csharp
public sealed class TimeLine
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TimeLine](timeline/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | アクティブ フレーム インデックスを取得または設定します。 |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | AFSt 値を取得または設定します。 |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | フレームのリストを取得します。 |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | FsID 値を取得または設定します。 |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | レイヤー ID 配列を取得または設定します。 |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | ループの回数を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | の新しいインスタンスを作成します`TimeLine`、入力から初期化[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | 現在のタイムライン値を入力に適用[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

### 例

TimeLine クラスは、フレーム遅延の変更や特定のフレームのレイヤー状態の編集など、PsdImage のタイムラインを操作する高度な機能を提供します。

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // フレーム 1 の dispose メソッドを変更
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // フレーム 2 の遅延を変更
    timeLine.Frames[1].Delay = 15;

    // フレーム 2 の「レイヤー 1」の不透明度を変更
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 'Layer 1' をフレーム 3 の左下隅に移動します
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // 新しいフレームを追加
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // フレーム 4 で「レイヤー 1」のblendMode を変更
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 変更を PsdImage インスタンスに適用します
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* 組み立て [Aspose.PSD](../../)


