---
title: TimeLine.InitializeFrom
second_title: Aspose.PSD for .NET API リファレンス
description: TimeLine 方法. の新しいインスタンスを作成しますTimeLine入力から初期化PsdImage .
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/
---
## TimeLine.InitializeFrom method

の新しいインスタンスを作成します[`TimeLine`](../)、入力から初期化[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/) .

```csharp
public static TimeLine InitializeFrom(PsdImage psdImage)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| psdImage | PsdImage | psd画像です。 |

### 戻り値

の新しいインスタンス[`TimeLine`](../)、入力から初期化[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

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

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* 組み立て [Aspose.PSD](../../../)


