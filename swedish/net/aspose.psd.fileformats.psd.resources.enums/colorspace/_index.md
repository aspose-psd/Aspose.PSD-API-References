---
title: "Enum ColorSpace"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace enum. Färgrymdstyperna"
type: docs
weight: 4160
url: /sv/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

Färgrymdstyperna.

```csharp
public enum ColorSpace : ushort
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| RGB | `0` | RGB-färgrymden. |
| HSB | `1` | HSB-färgrymden. |
| CMYK | `2` | CMYK-färgrymden. |
| Lab | `7` | Lab-färgrymden. |
| GrayScale | `8` | Gråskala-färgrymden. |

## Exempel

Följande kod visar hur man ändrar visningsalternativ för lagermask på 16-bitars bilder genom att ändra LmskResource-egenskaper.

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

// Läs in 16-bitars bild.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Hitta LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Kontrollera LmskResource-egenskaper.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Ändra LmskResource-egenskaper.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Spara bilden.
    image.Save(outputPsd);
}
```

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


