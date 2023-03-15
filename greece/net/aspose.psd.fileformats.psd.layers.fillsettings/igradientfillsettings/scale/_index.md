---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD για Αναφορά API .NET
description: IGradientFillSettings ιδιοκτησία. Παίρνει ή ρυθμίζει την κλίμακα.
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Παίρνει ή ρυθμίζει την κλίμακα.

```csharp
public int Scale { get; set; }
```

### Αξία περιουσίας

Η κλίμακα.

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς να χρησιμοποιήσετε την ιδιότητα Scale για να κλιμακώσετε το FillLayer με κλίση.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // λήψη ενός στρώματος πλήρωσης
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // τιμή κλίμακας ενημέρωσης
    settings.Scale = 200;
    fillLayer.Update(); // Ενημερώνει δεδομένα pixel

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Δείτε επίσης

* interface [IGradientFillSettings](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* συνέλευση [Aspose.PSD](../../../)


