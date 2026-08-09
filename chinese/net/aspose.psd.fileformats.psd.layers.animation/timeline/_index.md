---
title: "类 Timeline"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline 类。时间线选项模型"
type: docs
weight: 1980
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

时间线选项模型。

```csharp
public sealed class Timeline
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Timeline](timeline/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | 获取活动帧的索引。 |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | 获取或设置 AFSt 值。 |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | 获取帧列表。 |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | 获取或设置 FsID 值。 |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | 获取或设置循环次数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | 根据保存选项，将 PsdImage 和 Timeline 数据保存到指定流的指定格式中。 |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | 根据保存选项，将 PsdImage 和 Timeline 数据保存到指定文件位置的指定格式中。 |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | 将活动帧切换到目标帧。 |

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


