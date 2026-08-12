---
title: "LmskResource.Flag"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "LmskResource eigenschap. Haalt de vlag op"
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/
---
{{< psd/tize >}}
## LmskResource.Flag property

Haalt de vlag op.

```csharp
public byte Flag { get; }
```

### Property Value

De vlag.

## Voorbeelden

De volgende code demonstreert hoe je de weergaveopties van Layer Mask kunt wijzigen op 16-bit afbeeldingen door LmskResource-eigenschappen te wijzigen.

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

// Laad 16-bit afbeelding.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Zoek LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Controleer LmskResource-eigenschappen.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Wijzig LmskResource-eigenschappen.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Sla de afbeelding op.
    image.Save(outputPsd);
}
```

### Zie ook

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


