---
title: "类 Frame"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame 类。时间线帧项的选项"
type: docs
weight: 1940
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
{{< psd/tize >}}
## Frame class

时间线帧项的选项。

```csharp
public sealed class Frame
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Frame](frame/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | 获取或设置帧延迟值（单位为百分秒）。例如，1 秒包含 100 百分秒。 |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | 获取或设置帧的处理方式。 |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | 获取或设置帧 ID。 |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; set; } | 获取或设置帧的图层状态。 |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


