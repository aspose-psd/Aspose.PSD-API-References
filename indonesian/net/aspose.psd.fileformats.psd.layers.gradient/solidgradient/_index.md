---
title: "Class SolidGradient"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Gradient.SolidGradient class. Pengaturan efek isi gradien"
type: docs
weight: 2230
url: /id/net/aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---
{{< psd/tize >}}
## SolidGradient class

Pengaturan efek isi gradien.

```csharp
public class SolidGradient : BaseGradient
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SolidGradient](solidgradient/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/colorpoints/) { get; set; } | Mendapatkan atau mengatur titik warna. |
| override [GradientMode](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/gradientmode/) { get; } | Mendapatkan mode untuk gradien ini. Menentukan 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.gradient/basegradient/gradientname/) { get; set; } | Mendapatkan atau mengatur nama gradien. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/interpolation/) { get; set; } | Mendapatkan atau mengatur Interpolasi. Menentukan Kelancaran, ketika 'Gradient Type' = 'Solid'. Rentang nilai: 0-4096. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/transparencypoints/) { get; set; } | Mendapatkan atau mengatur titik transparansi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/addcolorpoint/)() | Menambahkan titik warna. |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/addtransparencypoint/)() | Menambahkan titik warna. |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/removecolorpoint/)(IGradientColorPoint) | Menghapus titik warna. |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/removetransparencypoint/)(IGradientTransparencyPoint) | Menghapus titik transparansi. |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/generatelfx2resourcenodes/)() | Menghasilkan node sumber daya LFX2. |

## Contoh

Menunjukkan cara membaca dan memodifikasi pengaturan gradien noise dan solid dalam efek isi goresan.

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Periksa properti pengaturan isi gradien umum
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // Periksa properti gradien Noise
    NoiseGradient noiseGradient = gradientFillSettings.Gradient as NoiseGradient;
    AssertIsNotNull(noiseGradient);
    AssertAreEqual(GradientKind.Noise, noiseGradient.GradientMode);
    AssertAreEqual(2107422935, noiseGradient.RndNumberSeed);
    AssertAreEqual(false, noiseGradient.ShowTransparency);
    AssertAreEqual(false, noiseGradient.UseVectorColor);
    AssertAreEqual(2048, noiseGradient.Roughness);
    AssertAreEqual(NoiseColorModel.RGB, noiseGradient.ColorModel);
    AssertAreEqual((long)0, noiseGradient.MinimumColor.GetAsLong());
    AssertAreEqual(28147819798528050, noiseGradient.MaximumColor.GetAsLong());

    // Ubah pengaturan gradien
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Dither = false;
    gradientFillSettings.Reverse = false;
    gradientFillSettings.Angle = 30;
    gradientFillSettings.Scale = 80;
    gradientFillSettings.GradientType = GradientType.Linear;

    var solidGradient = new SolidGradient();
    solidGradient.Interpolation = 2048;
    solidGradient.ColorPoints[0].RawColor.Components[0].Value = 255; // A
    solidGradient.ColorPoints[0].RawColor.Components[1].Value = 255; // R 
    solidGradient.ColorPoints[0].RawColor.Components[2].Value = 0;   // G
    solidGradient.ColorPoints[0].RawColor.Components[3].Value = 0;   // B
    solidGradient.TransparencyPoints[1].Opacity = 50;
    gradientFillSettings.Gradient = solidGradient;

    image.Save(outputFile);
}

// Periksa perubahan yang disimpan
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Periksa properti pengaturan isi gradien umum
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(false, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(false, gradientFillSettings.Dither);
    AssertAreEqual(false, gradientFillSettings.Reverse);
    AssertAreEqual(30.0, gradientFillSettings.Angle);
    AssertAreEqual(80, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Linear, gradientFillSettings.GradientType);

    SolidGradient solidGradient = gradientFillSettings.Gradient as SolidGradient;
    AssertIsNotNull(solidGradient);
    AssertAreEqual((short)2048, solidGradient.Interpolation);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[0].Value);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[1].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[2].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[3].Value);
    AssertAreEqual(50.0, solidGradient.TransparencyPoints[1].Opacity);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### Lihat Juga

* class [BaseGradient](../basegradient/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../)


