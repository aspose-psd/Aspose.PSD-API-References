---
title: GradientMapSettings.InterpolationMethod
second_title: Aspose.PSD for .NET API Reference
description: GradientMapSettings property. Gets or sets the interpolation method for the gradient
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/interpolationmethod/
---
{{< psd/tize >}}
## GradientMapSettings.InterpolationMethod property

Gets or sets the interpolation method for the gradient.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

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

* enum [InterpolationMethod](../../interpolationmethod/)
* class [GradientMapSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


