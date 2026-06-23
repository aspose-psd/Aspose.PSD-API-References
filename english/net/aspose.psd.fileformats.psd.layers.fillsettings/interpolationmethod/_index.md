---
title: Enum InterpolationMethod
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod enum. Packed fourCC values for Photoshop gradient interpolation method. Descriptor key gradientsInterpolationMethod
type: docs
weight: 2160
url: /net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Packed fourCC values for Photoshop gradient interpolation method. Descriptor key: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Classic (legacy default when key is absent). |
| Perceptual | `1348825699` | 'Perc' — Perceptual. |
| Linear | `1282306592` | 'Lnr ' — Linear (note trailing space). |
| Smooth | `1399680879` | 'Smoo' — Smooth. |
| Stripes | `1195986291` | 'GIMs' — Stripes. |

## Examples

The following code demonstrates the support of gradient rendering with Smooth method.

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
    // Read
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Change
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Check saved data
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

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


