---
title: "Enum InterpolationMethod"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod enum. Photoshop gradyan ara değerleme yöntemi için paketlenmiş fourCC değerleri. Tanımlayıcı anahtar gradientsInterpolationMethod"
type: docs
weight: 2160
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Photoshop gradyan ara değerleme yöntemi için paketlenmiş fourCC değerleri. Tanımlayıcı anahtar: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Klasik (anahtar yoksa eski varsayılan). |
| Perceptual | `1348825699` | 'Perc' — Algısal. |
| Linear | `1282306592` | 'Lnr ' — Doğrusal (sondaki boşluğa dikkat edin). |
| Smooth | `1399680879` | 'Smoo' — Pürüzsüz. |
| Stripes | `1195986291` | 'GIMs' — Çizgili. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


