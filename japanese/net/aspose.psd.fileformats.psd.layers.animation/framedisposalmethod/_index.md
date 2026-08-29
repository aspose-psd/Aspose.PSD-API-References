---
title: "列挙型 FrameDisposalMethod"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod 列挙型。フレーム破棄方法は、次のフレームを表示する前に現在のフレームを破棄するかどうかを指定します。背景の透明性を含むアニメーションでは、現在のフレームが次のフレームの透明領域を通して表示されるかどうかを指定するために破棄方法を選択します。"
type: docs
weight: 1950
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

フレーム破棄方法は、次のフレームを表示する前に現在のフレームを破棄するかどうかを指定します。背景の透過を含むアニメーションでは、破棄方法を選択して、現在のフレームが次のフレームの透過領域を通して表示されるかどうかを指定します。

```csharp
public enum FrameDisposalMethod
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Automatic | `0` | 次のフレームにレイヤーの透明性が含まれる場合、現在のフレームを自動的に破棄し、現在のフレームの破棄方法を自動的に決定します。ほとんどのアニメーションでは、Automatic オプション（デフォルト）が期待通りの結果をもたらします。 |
| DoNotDispose | `1` | 次のフレームが表示に追加される間、現在のフレームを保持します。現在のフレーム（および前のフレーム）は、次のフレームの透明領域を通して表示されることがあります。 |
| Dispose | `2` | 次のフレームが表示される前に現在のフレームを表示から破棄します。常に単一のフレームのみが表示され（現在のフレームは次のフレームの透明領域を通して表示されません）。 |

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


