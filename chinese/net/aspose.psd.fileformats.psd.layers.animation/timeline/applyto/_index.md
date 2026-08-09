---
title: "TimeLine.ApplyTo"
second_title: "Aspose.PSD for .NET API 参考"
description: "TimeLine 方法。将当前时间线值应用于输入 PsdImage"
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

将当前时间线值应用于输入 [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/)。

```csharp
public void ApplyTo(PsdImage psdImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| psdImage | PsdImage | psd 图像。 |

## 示例

TimeLine 类提供了高级功能，可操作 PsdImage 的时间线，例如更改帧延迟或在特定帧上编辑图层状态。

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // 更改帧 1 的处理方式。
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // 更改帧 2 的延迟。
    timeLine.Frames[1].Delay = 15;

    // 更改帧 2 上 'Layer 1' 的不透明度。
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 将 'Layer 1' 移动到帧 3 的左下角。
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // 添加新帧。
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // 更改帧 4 上 'Layer 1' 的 blendMode。
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 将更改应用回 PsdImage 实例。
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### 另请参阅

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


