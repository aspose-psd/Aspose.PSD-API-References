---
title: "Frame.LayerStates"
second_title: "Aspose.PSD for .NET API Reference"
description: "Frame プロパティ。フレームのレイヤー状態を取得または設定します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/frame/layerstates/
---
{{< psd/tize >}}
## Frame.LayerStates property

フレームのレイヤー状態を取得または設定します。

```csharp
public LayerState[] LayerStates { get; set; }
```

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

* class [LayerState](../../layerstate/)
* class [Frame](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


