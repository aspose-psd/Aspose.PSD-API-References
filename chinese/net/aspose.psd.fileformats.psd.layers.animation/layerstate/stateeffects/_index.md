---
title: LayerState.StateEffects
second_title: Aspose.PSD for .NET API 参考
description: LayerState 财产. 获取图层状态效果
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

获取图层状态效果。

```csharp
public LayerStateEffects StateEffects { get; }
```

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

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* 部件 [Aspose.PSD](../../../)


