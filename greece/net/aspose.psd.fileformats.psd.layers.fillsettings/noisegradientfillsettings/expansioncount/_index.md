---
title: "NoiseGradientFillSettings.ExpansionCount"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "NoiseGradientFillSettings ιδιότητα. Λαμβάνει ή ορίζει τον αριθμό επέκτασης   2 για Photoshop 6.0"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/expansioncount/
---
{{< psd/tize >}}
## NoiseGradientFillSettings.ExpansionCount property

Λαμβάνει ή ορίζει τον αριθμό επέκτασης ( = 2 για Photoshop 6.0).

```csharp
public short ExpansionCount { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του στρώματος χάρτη διαβάθμισης.

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Προσθήκη στρώσης προσαρμογής χάρτη διαβάθμισης.
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// Ελέγξτε τις αποθηκευμένες αλλαγές
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    GradientFillSettings gradientSettings = (GradientFillSettings)gradientMapLayer.GradientSettings;

    AssertAreEqual(90.0, gradientSettings.Angle);
    AssertAreEqual((short)4096, gradientSettings.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(true, gradientSettings.AlignWithLayer);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual(GradientType.Linear, gradientSettings.GradientType);
    AssertAreEqual(100, gradientSettings.Scale);
    AssertAreEqual(0.0, gradientSettings.HorizontalOffset);
    AssertAreEqual(0.0, gradientSettings.VerticalOffset);
    AssertAreEqual("Custom", gradientSettings.GradientName);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Δείτε επίσης

* class [NoiseGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


