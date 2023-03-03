---
title: TimeLine.ApplyTo
second_title: Aspose.PSD for .NET API 参考
description: TimeLine 方法. 将当前时间线值应用于输入PsdImage .
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
## TimeLine.ApplyTo method

将当前时间线值应用于输入[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/) .

```csharp
public void ApplyTo(PsdImage psdImage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| psdImage | PsdImage | psd图像。 |

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

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* 部件 [Aspose.PSD](../../../)


