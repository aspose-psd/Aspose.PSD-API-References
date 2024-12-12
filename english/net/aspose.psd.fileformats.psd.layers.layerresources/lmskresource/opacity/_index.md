---
title: LmskResource.Opacity
second_title: Aspose.PSD for .NET API Reference
description: LmskResource property. Gets the opacity
type: docs
weight: 90
url: /net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/
---
{{< psd/tize >}}
## LmskResource.Opacity property

Gets the opacity.

```csharp
public short Opacity { get; set; }
```

### Property Value

The opacity.

## Examples

The following code demonstrates how to change Layer Mask Display Options on 16-bit images through changing LmskResource properties.

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

// Load 16-bit image.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Find LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Check LmskResource properties.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Change LmskResource properties.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Save the image.
    image.Save(outputPsd);
}
```

### See Also

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


