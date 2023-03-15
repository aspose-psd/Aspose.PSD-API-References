---
title: FXidResource.FXidResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: FXidResource constructeur. Initialise une nouvelle instance duFXidResource classe.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Initialise une nouvelle instance du[`FXidResource`](../) classe.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| key | Int32 | La clé de ressource. |
| version | Int32 | La version. |
| filterEffectMasks | FilterEffectMaskData[] | Les masques d'effet de filtre. |

### Exemples

Cet exemple montre comment obtenir et définir les propriétés de la ressource FXidResource.

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

// vérification après sauvegarde
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

### Voir également

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* Assemblée [Aspose.PSD](../../../)


