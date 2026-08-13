---
title: "Sınıf GradientOverlayEffect"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.GradientOverlayEffect sınıfı. Gradient Katman etkisi"
type: docs
weight: 2320
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/
---
{{< psd/tize >}}
## GradientOverlayEffect class

Gradyan Katman efekti

```csharp
public class GradientOverlayEffect : ILayerEffect
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/blendmode/) { get; set; } | Karışım modunu alır veya ayarlar. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/effecttype/) { get; } | Bir efekt türünü alır. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/isvisible/) { get; set; } | Bu örneğin görünür olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/opacity/) { get; set; } | Opaklığı alır veya ayarlar. |
| [Settings](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/settings/) { get; set; } | Ayarları alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/geteffectbounds/)(Rectangle, int) | Girdi katman piksel sınırlarına dayanarak efekt piksel sınırlarını hesaplar ve alır. |

## Örnekler

Aşağıdaki kod, gradient kaplama etkisinin desteğini gösterir.

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
    AssertAreEqual(FillType.Gradient, settings.FillType);
    AssertAreEqual(true, settings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, settings.GradientType);
    AssertIsTrue(Math.Abs(33 - settings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, settings.Dither);
    AssertIsTrue(Math.Abs(129 - settings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(156 - settings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, settings.Reverse);

    // Renk Noktaları
    var colorPoints = solidGradient.ColorPoints;
    AssertAreEqual(3, colorPoints.Length);

    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(255, 9, 0, 178), colorPoints[0].RawColor);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(Color.Red), colorPoints[1].RawColor);
    AssertAreEqual(2048, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(255, 255, 252, 0), colorPoints[2].RawColor);
    AssertAreEqual(4096, colorPoints[2].Location);
    AssertAreEqual(50, colorPoints[2].MedianPointLocation);

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
    gradientOverlay.Opacity = 193;
    gradientOverlay.BlendMode = BlendMode.Lighten;

    settings.AlignWithLayer = false;
    settings.GradientType = GradientType.Radial;
    settings.Angle = 45;
    settings.Dither = true;
    settings.HorizontalOffset = 15;
    settings.VerticalOffset = 11;
    settings.Reverse = true;

    // Yeni renk noktası ekle
    var colorPoint = solidGradient.AddColorPoint();
    colorPoint.RawColor = RawColorHelper.CreateArgb8BitColor(Color.Green);
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Önceki noktanın konumunu değiştir
    solidGradient.ColorPoints[2].Location = 3000;

    // Yeni şeffaflık noktası ekle
    var transparencyPoint = solidGradient.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Önceki şeffaflık noktasının konumunu değiştir
    solidGradient.TransparencyPoints[1].Location = 2315;
    im.Save(exportPath);
}

// Düzenlemeden sonra test dosyası
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientOverlay = (GradientOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Lighten, gradientOverlay.BlendMode);
    AssertAreEqual((byte)193, gradientOverlay.Opacity);
    AssertAreEqual(true, gradientOverlay.IsVisible);

    var fillSettings = (GradientFillSettings)gradientOverlay.Settings;
    var solidGradient = (SolidGradient)gradientOverlay.Settings.Gradient;
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Renk noktalarını kontrol et
    AssertAreEqual(4, solidGradient.ColorPoints.Length);

    var point = solidGradient.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(255, 9, 0, 178), point.RawColor);
    AssertAreEqual(0, point.Location);

    point = solidGradient.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(Color.Red), point.RawColor);
    AssertAreEqual(2048, point.Location);

    point = solidGradient.ColorPoints[2];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(255, 255, 252, 0), point.RawColor);
    AssertAreEqual(3000, point.Location);

    point = solidGradient.ColorPoints[3];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(RawColorHelper.CreateArgb8BitColor(Color.Green), point.RawColor);
    AssertAreEqual(4096, point.Location);

    // Şeffaf noktaları kontrol et
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

### Ayrıca Bakınız

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


