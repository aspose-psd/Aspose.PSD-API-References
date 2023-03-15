---
title: GradientColorPoint.GradientColorPoint
second_title: Aspose.PSD for .NET API 参考
description: GradientColorPoint 构造函数. 初始化一个新的实例GradientColorPoint类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

初始化一个新的实例[`GradientColorPoint`](../)类.

```csharp
public GradientColorPoint()
```

### 也可以看看

* class [GradientColorPoint](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* 部件 [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

初始化一个新的实例[`GradientColorPoint`](../)类.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | Color | 渐变色点。 |
| location | Int32 | 颜色点在渐变上的位置。 |
| medianPointLocation | Int32 | 中值梯度点位置。 |

### 例子

以下示例演示如何在图层中创建/编辑 GradientOverlayEffect 效果对象。

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// 创建/获取和编辑图层中的渐变叠加效果。
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

    // 为效果添加一点透明度。
    gradientOverlayEffect.Opacity = 200;

    // 改变渐变效果的混合模式。
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // 获取 GradientFillSettings 对象以配置渐变叠加设置。
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // 设置具有两种颜色的新渐变。
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // 将渐变的倾角设置为 80 度。
    settings.Angle = 80;

    // 缩放渐变效果高达 150%。
    settings.Scale = 150;

    // 设置渐变类型。
    settings.GradientType = GradientType.Linear;

    // 通过在每个透明点将不透明度设置为 100% 使渐变不透明。
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### 也可以看看

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* 部件 [Aspose.PSD](../../../)


