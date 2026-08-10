---
title: "NoiseGradient.ExpansionCount"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "NoiseGradient ιδιότητα. Ανακτά ή ορίζει τον αριθμό Επέκτασης   2 για το Photoshop 6.0"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.gradient/noisegradient/expansioncount/
---
{{< psd/tize >}}
## NoiseGradient.ExpansionCount property

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
    var gradientSettings = gradientMapLayer.GradientSettings;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;

    AssertAreEqual((short)4096, solidGradient.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual("Custom", solidGradient.GradientName);
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

* class [NoiseGradient](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../../)


