---
title: Class LayerState
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState 班级. 时间线图层状态选项
type: docs
weight: 1860
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

时间线图层状态选项。

```csharp
public sealed class LayerState
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LayerState](layerstate/)(int) | 初始化一个新的实例`LayerState`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | 获取或设置 blen 模式。 |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | 获取或设置启用状态。 |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | 获取或设置填充不透明度值。 |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | 获取或设置 HorizontalFXRf 值。 |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | 获取或设置 id. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | 获取或设置不透明度值。 |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | 获取或设置与实际图层位置相关的图层位置偏移。 |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | 获取图层状态效果。 |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | 获取或设置 VerticalFXRf 值。 |

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


