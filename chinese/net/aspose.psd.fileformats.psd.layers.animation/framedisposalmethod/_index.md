---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod 枚举. 帧处理方法指定是否在显示下一帧之前丢弃当前帧 您为包含背景透明度的动画选择处理方法以指定当前 帧是否通过下一帧的透明区域可见
type: docs
weight: 1850
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

帧处理方法指定是否在显示下一帧之前丢弃当前帧。 您为包含背景透明度的动画选择处理方法以指定当前 帧是否通过下一帧的透明区域可见。

```csharp
public enum FrameDisposalMethod
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Automatic | `0` | 自动确定当前帧的处理方法，如果下一帧包含图层透明度，则丢弃当前帧。 对于大多数动画，自动选项（默认）会产生所需的结果。 |
| DoNotDispose | `1` | 在将下一帧添加到显示器时保留当前帧。 当前帧（和之前的帧）可能会通过下一帧的透明区域显示。 |
| Dispose | `2` | 在显示下一帧之前从显示器中丢弃当前帧。 任何时候都只显示一个帧（并且当前帧不会通过下一帧的透明区域出现）。 |

### 例子

TimeLine 类提供了操作 PsdImage 时间轴的高级能力，例如更改帧延迟或编辑特定帧上的图层状态。

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // 改变 frame 1 的 dispose 方法
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // 改变第 2 帧的延迟
    timeLine.Frames[1].Delay = 15;

    // 改变第 2 帧“第 1 层”的不透明度
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 将“Layer 1”移动到第 3 帧的左下角
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // 添加新框架
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // 在第 4 帧上更改“Layer 1”的混合模式
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 将更改应用回 PsdImage 实例
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* 部件 [Aspose.PSD](../../)


