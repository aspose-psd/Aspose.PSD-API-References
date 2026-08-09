---
title: "Interface IGradientFillSettings"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings interface. Interface de base pour les paramètres de remplissage Gradient"
type: docs
weight: 2130
url: /fr/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
{{< psd/tize >}}
## IGradientFillSettings interface

Interface de base pour les paramètres de remplissage de dégradé.

```csharp
public interface IGradientFillSettings : IFillSettings
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | Obtient ou définit une valeur indiquant si [align with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | Obtient ou définit l'angle. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | Obtient ou définit une valeur indiquant si ce `IGradientFillSettings` est dither. |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradient/) { get; set; } | Obtient ou définit une instance de définition de dégradé spécifique (Solid/Noise). |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | Obtient ou définit le type du dégradé. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | Obtient ou définit le décalage horizontal. |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/) { get; set; } | Obtient ou définit la méthode d'interpolation du dégradé. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | Obtient ou définit une valeur indiquant si ce `IGradientFillSettings` est inversé. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | Obtient ou définit l'échelle de gradient **normalisée** (en pourcentage). |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | Obtient ou définit le décalage vertical. |

## Exemples

L'exemple suivant montre la prise en charge du FillLayer Gradient et les options de modification de IGradientFillSettings..

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
            var settings = (GradientFillSettings)fillLayer.FillSettings;
            var solidGradient = (SolidGradient)settings.Gradient;
            if (
             Math.Abs(settings.Angle - 45) > 0.25 ||
             settings.Dither != true ||
             settings.AlignWithLayer != false ||
             settings.Reverse != false ||
             Math.Abs(settings.HorizontalOffset - (-39)) > 0.25 ||
             Math.Abs(settings.VerticalOffset - (-5)) > 0.25 ||
             solidGradient.TransparencyPoints.Length != 3 ||
             solidGradient.ColorPoints.Length != 2 ||
             Math.Abs(100.0 - solidGradient.TransparencyPoints[0].Opacity) > 0.25 ||
             solidGradient.TransparencyPoints[0].Location != 0 ||
             solidGradient.TransparencyPoints[0].MedianPointLocation != 50 ||
             solidGradient.ColorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
             solidGradient.ColorPoints[0].Location != 0 ||
             solidGradient.ColorPoints[0].MedianPointLocation != 50)
            {
                throw new Exception("Gradient Fill was not read correctly");
            }
            settings.Angle = 0.0;
            settings.Dither = false;
            settings.AlignWithLayer = true;
            settings.Reverse = true;
            settings.HorizontalOffset = 25;
            settings.VerticalOffset = -15;
            var colorPoints = new List<IGradientColorPoint>(solidGradient.ColorPoints);
            var transparencyPoints = new List<IGradientTransparencyPoint>(solidGradient.TransparencyPoints);
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
            solidGradient.ColorPoints = colorPoints.ToArray();
            solidGradient.TransparencyPoints = transparencyPoints.ToArray();
            fillLayer.Update();
            im.Save(outputFile, new PsdOptions(im));
            break;
        }
    }
}
```

### Voir aussi

* interface [IFillSettings](../ifillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


