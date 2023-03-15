---
title: Class GradientFillSettings
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientFillSettings sınıf. Degrade dolgu efekti ayarları.
type: docs
weight: 1960
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---
## GradientFillSettings class

Degrade dolgu efekti ayarları.

```csharp
public class GradientFillSettings : BaseFillSettings, IGradientFillSettings
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GradientFillSettings](gradientfillsettings/)() | Yeni bir örneğini başlatır.`GradientFillSettings` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/alignwithlayer/) { get; set; } | [katmanla hizalayın]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/angle/) { get; set; } | Açıyı alır veya ayarlar. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/color/) { get; set; } | Rengi alır veya ayarlar. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/colorpoints/) { get; set; } | Renk noktalarını alır veya ayarlar. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/dither/) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.`GradientFillSettings` titreme. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/filltype/) { get; } | Dolgu türü |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradientname/) { get; set; } | Degradenin adını alır veya ayarlar. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/) { get; set; } | Degradenin türünü alır veya ayarlar. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/horizontaloffset/) { get; set; } | Yatay ofseti yüzde olarak alır veya ayarlar. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/reverse/) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.`GradientFillSettings` ters. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/scale/) { get; set; } | Ölçeği alır veya ayarlar. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/transparencypoints/) { get; set; } | Şeffaflık noktalarını alır veya ayarlar. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/verticaloffset/) { get; set; } | Dikey ofseti yüzde olarak alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addcolorpoint/)() | Renk noktasını ekler. |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addtransparencypoint/)() | Renk noktasını ekler. |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removecolorpoint/)(IGradientColorPoint) | Renk noktasını kaldırır. |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removetransparencypoint/)(IGradientTransparencyPoint) | Saydamlık noktasını kaldırır. |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/generatelfx2resourcenodes/)() | LFX2 kaynak düğümlerini oluşturur. |

### Örnekler

Aşağıdaki kod, dolgu türü - Degrade ile kontur efekti katmanının desteğini gösterir.

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
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);
    AssertAreEqual(true, fillSettings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, fillSettings.GradientType);
    AssertIsTrue(Math.Abs(90 - fillSettings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, fillSettings.Dither);
    AssertIsTrue(Math.Abs(0 - fillSettings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - fillSettings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, fillSettings.Reverse);

    // Renk Noktaları
    var colorPoints = fillSettings.ColorPoints;
    AssertAreEqual(2, colorPoints.Length);

    AssertAreEqual(Color.Black, colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.White, colorPoints[1].Color);
    AssertAreEqual(4096, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    // Şeffaflık noktaları
    var transparencyPoints = fillSettings.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Test düzenleme
    fillSettings.Color = Color.Green;

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
    var colorPoint = fillSettings.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Önceki noktanın konumunu değiştir
    fillSettings.ColorPoints[1].Location = 1899;

    // Yeni şeffaflık noktası ekle
    var transparencyPoint = fillSettings.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Önceki saydamlık noktasının konumunu değiştir
    fillSettings.TransparencyPoints[1].Location = 2411;

    im.Save(exportPath);
}

// Düzenlemeden sonra dosyayı test edin
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, gradientStroke.BlendMode);
    AssertAreEqual((byte)127, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(Color.Green, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Renk noktalarını kontrol et
    AssertAreEqual(3, fillSettings.ColorPoints.Length);

    var point = fillSettings.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Black, point.Color);
    AssertAreEqual(0, point.Location);

    point = fillSettings.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.White, point.Color);
    AssertAreEqual(1899, point.Location);

    point = fillSettings.ColorPoints[2];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // Saydam noktaları kontrol et
    AssertAreEqual(3, fillSettings.TransparencyPoints.Length);

    var transparencyPoint = fillSettings.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(2411, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.00, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### Ayrıca bakınız

* class [BaseFillSettings](../basefillsettings/)
* interface [IGradientFillSettings](../igradientfillsettings/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* toplantı [Aspose.PSD](../../)


