---
title: FilterEffectMaskData.GUID
second_title: Aspose.PSD för .NET API-referens
description: FilterEffectMaskData fast egendom. Hämtar GUID.
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/
---
## FilterEffectMaskData.GUID property

Hämtar GUID.

```csharp
public string GUID { get; }
```

### Exempel

Det här exemplet visar hur man hämtar och ställer in egenskaper för FXidResource-resursen.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// kontrollera efter att du har sparat
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### Se även

* class [FilterEffectMaskData](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* hopsättning [Aspose.PSD](../../../)


