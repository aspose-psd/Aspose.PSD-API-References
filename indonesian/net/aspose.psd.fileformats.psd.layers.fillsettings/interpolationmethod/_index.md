---
title: "Enum InterpolationMethod"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod. Nilai fourCC yang dipaketkan untuk metode interpolasi gradien Photoshop. Kunci deskriptor gradientsInterpolationMethod"
type: docs
weight: 2160
url: /id/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Nilai fourCC terpaket untuk metode interpolasi gradien Photoshop. Kunci deskriptor: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Klasik (default warisan ketika kunci tidak ada). |
| Perceptual | `1348825699` | 'Perc' — Perseptual. |
| Linear | `1282306592` | 'Lnr ' — Linear (catatan spasi di akhir). |
| Smooth | `1399680879` | 'Smoo' — Halus. |
| Stripes | `1195986291` | 'GIMs' — Garis-garis. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


