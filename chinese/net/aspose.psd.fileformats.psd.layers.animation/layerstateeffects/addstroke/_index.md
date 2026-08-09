---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD for .NET API 参考"
description: "LayerStateEffects 方法。添加描边效果"
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

添加描边效果。

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillType | FillType | 类型描边填充。 |

### 返回值

新的 [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) 类的实例。

## 示例

以下代码演示了在 Timeline 帧中对效果的支持。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### 另请参阅

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


