---
title: LayerStateEffects.AddStroke
second_title: Aspose.PSD for .NET API 参考
description: LayerStateEffects 方法. 添加描边效果
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
## LayerStateEffects.AddStroke method

添加描边效果。

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fillType | FillType | 类型描边填充。 |

### 返回值

的新实例[`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)班级。

### 例子

以下代码演示了对时间轴帧中效果的支持。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### 也可以看看

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* 部件 [Aspose.PSD](../../../)


