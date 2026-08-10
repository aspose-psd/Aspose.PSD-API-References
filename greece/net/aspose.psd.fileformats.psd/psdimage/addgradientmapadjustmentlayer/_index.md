---
title: "PsdImage.AddGradientMapAdjustmentLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος PsdImage. Προσθέτει στρώμα προσαρμογής GradientMap"
type: docs
weight: 360
url: /el/net/aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddGradientMapAdjustmentLayer method

Προσθέτει το επίπεδο προσαρμογής GradientMap.

```csharp
public GradientMapLayer AddGradientMapAdjustmentLayer()
```

### Τιμή Επιστροφής

Παράδειγμα GradientMap.

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

* class [GradientMapLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


