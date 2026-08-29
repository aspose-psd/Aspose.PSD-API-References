---
title: "LmskResource.ColorSpace"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "LmskResource ιδιότητα. Λαμβάνει το χρωματικό χώρο"
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/
---
{{< psd/tize >}}
## LmskResource.ColorSpace property

Λαμβάνει το χρωματικό χώρο.

```csharp
public ColorSpace ColorSpace { get; set; }
```

### Property Value

Ο χρωματικός χώρος.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε τις επιλογές εμφάνισης Layer Mask σε εικόνες 16-bit μέσω αλλαγής των ιδιοτήτων LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Φόρτωση εικόνας 16-bit.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Εύρεση LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Έλεγχος ιδιοτήτων LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Αλλαγή ιδιοτήτων LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Αποθήκευση της εικόνας.
    image.Save(outputPsd);
}
```

### Δείτε επίσης

* enum [ColorSpace](../../../aspose.psd.fileformats.psd.resources.enums/colorspace/)
* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


