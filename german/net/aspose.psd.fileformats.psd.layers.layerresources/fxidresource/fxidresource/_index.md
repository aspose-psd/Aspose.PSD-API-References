---
title: FXidResource.FXidResource
second_title: Aspose.PSD für .NET-API-Referenz
description: FXidResource constructeur. Initialisiert eine neue Instanz vonFXidResource Klasse.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Initialisiert eine neue Instanz von[`FXidResource`](../) Klasse.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | Int32 | Der Ressourcenschlüssel. |
| version | Int32 | Die Version. |
| filterEffectMasks | FilterEffectMaskData[] | Die Filtereffektmasken. |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* Montage [Aspose.PSD](../../../)


