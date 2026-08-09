---
title: "枚举 RenderQuality"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality 枚举。 它描述了 Warp 的渲染质量"
type: docs
weight: 3990
url: /zh/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

它描述了变形的渲染质量。

```csharp
public enum RenderQuality
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Turbo | `4` | 最快的选项，但质量受影响。 |
| VeryFast | `18` | 如果您需要快速处理，它可能适用于小幅度曲线。 |
| Fast | `35` | 允许您在质量略有下降的情况下加快渲染速度。 |
| Normal | `60` | 大多数曲线的推荐值 |
| Good | `130` | 高于标准质量，速度较慢。 推荐用于强烈的畸变。 |
| Excellent | `260` | 最慢的选项。 推荐用于强烈的畸变和高分辨率。 |

## 示例

以下代码演示使用 WarpSettings.RenderQuality 属性配置扭曲变形。

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // 它从智能图层获取 WarpSettings
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // 它设置扭曲处理区域的大小
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // 这里不应出现错误
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


