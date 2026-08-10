---
title: "GradientMapSettings.InterpolationMethod"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti GradientMapSettings. Mendapatkan atau mengatur metode interpolasi untuk gradien"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/interpolationmethod/
---
{{< psd/tize >}}
## GradientMapSettings.InterpolationMethod property

Mendapatkan atau mengatur metode interpolasi untuk gradien.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

## Contoh

Kode berikut menunjukkan dukungan rendering gradien dengan metode Smooth.

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
    // Baca
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Ubah
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Periksa data yang disimpan
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

### Lihat Juga

* enum [InterpolationMethod](../../interpolationmethod/)
* class [GradientMapSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


