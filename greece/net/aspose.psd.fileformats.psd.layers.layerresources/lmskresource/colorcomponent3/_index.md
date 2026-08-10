---
title: "LmskResource.ColorComponent3"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "LmskResource ιδιότητα. Λαμβάνει το στοιχείο χρώματος 3"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/
---
{{< psd/tize >}}
## LmskResource.ColorComponent3 property

Λαμβάνει το συστατικό χρώματος 3.

```csharp
public ushort ColorComponent3 { get; set; }
```

### Property Value

Το στοιχείο χρώματος 3.

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

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


