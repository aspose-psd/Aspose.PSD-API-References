---
title: "IGradientFillSettings.InterpolationMethod"
second_title: "Aspose.PSD for .NET API Referansı"
description: "IGradientFillSettings özelliği. Gradyan için ara değerleme yöntemini alır veya ayarlar"
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/
---
{{< psd/tize >}}
## IGradientFillSettings.InterpolationMethod property

Degrade için ara değerleme yöntemini alır veya ayarlar.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

## Örnekler

Aşağıdaki kod, Smooth yöntemiyle degrade renderleme desteğini gösterir.

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
    // Oku
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Değiştir
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Kaydedilen verileri kontrol et
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

### Ayrıca Bakınız

* enum [InterpolationMethod](../../interpolationmethod/)
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


