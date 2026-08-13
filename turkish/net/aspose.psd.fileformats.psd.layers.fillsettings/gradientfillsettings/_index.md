---
title: "Sınıf GradientFillSettings"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientFillSettings sınıfı. Temel gradyan tanım sınıfı. Hem Katı hem de Gürültü gradyan türleri için ortak özellikleri içerir."
type: docs
weight: 2070
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---
{{< psd/tize >}}
## GradientFillSettings class

Temel gradyan tanım sınıfı. Hem Katı hem de Gürültü gradyan türleri için ortak özellikleri içerir.

```csharp
public class GradientFillSettings : BaseFillSettings, IGradientFillSettings
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [GradientFillSettings](gradientfillsettings/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/alignwithlayer/) { get; set; } | [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/angle/) { get; set; } | Açıyı alır veya ayarlar. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/dither/) { get; set; } | Bu `GradientFillSettings`'in titreme (dither) olup olmadığını gösteren bir değeri alır veya ayarlar. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/filltype/) { get; } | Doldurma türü. |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradient/) { get; set; } | Belirli degrade tanımı örneğini (Katı/Gürültü) alır veya ayarlar. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/) { get; set; } | Degrade tipini alır veya ayarlar. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/horizontaloffset/) { get; set; } | Yüzde olarak yatay ofseti alır veya ayarlar. |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/interpolationmethod/) { get; set; } | Degrade için ara değerleme yöntemini alır veya ayarlar. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/reverse/) { get; set; } | Bu `GradientFillSettings`'in ters (reverse) olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/scale/) { get; set; } | Yüzde olarak **normalized** gradyan ölçeğini alır veya ayarlar. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/verticaloffset/) { get; set; } | Yüzde olarak dikey ofseti alır veya ayarlar. |

## Örnekler

Aşağıdaki kod, dolgu tipi - Gradyan ile çizgi efekti katmanının desteğini gösterir.

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

string sourceFileName = "Stroke.psd";
string exportPath = "StrokeGradientChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, gradientStroke.BlendMode);
    AssertAreEqual((byte)255, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);
    AssertAreEqual(true, fillSettings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, fillSettings.GradientType);
    AssertIsTrue(Math.Abs(90 - fillSettings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, fillSettings.Dither);
    AssertIsTrue(Math.Abs(0 - fillSettings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - fillSettings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, fillSettings.Reverse);

    // Renk Noktaları
    var solidGradient = (SolidGradient)fillSettings.Gradient;
    var colorPoints = solidGradient.ColorPoints;
    AssertAreEqual(2, colorPoints.Length);

    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(Color.Black), colorPoints[0].RawColor);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(Color.White), colorPoints[1].RawColor);
    AssertAreEqual(4096, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    // Şeffaflık noktaları
    var transparencyPoints = solidGradient.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Düzenlemeyi test et
    gradientStroke.Opacity = 127;
    gradientStroke.BlendMode = BlendMode.Color;

    fillSettings.AlignWithLayer = false;
    fillSettings.GradientType = GradientType.Radial;
    fillSettings.Angle = 45;
    fillSettings.Dither = true;
    fillSettings.HorizontalOffset = 15;
    fillSettings.VerticalOffset = 11;
    fillSettings.Reverse = true;

    // Yeni renk noktası ekle
    var colorPoint = solidGradient.AddColorPoint();
    colorPoint.RawColor = RawColorHelper.CreateArgb8BitColor(Color.Green);
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Önceki noktanın konumunu değiştir
    solidGradient.ColorPoints[1].Location = 1899;

    // Yeni şeffaflık noktası ekle
    var transparencyPoint = solidGradient.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Önceki şeffaflık noktasının konumunu değiştir
    solidGradient.TransparencyPoints[1].Location = 2411;

    im.Save(exportPath);
}

// Düzenlemeden sonra test dosyası
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, gradientStroke.BlendMode);
    AssertAreEqual((byte)127, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    var solidGradient = (SolidGradient)fillSettings.Gradient;
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Renk noktalarını kontrol et
    AssertAreEqual(3, solidGradient.ColorPoints.Length);

    var point = solidGradient.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(Color.Black), point.RawColor);
    AssertAreEqual(0, point.Location);

    point = solidGradient.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(Color.White), point.RawColor);
    AssertAreEqual(1899, point.Location);

    point = solidGradient.ColorPoints[2];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(Color.Green), point.RawColor);
    AssertAreEqual(4096, point.Location);

    // Şeffaf noktaları kontrol et
    AssertAreEqual(3, solidGradient.TransparencyPoints.Length);

    var transparencyPoint = solidGradient.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = solidGradient.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(2411, transparencyPoint.Location);

    transparencyPoint = solidGradient.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.00, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### Ayrıca Bakınız

* class [BaseFillSettings](../basefillsettings/)
* interface [IGradientFillSettings](../igradientfillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


