---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD for .NET API 参考
description: GradientFillSettings 财产. 获取或设置渐变的类型
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

获取或设置渐变的类型。

```csharp
public GradientType GradientType { get; set; }
```

### 适当的价值

渐变的类型。

### 例子

下面的代码保存了不同类型渐变的图像，并展示了如何在 Aspose.PSD 中绘制渐变。

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 也可以看看

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* 部件 [Aspose.PSD](../../../)


