---
title: "类 LayerState"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState 类。时间线图层状态的选项"
type: docs
weight: 1960
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

时间线图层状态的选项。

```csharp
public sealed class LayerState
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LayerState](layerstate/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | 获取或设置混合模式。 |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | 获取或设置启用状态。 |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | 获取或设置填充不透明度值。 |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | 获取或设置 HorizontalFXRf 值。 |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | 获取或设置图层 ID。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | 获取或设置不透明度值。 |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | 获取或设置相对于实际图层位置的图层位置偏移。 |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | 获取图层状态效果。 |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | 获取或设置 VerticalFXRf 值。 |

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


