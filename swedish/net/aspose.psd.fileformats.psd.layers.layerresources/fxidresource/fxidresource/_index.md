---
title: FXidResource.FXidResource
second_title: Aspose.PSD för .NET API-referens
description: FXidResource byggare. Initierar en ny instans avFXidResource class.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Initierar en ny instans av[`FXidResource`](../) class.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | Int32 | Resursnyckeln. |
| version | Int32 | Versionen. |
| filterEffectMasks | FilterEffectMaskData[] | Filtereffekten maskerar. |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* hopsättning [Aspose.PSD](../../../)


