---
title: "PsdImage.AddGradientMapAdjustmentLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Methode. Fügt eine GradientMap-Anpassungsebene hinzu."
type: docs
weight: 360
url: /de/net/aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddGradientMapAdjustmentLayer method

Fügt die GradientMap‑Anpassungsebene hinzu.

```csharp
public GradientMapLayer AddGradientMapAdjustmentLayer()
```

### Rückgabewert

GradientMap-Instanz.

## Beispiele

Der folgende Code demonstriert die Unterstützung der Gradient‑Map‑Ebene.

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Fügen Sie eine Gradient‑Map‑Anpassungsebene hinzu.
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// Gespeicherte Änderungen überprüfen
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

### Siehe auch

* class [GradientMapLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


