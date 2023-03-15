---
title: Class GradientOverlayEffect
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.GradientOverlayEffect klas. Verlooplaageffect
type: docs
weight: 2130
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/
---
## GradientOverlayEffect class

Verlooplaageffect

```csharp
public class GradientOverlayEffect : ILayerEffect
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/blendmode/) { get; set; } | Krijgt of stelt de overvloeimodus in. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/effecttype/) { get; } | Krijgt een type effect |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/isvisible/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie zichtbaar is. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/opacity/) { get; set; } | Haalt of stelt de dekking in. |
| [Settings](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/settings/) { get; set; } | Krijgt of stelt de instellingen in. |

### Voorbeelden

De volgende code demonstreert de ondersteuning van het verloopoverlay-effect.

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

    var settings = gradientOverlay.Settings;
    AssertAreEqual(Color.Empty, settings.Color);
    AssertAreEqual(FillType.Gradient, settings.FillType);
    AssertAreEqual(true, settings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, settings.GradientType);
    AssertIsTrue(Math.Abs(33 - settings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, settings.Dither);
    AssertIsTrue(Math.Abs(129 - settings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(156 - settings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, settings.Reverse);

    // Kleurpunten
    var colorPoints = settings.ColorPoints;
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

    // Transparantiepunten
    var transparencyPoints = settings.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Testbewerking
    settings.Color = Color.Green;

    gradientOverlay.Opacity = 193;
    gradientOverlay.BlendMode = BlendMode.Lighten;

    settings.AlignWithLayer = false;
    settings.GradientType = GradientType.Radial;
    settings.Angle = 45;
    settings.Dither = true;
    settings.HorizontalOffset = 15;
    settings.VerticalOffset = 11;
    settings.Reverse = true;

    // Voeg een nieuw kleurpunt toe
    var colorPoint = settings.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Wijzig de locatie van het vorige punt
    settings.ColorPoints[2].Location = 3000;

    // Voeg een nieuw transparantiepunt toe
    var transparencyPoint = settings.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Wijzig de locatie van het vorige transparantiepunt
    settings.TransparencyPoints[1].Location = 2315;
    im.Save(exportPath);
}

// Testbestand na bewerking
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientOverlay = (GradientOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Lighten, gradientOverlay.BlendMode);
    AssertAreEqual((byte)193, gradientOverlay.Opacity);
    AssertAreEqual(true, gradientOverlay.IsVisible);

    var fillSettings = gradientOverlay.Settings;
    AssertAreEqual(Color.Empty, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Controleer kleurpunten
    AssertAreEqual(4, fillSettings.ColorPoints.Length);

    var point = fillSettings.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.FromArgb(9, 0, 178), point.Color);
    AssertAreEqual(0, point.Location);

    point = fillSettings.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Red, point.Color);
    AssertAreEqual(2048, point.Location);

    point = fillSettings.ColorPoints[2];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.FromArgb(255, 252, 0), point.Color);
    AssertAreEqual(3000, point.Location);

    point = fillSettings.ColorPoints[3];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // Controleer transparante punten
    AssertAreEqual(3, fillSettings.TransparencyPoints.Length);

    var transparencyPoint = fillSettings.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.0, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.0, transparencyPoint.Opacity);
    AssertAreEqual(2315, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.0, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### Zie ook

* interface [ILayerEffect](../ilayereffect/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* montage [Aspose.PSD](../../)


