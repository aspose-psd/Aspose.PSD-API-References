---
title: "GradientMapLayer.GradientSettings"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα GradientMapLayer. Λαμβάνει ή ορίζει το στιγμιότυπο ρυθμίσεων Gradient που παρέχεται από το στιγμιότυπο GrdmResource"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/gradientsettings/
---
{{< psd/tize >}}
## GradientMapLayer.GradientSettings property

Λαμβάνει ή ορίζει την παρουσία ρυθμίσεων Gradient που περνιέται από την παρουσία GrdmResource.

```csharp
public GradientMapSettings GradientSettings { get; set; }
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

* class [GradientMapSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/)
* class [GradientMapLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


