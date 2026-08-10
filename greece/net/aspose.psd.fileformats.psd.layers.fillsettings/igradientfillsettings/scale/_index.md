---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα IGradientFillSettings. Λαμβάνει ή ορίζει την κανονικοποιημένη κλίμακα διαβάθμισης σε ποσοστό"
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

Λαμβάνει ή ορίζει την **κανονικοποιημένη** κλίμακα διαβάθμισης (σε ποσοστό).

```csharp
public int Scale { get; set; }
```

### Property Value

Η κλίμακα.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να χρησιμοποιήσετε την ιδιότητα Scale για να κλιμακώσετε το FillLayer με διαβάθμιση.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // Λήψη ενός FillLayer
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

    // Ενημέρωση τιμής κλίμακας
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Δείτε επίσης

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


