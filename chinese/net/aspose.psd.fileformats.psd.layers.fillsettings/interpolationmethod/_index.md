---
title: "枚举 InterpolationMethod"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod 枚举。用于 Photoshop 渐变插值方法的打包 fourCC 值。描述符键 gradientsInterpolationMethod"
type: docs
weight: 2160
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Photoshop 渐变插值方法的打包 fourCC 值。描述符键："gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Classic | `1197698163` | ‘Gcls’ — 经典（键缺失时的旧默认）。 |
| Perceptual | `1348825699` | ‘Perc’ — 感知。 |
| Linear | `1282306592` | ‘Lnr ’ — 线性（注意尾随空格）。 |
| Smooth | `1399680879` | ‘Smoo’ — 平滑。 |
| Stripes | `1195986291` | ‘GIMs’ — 条纹。 |

## 示例

以下代码演示了使用 Smooth 方法的渐变渲染支持。

```csharp
[C#]

string sourceFile = "GradientOverlay.psd";
string outputFile = "output_GradientOverlay.psd";
string outputFilePng = "output_GradientOverlay.png";

var srcMethod = InterpolationMethod.Linear;
var newMethod = InterpolationMethod.Smooth;

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var image = (PsdImage)Image.Load(sourceFile, opt))
{
    // 读取
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // 更改
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// 检查已保存的数据
using (var image = (PsdImage)Image.Load(outputFile, opt))
{
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;

    AssertAreEqual(newMethod, gradientSettings.InterpolationMethod);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


