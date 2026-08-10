---
title: "ShapeLayer.Fill"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα ShapeLayer. Λαμβάνει ή ορίζει τις ρυθμίσεις Fill για την εσωτερική περιοχή των Shapes στη στρώση Shape."
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers/shapelayer/fill/
---
{{< psd/tize >}}
## ShapeLayer.Fill property

Λαμβάνει ή ορίζει τις ρυθμίσεις γεμίσματος για την εσωτερική περιοχή των Σχημάτων στο στρώμα Shape.

```csharp
public IFillSettings Fill { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την ιδιότητα Fill του ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeInternalSolid.psd";
string outFile = "ShapeInternalSolid.psd.out.psd";

using (PsdImage image = (PsdImage)Image.Load(
           srcFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    fillSettings.Color = Color.Red;

    shapeLayer.Update();

    image.Save(outFile);
}

// Ελέγξτε τις αποθηκευμένες αλλαγές
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;

    AssertAreEqual(Color.Red, fillSettings.Color);

    image.Save(outFile);
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

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


