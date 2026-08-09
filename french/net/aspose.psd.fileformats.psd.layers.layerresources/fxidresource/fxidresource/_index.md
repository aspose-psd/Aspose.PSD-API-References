---
title: "FXidResource.FXidResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur FXidResource. Initialise une nouvelle instance de la classe FXidResource"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
{{< psd/tize >}}
## FXidResource constructor

Initialise une nouvelle instance de la classe [`FXidResource`](../).

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| clé | Int32 | La clé de ressource. |
| version | Int32 | La version. |
| filterEffectMasks | FilterEffectMaskData[] | Les masques d'effet de filtre. |

## Exemples

Cet exemple montre comment obtenir et définir les propriétés de la ressource FXidResource.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

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

// vérifier après l'enregistrement
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

### Voir aussi

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


