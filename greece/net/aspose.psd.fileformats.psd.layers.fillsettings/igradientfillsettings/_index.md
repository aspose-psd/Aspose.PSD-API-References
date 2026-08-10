---
title: "Διεπαφή IGradientFillSettings"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings διεπαφή. Βασική διεπαφή για ρυθμίσεις γεμίσματος Gradient"
type: docs
weight: 2130
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
{{< psd/tize >}}
## IGradientFillSettings interface

Βασική διεπαφή για ρυθμίσεις γεμίσματος διαβάθμισης.

```csharp
public interface IGradientFillSettings : IFillSettings
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `BaseGradientFillSettings` είναι με θόρυβο. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `IGradientFillSettings` είναι δεντρά. |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradient/) { get; set; } | Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise). |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση. |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/) { get; set; } | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `IGradientFillSettings` είναι αντίστροφο. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | Λαμβάνει ή ορίζει την **κανονικοποιημένη** κλίμακα διαβάθμισης (σε ποσοστό). |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει την υποστήριξη του Gradient FillLayer και τις επιλογές επεξεργασίας του IGradientFillSettings.

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

### Δείτε επίσης

* interface [IFillSettings](../ifillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


