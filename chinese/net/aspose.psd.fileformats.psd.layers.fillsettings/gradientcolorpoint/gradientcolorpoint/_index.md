---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD for .NET API 参考"
description: "GradientColorPoint 构造函数. 初始化 GradientColorPoint 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

初始化 [`GradientColorPoint`](../) 类的新实例。

```csharp
public GradientColorPoint()
```

### 另请参阅

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

初始化 [`GradientColorPoint`](../) 类的新实例。

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 颜色 | 颜色 | 梯度上的颜色点。 |
| 位置 | Int32 | 渐变上颜色点的位置。 |
| medianPointLocation | Int32 | 中位渐变点的位置。 |

## 示例

以下示例演示如何在图层中创建/编辑 GradientOverlayEffect 效果对象。

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// 在图层中创建/获取并编辑渐变叠加效果。
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // 在图层中搜索 GradientOverlayEffect。
    foreach (ILayerEffect effect in layerBlendOptions.Effects)
    {
        gradientOverlayEffect = effect as GradientOverlayEffect;
        if (gradientOverlayEffect != null)
        {
            break;
        }
    }

    if (gradientOverlayEffect == null)
    {
        // 如果不存在，您可以创建一个新的 GradientOverlayEffect。
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // 为该效果添加一点透明度。
    gradientOverlayEffect.Opacity = 200;

    // 更改渐变效果的混合模式。
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // 获取 GradientFillSettings 对象以配置渐变叠加设置。
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // 设置一个包含两种颜色的新渐变。
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // 将渐变的倾斜角度设置为 80 度。
    settings.Angle = 80;

    // 将渐变效果缩放至最高 150%。
    settings.Scale = 150;

    // 设置渐变的类型。
    settings.GradientType = GradientType.Linear;

    // 通过将每个透明点的不透明度设置为 100%，使渐变不透明。
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### 另请参阅

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


