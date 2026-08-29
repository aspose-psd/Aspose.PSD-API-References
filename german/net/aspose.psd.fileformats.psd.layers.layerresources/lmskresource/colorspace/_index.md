---
title: "LmskResource.ColorSpace"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LmskResource-Eigenschaft. Gibt den Farbraum zurück"
type: docs
weight: 60
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/
---
{{< psd/tize >}}
## LmskResource.ColorSpace property

Liest den Farbraum.

```csharp
public ColorSpace ColorSpace { get; set; }
```

### Property Value

Der Farbraum.

## Beispiele

Der folgende Code demonstriert, wie man die Anzeigeoptionen der Ebenenmaske bei 16‑Bit‑Bildern durch Ändern der LmskResource‑Eigenschaften ändert.

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

// 16‑Bit‑Bild laden.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // LmskResource finden.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // LmskResource‑Eigenschaften prüfen.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // LmskResource‑Eigenschaften ändern.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Das Bild speichern.
    image.Save(outputPsd);
}
```

### Siehe auch

* enum [ColorSpace](../../../aspose.psd.fileformats.psd.resources.enums/colorspace/)
* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


