---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdImage プロパティ。この PsdImage の Timeline を取得します"
type: docs
weight: 250
url: /ja/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

この [`PsdImage`](../) の `Timeline` を取得します。

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


