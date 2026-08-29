---
title: "枚举 FrameDisposalMethod"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod 枚举。帧处理方法指定在显示下一帧之前是否丢弃当前帧。对于包含背景透明度的动画，您可以选择处理方法，以指定当前帧是否会在下一帧的透明区域中可见。"
type: docs
weight: 1950
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

帧处置方法指定是否在显示下一帧之前丢弃当前帧。对于包含背景透明度的动画，您可以选择处置方法，以指定当前帧是否会通过下一帧的透明区域可见。

```csharp
public enum FrameDisposalMethod
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Automatic | `0` | 自动确定当前帧的处理方法，如果下一帧包含图层透明度则丢弃当前帧。对于大多数动画，自动选项（默认）可获得期望的结果。 |
| DoNotDispose | `1` | 在将下一帧添加到显示时保留当前帧。当前帧（以及之前的帧）可能会透过下一帧的透明区域显示。 |
| Dispose | `2` | 在显示下一帧之前从显示中丢弃当前帧。任意时刻仅显示单帧（当前帧不会透过下一帧的透明区域出现）。 |

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


