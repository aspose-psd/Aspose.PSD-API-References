---
title: "Kelas GradientOverlayEffect"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.GradientOverlayEffect. Efek Lapisan Gradien"
type: docs
weight: 2320
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/
---
{{< psd/tize >}}
## GradientOverlayEffect class

Efek lapisan Gradient.

```csharp
public class GradientOverlayEffect : ILayerEffect
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/blendmode/) { get; set; } | Mendapatkan atau mengatur mode perpaduan. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/effecttype/) { get; } | Mendapatkan tipe efek |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/isvisible/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terlihat. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas. |
| [Settings](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/settings/) { get; set; } | Mendapatkan atau mengatur pengaturan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/geteffectbounds/)(Rectangle, int) | Menghitung dan mendapatkan batas piksel efek berdasarkan batas piksel lapisan masukan. |

## Contoh

Kode berikut menunjukkan dukungan efek overlay gradien.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}
void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "GradientOverlay.psd";
string exportPath = "GradientOverlayChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var gradientOverlay = (GradientOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, gradientOverlay.BlendMode);
    AssertAreEqual((byte)255, gradientOverlay.Opacity);
    AssertAreEqual(true, gradientOverlay.IsVisible);

    var settings = (GradientFillSettings)gradientOverlay.Settings;
    var solidGradient = (SolidGradient)gradientOverlay.Settings.Gradient;
    AssertAreEqual(Color.Empty, solidGradient.Color);
    AssertAreEqual(FillType.Gradient, settings.FillType);
    AssertAreEqual(true, settings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, settings.GradientType);
    AssertIsTrue(Math.Abs(33 - settings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, settings.Dither);
    AssertIsTrue(Math.Abs(129 - settings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(156 - settings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, settings.Reverse);

    // Titik Warna
    var colorPoints = solidGradient.ColorPoints;
    AssertAreEqual(3, colorPoints.Length);

    AssertAreEqual(Color.FromArgb(9, 0, 178), colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.Red, colorPoints[1].Color);
    AssertAreEqual(2048, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    AssertAreEqual(Color.FromArgb(255, 252, 0), colorPoints[2].Color);
    AssertAreEqual(4096, colorPoints[2].Location);
    AssertAreEqual(50, colorPoints[2].MedianPointLocation);

    // Titik Transparansi
    var transparencyPoints = solidGradient.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Uji penyuntingan
    solidGradient.Color = Color.Green;

    gradientOverlay.Opacity = 193;
    gradientOverlay.BlendMode = BlendMode.Lighten;

    settings.AlignWithLayer = false;
    settings.GradientType = GradientType.Radial;
    settings.Angle = 45;
    settings.Dither = true;
    settings.HorizontalOffset = 15;
    settings.VerticalOffset = 11;
    settings.Reverse = true;

    // Tambahkan titik warna baru
    var colorPoint = solidGradient.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Ubah lokasi titik sebelumnya
    solidGradient.ColorPoints[2].Location = 3000;

    // Tambahkan titik transparansi baru
    var transparencyPoint = solidGradient.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Ubah lokasi titik transparansi sebelumnya
    solidGradient.TransparencyPoints[1].Location = 2315;
    im.Save(exportPath);
}

// File uji setelah edit
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientOverlay = (GradientOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Lighten, gradientOverlay.BlendMode);
    AssertAreEqual((byte)193, gradientOverlay.Opacity);
    AssertAreEqual(true, gradientOverlay.IsVisible);

    var fillSettings = (GradientFillSettings)gradientOverlay.Settings;
    var solidGradient = (SolidGradient)gradientOverlay.Settings.Gradient;
    AssertAreEqual(Color.Empty, solidGradient.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Periksa titik warna
    AssertAreEqual(4, solidGradient.ColorPoints.Length);

    var point = solidGradient.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.FromArgb(9, 0, 178), point.Color);
    AssertAreEqual(0, point.Location);

    point = solidGradient.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Red, point.Color);
    AssertAreEqual(2048, point.Location);

    point = solidGradient.ColorPoints[2];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.FromArgb(255, 252, 0), point.Color);
    AssertAreEqual(3000, point.Location);

    point = solidGradient.ColorPoints[3];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // Periksa titik transparan
    AssertAreEqual(3, solidGradient.TransparencyPoints.Length);

    var transparencyPoint = solidGradient.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.0, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = solidGradient.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.0, transparencyPoint.Opacity);
    AssertAreEqual(2315, transparencyPoint.Location);

    transparencyPoint = solidGradient.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.0, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### Lihat Juga

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


