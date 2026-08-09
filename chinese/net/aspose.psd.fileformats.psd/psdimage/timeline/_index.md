---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 属性。获取此 PsdImage 的时间线"
type: docs
weight: 250
url: /zh/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

获取此 [`PsdImage`](../) 的 `Timeline`。

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


