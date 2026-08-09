---
title: "Timeline.Frames"
second_title: "Aspose.PSD for .NET API 参考"
description: "Timeline 属性。获取帧列表"
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/timeline/frames/
---
{{< psd/tize >}}
## Timeline.Frames property

获取帧列表。

```csharp
public Frame[] Frames { get; set; }
```

## 示例

Timeline 类提供了高级功能来操作 PsdImage 的时间轴，例如更改帧延迟或在特定帧上编辑图层状态。

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // 更改帧 1 的处理方式。
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // 更改帧 2 的延迟。
    timeline.Frames[1].Delay = 15;

    // 更改帧 2 上 'Layer 1' 的不透明度。
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // 将 'Layer 1' 移动到帧 3 的左下角。
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // 添加新帧。
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // 更改帧 4 上 'Layer 1' 的 blendMode。
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 将更改应用回 PsdImage 实例。
    psdImage.Save(outputPsd);
}
```

### 另请参阅

* class [Frame](../../frame/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


