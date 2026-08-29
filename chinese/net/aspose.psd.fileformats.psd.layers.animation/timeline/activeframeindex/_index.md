---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD for .NET API 参考"
description: "Timeline 属性。获取活动帧索引"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

获取活动帧的索引。

```csharp
public int ActiveFrameIndex { get; }
```

## 示例

以下代码演示了使用 Timeline 的新方法。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // 再添加一帧
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### 另请参阅

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


