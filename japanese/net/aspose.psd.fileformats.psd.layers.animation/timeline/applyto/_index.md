---
title: "TimeLine.ApplyTo"
second_title: "Aspose.PSD for .NET API Reference"
description: "TimeLine メソッド。現在のタイムライン値を入力された PsdImage に適用します"
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

入力された [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/) に現在のタイムライン値を適用します。

```csharp
public void ApplyTo(PsdImage psdImage)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| psdImage | PsdImage | psd 画像です。 |

## 例

TimeLine クラスは、PsdImage のタイムラインを操作する高度な機能を提供します。たとえば、フレーム遅延の変更や特定フレームのレイヤー状態の編集などが可能です。

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // フレーム 1 の破棄方法を変更します
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // フレーム 2 の遅延を変更します
    timeLine.Frames[1].Delay = 15;

    // フレーム 2 の 'Layer 1' の不透明度を変更します
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // フレーム 3 で 'Layer 1' を左下隅に移動します
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // 新しいフレームを追加します
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // フレーム 4 の 'Layer 1' の blendMode を変更します
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


