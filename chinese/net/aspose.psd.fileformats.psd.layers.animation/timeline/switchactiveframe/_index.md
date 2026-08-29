---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD for .NET API 参考"
description: "Timeline 方法。将活动帧切换到目标帧"
type: docs
weight: 80
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

将活动帧切换到目标帧。

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | 目标帧索引。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IndexOutOfRangeException | 活动帧的新索引应在帧计数范围内。 |

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


