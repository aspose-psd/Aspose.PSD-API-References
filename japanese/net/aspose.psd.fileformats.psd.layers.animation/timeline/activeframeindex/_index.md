---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD for .NET API Reference"
description: "Timeline プロパティ。アクティブフレームインデックスを取得します"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

アクティブフレームのインデックスを取得します。

```csharp
public int ActiveFrameIndex { get; }
```

## 例

以下のコードは Timeline を使用する新しいアプローチを示しています。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // フレームをもう1つ追加する
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### 関連項目

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


