---
title: Interface IGradientFillSettings
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings koppel. Basisinterface voor vulinstellingen
type: docs
weight: 2010
url: /nl/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
## IGradientFillSettings interface

Basisinterface voor vulinstellingen

```csharp
public interface IGradientFillSettings : IFillSettings
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [uitlijnen met laag]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | Haalt of stelt de hoek in. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/color/) { get; set; } | Krijgt of stelt de kleur in. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/colorpoints/) { get; set; } | Krijgt de kleurpunten. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | Haalt of stelt een waarde in die aangeeft of dit`IGradientFillSettings` is dither. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradientname/) { get; set; } | Haalt de naam van het verloop op of stelt deze in. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | Hiermee wordt het type verloop opgehaald of ingesteld. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | Haalt of stelt de horizontale offset in. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | Haalt of stelt een waarde in die aangeeft of dit`IGradientFillSettings` is omgekeerd. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | Krijgt of stelt de schaal in. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/transparencypoints/) { get; set; } | Haalt de transparantiepunten op. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | Haalt of stelt de verticale offset in. |

### Voorbeelden

Het volgende voorbeeld demonstreert ondersteuning voor Gradient FillLayer en bewerkingsopties voor IGradientFillSettings..

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string outputFile = "ComplexGradientFillLayer_output.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            if (fillLayer.FillSettings.FillType != FillType.Gradient)
            {
                throw new Exception("Wrong Fill Layer");
            }
            var settings = (IGradientFillSettings)fillLayer.FillSettings;
            if (
             Math.Abs(settings.Angle - 45) > 0.25 ||
             settings.Dither != true ||
             settings.AlignWithLayer != false ||
             settings.Reverse != false ||
             Math.Abs(settings.HorizontalOffset - (-39)) > 0.25 ||
             Math.Abs(settings.VerticalOffset - (-5)) > 0.25 ||
             settings.TransparencyPoints.Length != 3 ||
             settings.ColorPoints.Length != 2 ||
             Math.Abs(100.0 - settings.TransparencyPoints[0].Opacity) > 0.25 ||
             settings.TransparencyPoints[0].Location != 0 ||
             settings.TransparencyPoints[0].MedianPointLocation != 50 ||
             settings.ColorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
             settings.ColorPoints[0].Location != 0 ||
             settings.ColorPoints[0].MedianPointLocation != 50)
            {
                throw new Exception("Gradient Fill was not read correctly");
            }
            settings.Angle = 0.0;
            settings.Dither = false;
            settings.AlignWithLayer = true;
            settings.Reverse = true;
            settings.HorizontalOffset = 25;
            settings.VerticalOffset = -15;
            var colorPoints = new List<IGradientColorPoint>(settings.ColorPoints);
            var transparencyPoints = new List<IGradientTransparencyPoint>(settings.TransparencyPoints);
            colorPoints.Add(new GradientColorPoint()
            {
                Color = Color.Violet,
                Location = 4096,
                MedianPointLocation = 75
            });
            colorPoints[1].Location = 3000;
            transparencyPoints.Add(new GradientTransparencyPoint()
            {
                Opacity = 80.0,
                Location = 4096,
                MedianPointLocation = 25
            });
            transparencyPoints[2].Location = 3000;
            settings.ColorPoints = colorPoints.ToArray();
            settings.TransparencyPoints = transparencyPoints.ToArray();
            fillLayer.Update();
            im.Save(outputFile, new PsdOptions(im));
            break;
        }
    }
}
```

### Zie ook

* interface [IFillSettings](../ifillsettings/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* montage [Aspose.PSD](../../)


