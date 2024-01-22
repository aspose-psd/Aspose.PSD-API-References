---
title: Enum GradientType
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientType enum. Gradient type
type: docs
weight: 2070
url: /net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/
---
{{< psd/tize >}}
## GradientType enumeration

Gradient type

```csharp
public enum GradientType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Linear | `0` | The linear gradient type |
| Radial | `1` | The radial gradient type |
| Angle | `2` | The angle gradient type |
| Reflected | `3` | The reflected gradient type |
| Diamond | `4` | The diamond gradient type |
| ShapeBurst | `5` | The shape burst gradient type |

## Examples

The following code save images with different type of gradient and shows how to Aspose.PSD draws the gradient.

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

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


