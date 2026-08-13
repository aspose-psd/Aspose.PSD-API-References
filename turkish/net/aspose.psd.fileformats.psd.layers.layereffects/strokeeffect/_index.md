---
title: "Sınıf StrokeEffect"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokeEffect sınıfı. PSD katmanı için Adobe Photoshop kontur efekti"
type: docs
weight: 2390
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---
{{< psd/tize >}}
## StrokeEffect class

PSD katmanı için Adobe® Photoshop® çizgi efekti.

```csharp
public class StrokeEffect : ILayerEffect
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/blendmode/) { get; set; } | Karışım modunu alır veya ayarlar. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/effecttype/) { get; } | Bir efekt türünü alır. |
| [FillSettings](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/fillsettings/) { get; set; } | Doldurma ayarlarını alır veya ayarlar. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/isvisible/) { get; set; } | Bu örneğin görünür olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/opacity/) { get; set; } | Opaklığı alır veya ayarlar. |
| [Overprint](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/overprint/) { get; set; } | Bu `StrokeEffect`'in mevcut katman içeriğine karşı çizgiyi harmanlayıp harmanlamayacağını belirten bir değeri alır veya ayarlar. |
| [Position](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/) { get; set; } | Çizgi etkisinin konumunu alır veya ayarlar; bu, çizginizin PSD katman içeriğine göre hizalanmasını kontrol eder. Değer, çizgiyi PSD katman içeriğinin içine çizmek için Inside, dışına çizmek için Outside veya hem içine hem dışına çizmek için Center olabilir. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/size/) { get; set; } | Çizgi etkisinin genişliğini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/geteffectbounds/)(Rectangle, int) | Girdi katman piksel sınırlarına dayanarak efekt piksel sınırlarını hesaplar ve alır. |

## Örnekler

Aşağıdaki kod örneği, Renk Doldurma ile Stroke etkisinin işlenmesini gösterir.

```csharp
[C#]

// Dışa aktarma için Renk Doldurma ile Stroke etkisinin işlenmesini uygulayın
string sourceFileName = "StrokeComplex.psd";
string exportPath = "StrokeComplexRendering.psd";
string exportPathPng = "StrokeComplexRendering.png";
var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};
using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    for (int i = 0; i < im.Layers.Length; i++)
    {
        var effect = (StrokeEffect)im.Layers[i].BlendingOptions.Effects[0];
        var settings = (ColorFillSettings)effect.FillSettings;
        settings.Color = Color.DeepPink;
    }

    // PSD'yi kaydet
    im.Save(exportPath, new PsdOptions());
    // PNG'yi kaydet
    im.Save(exportPathPng, new PngOptions()
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

Aşağıdaki kod, doldurma türü - Renk ile çizgi efekti katmanının desteğini gösterir.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

var sourceFileName = "Stroke.psd";
var exportPath = "StrokeColorChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, colorStroke.BlendMode);
    AssertAreEqual((byte)255, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);

    fillSettings.Color = Color.Yellow;

    colorStroke.Opacity = 127;
    colorStroke.BlendMode = BlendMode.Color;
    im.Save(exportPath);
}

// Düzenlemeden sonra test dosyası
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, colorStroke.BlendMode);
    AssertAreEqual((byte)127, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Yellow, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);
}
```

Aşağıdaki kod, doldurma tipi - Desen olan çizgi efekti katmanının desteğini gösterir.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (expected is Array && actual is Array)
    {
        Array array1 = (Array)expected;
        Array array2 = (Array)actual;
        AssertAreEqual(array1.Length, array2.Length);

        for (int i = 0; i < array1.Length; i++)
        {
            AssertAreEqual(array1.GetValue(i), array2.GetValue(i));
        }
        return;
    }

    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "Stroke.psd";
string exportPath = "StrokePatternChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

// Yeni veri hazırlanıyor
var newPattern = new int[]
{
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
};

var newPatternBounds = new Rectangle(0, 0, 4, 4);
var guid = Guid.NewGuid();

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var patternStroke = (StrokeEffect)im.Layers[3].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, patternStroke.BlendMode);
    AssertAreEqual((byte)255, patternStroke.Opacity);
    AssertAreEqual(true, patternStroke.IsVisible);

    var fillSettings = (PatternFillSettings)patternStroke.FillSettings;
    AssertAreEqual(FillType.Pattern, fillSettings.FillType);

    patternStroke.Opacity = 127;
    patternStroke.BlendMode = BlendMode.Color;

    PattResource resource;
    foreach (var globalLayerResource in im.GlobalLayerResources)
    {
        if (globalLayerResource is PattResource)
        {
            resource = (PattResource)globalLayerResource;
            resource.Patterns[0].PatternId = guid.ToString();
            resource.Patterns[0].Name = "$$$/Presets/Patterns/HorizontalLine1=Horizontal Line 9\0";

            resource.Patterns[0].SetPattern(newPattern, newPatternBounds);
        }
    }

    ((PatternFillSettings)patternStroke.FillSettings).PatternName = "$$$/Presets/Patterns/HorizontalLine1=Horizontal Line 9\0";

    ((PatternFillSettings)patternStroke.FillSettings).PatternId = guid.ToString() + "\0";
    im.Save(exportPath);
}

// Düzenlemeden sonra test dosyası
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var patternStroke = (StrokeEffect)im.Layers[3].BlendingOptions.Effects[0];

    PattResource resource = null;
    foreach (var globalLayerResource in im.GlobalLayerResources)
    {
        if (globalLayerResource is PattResource)
        {
            resource = (PattResource)globalLayerResource;
        }
    }

    if (resource == null)
    {
        throw new Exception("PattResource not found");
    }

    // Desen verisini kontrol et
    AssertAreEqual(newPattern, resource.Patterns[0].PatternData);
    AssertAreEqual(newPatternBounds, new Rectangle(0, 0, resource.Patterns[0].Width, resource.Patterns[0].Height));
    AssertAreEqual(guid.ToString().ToUpperInvariant(), resource.Patterns[0].PatternId);

    AssertAreEqual(BlendMode.Color, patternStroke.BlendMode);
    AssertAreEqual((byte)127, patternStroke.Opacity);
    AssertAreEqual(true, patternStroke.IsVisible);

    var fillSettings = (PatternFillSettings)patternStroke.FillSettings;

    AssertAreEqual(FillType.Pattern, fillSettings.FillType);
}
```

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

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


