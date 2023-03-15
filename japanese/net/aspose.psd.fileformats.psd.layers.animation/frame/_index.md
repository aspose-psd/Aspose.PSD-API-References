---
title: Class Frame
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame クラス. タイムラインフレーム項目のオプション.
type: docs
weight: 1840
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

タイムラインフレーム項目のオプション.

```csharp
public sealed class Frame
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Frame](frame/)(TimeLine) | の新しいインスタンスを初期化します`Frame`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | フレーム遅延値をセント秒単位で取得または設定します。 たとえば、1 秒には 100 セント秒が含まれます。 |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | フレームの破棄方法を取得または設定します。 |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | フレーム ID を取得または設定します。 |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | フレームのレイヤー状態を取得または設定します。 |

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


