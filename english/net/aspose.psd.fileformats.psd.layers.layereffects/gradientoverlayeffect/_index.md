---
title: Class GradientOverlayEffect
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.GradientOverlayEffect class. Gradient Layer effect
type: docs
weight: 2160
url: /net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/
---
{{< psd/tize >}}
## GradientOverlayEffect class

Gradient Layer effect

```csharp
public class GradientOverlayEffect : ILayerEffect
```

## Properties

| Name | Description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/blendmode/) { get; set; } | Gets or sets the blend mode. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/effecttype/) { get; } | Gets a type of effect |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/isvisible/) { get; set; } | Gets or sets a value indicating whether this instance is visible. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/opacity/) { get; set; } | Gets or sets the opacity. |
| [Settings](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/settings/) { get; set; } | Gets or sets the settings. |

## Examples

The following code demonstrates the support of the gradient overlay effect.

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

    // Color Points
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

    // Transparency points
    var transparencyPoints = settings.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Test editing
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

    // Add new color point
    var colorPoint = settings.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Change location of previous point
    settings.ColorPoints[2].Location = 3000;

    // Add new transparency point
    var transparencyPoint = settings.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Change location of previous transparency point
    settings.TransparencyPoints[1].Location = 2315;
    im.Save(exportPath);
}

// Test file after edit
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientOverlay = (GradientOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Lighten, gradientOverlay.BlendMode);
    AssertAreEqual((byte)193, gradientOverlay.Opacity);
    AssertAreEqual(true, gradientOverlay.IsVisible);

    var fillSettings = gradientOverlay.Settings;
    AssertAreEqual(Color.Empty, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Check color points
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

    // Check transparent points
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

### See Also

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


