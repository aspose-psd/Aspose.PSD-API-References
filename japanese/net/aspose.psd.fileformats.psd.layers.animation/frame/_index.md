---
title: "クラス Frame"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame クラス。タイムラインフレーム項目のオプション"
type: docs
weight: 1940
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
{{< psd/tize >}}
## Frame class

タイムラインフレーム項目のオプションです。

```csharp
public sealed class Frame
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Frame](frame/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | フレーム遅延値をセンタ秒で取得または設定します。たとえば、1 秒は 100 センタ秒です。 |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | フレームの破棄方法を取得または設定します。 |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | フレーム ID を取得または設定します。 |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; set; } | フレームのレイヤー状態を取得または設定します。 |

## 例

Timeline クラスは、PsdImage のタイムラインを操作する高度な機能を提供します。たとえば、フレーム遅延の変更や特定フレームでのレイヤー状態の編集などです。

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // フレーム 1 の破棄方法を変更します
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // フレーム 2 の遅延を変更します
    timeline.Frames[1].Delay = 15;

    // フレーム 2 の 'Layer 1' の不透明度を変更します
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // フレーム 3 で 'Layer 1' を左下隅に移動します
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // 新しいフレームを追加します
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // フレーム 4 の 'Layer 1' の blendMode を変更します
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 変更を PsdImage インスタンスに適用します
    psdImage.Save(outputPsd);
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


