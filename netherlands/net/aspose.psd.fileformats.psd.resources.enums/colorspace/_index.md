---
title: "Enum ColorSpace"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace enum. De typen kleurruimtes."
type: docs
weight: 4160
url: /nl/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

De kleurruimtetypen.

```csharp
public enum ColorSpace : ushort
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| RGB | `0` | De RGB-kleurruimte. |
| HSB | `1` | De HSB-kleurruimte. |
| CMYK | `2` | De CMYK-kleurruimte. |
| Lab | `7` | De Lab-kleurruimte. |
| GrayScale | `8` | De Grijswaarden-kleurruimte. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


