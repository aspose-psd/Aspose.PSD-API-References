---
title: FXidResource.FXidResource
second_title: Aspose.PSD voor .NET API-referentie
description: FXidResource constructeur. Initialiseert een nieuw exemplaar van hetFXidResource klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Initialiseert een nieuw exemplaar van het[`FXidResource`](../) klasse.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | Int32 | De bronsleutel. |
| version | Int32 | De versie. |
| filterEffectMasks | FilterEffectMaskData[] | De filtereffectmaskers. |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* montage [Aspose.PSD](../../../)


