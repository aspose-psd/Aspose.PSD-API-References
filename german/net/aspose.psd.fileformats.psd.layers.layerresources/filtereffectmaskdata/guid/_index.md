---
title: FilterEffectMaskData.GUID
second_title: Aspose.PSD für .NET-API-Referenz
description: FilterEffectMaskData eigendom. Ruft die GUID ab.
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/
---
## FilterEffectMaskData.GUID property

Ruft die GUID ab.

```csharp
public string GUID { get; }
```

### Beispiele

Dieses Beispiel zeigt, wie Eigenschaften der FXidResource-Ressource abgerufen und festgelegt werden.

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

// Nach dem Speichern prüfen
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

### Siehe auch

* class [FilterEffectMaskData](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* Montage [Aspose.PSD](../../../)


