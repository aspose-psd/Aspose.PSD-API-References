---
title: "VscgResource.Items"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "VscgResource ιδιότητα. Λαμβάνει ή ορίζει τον πίνακα των στοιχείων δομής. Προειδοποίηση: Οι τιμές του πίνακα Items πρέπει να ταιριάζουν με την ιδιότητα KeyForData, η οποία καθορίζει τον τύπο των ρυθμίσεων γεμίσματος που αποθηκεύονται στις δομές εντός Items"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/
---
{{< psd/tize >}}
## VscgResource.Items property

Λαμβάνει ή ορίζει τον πίνακα των στοιχείων δομής. **Warning:** Οι τιμές του πίνακα `Items` πρέπει να ταιριάζουν με την ιδιότητα `KeyForData`, η οποία καθορίζει τον τύπο των ρυθμίσεων γεμίσματος που αποθηκεύονται στις δομές μέσα στο `Items`.

```csharp
public OSTypeStructure[] Items { get; }
```

### Property Value

Ο πίνακας των [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) στοιχείων.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του VscgResource.

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// έλεγχος αλλαγών
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### Δείτε επίσης

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [VscgResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


