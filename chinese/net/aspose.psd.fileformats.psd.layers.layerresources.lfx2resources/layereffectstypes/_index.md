---
title: "枚举 LayerEffectsTypes"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes 枚举。图层混合效果"
type: docs
weight: 2900
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

图层混合效果。

```csharp
public enum LayerEffectsTypes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| DropShadow | `0` | 投影。 |
| OuterGlow | `1` | 外发光。 |
| PatternOverlay | `2` | 图案叠加。 |
| GradientOverlay | `3` | 渐变叠加。 |
| ColorOverlay | `4` | 颜色叠加。 |
| Satin | `5` | 缎面效果类型。 |
| InnerGlow | `6` | 内发光。 |
| InnerShadow | `7` | 内阴影。 |
| Stroke | `8` | 描边。 |
| BevelEmboss | `9` | 斜面浮雕。 |

## 示例

以下代码演示了对 ILayerEffect.EffectType 属性的支持。

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // 已捕获
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assembly [Aspose.PSD](../../)


