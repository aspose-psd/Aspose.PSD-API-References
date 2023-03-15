---
title: FilterEffectMaskData.GUID
second_title: Aspose.PSD voor .NET API-referentie
description: FilterEffectMaskData eigendom. Haalt de GUID op.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/
---
## FilterEffectMaskData.GUID property

Haalt de GUID op.

```csharp
public string GUID { get; }
```

### Voorbeelden

Dit voorbeeld laat zien hoe u eigenschappen van de FXidResource-resource kunt ophalen en instellen.

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

// controleren na opslaan
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

### Zie ook

* class [FilterEffectMaskData](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* montage [Aspose.PSD](../../../)


