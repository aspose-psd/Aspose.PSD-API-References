---
title: FilterEffectMaskData.Rectangle
second_title: Référence de l'API Aspose.PSD pour .NET
description: FilterEffectMaskData propriété. Obtient le rectangle des canaux.
type: docs
weight: 80
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/
---
## FilterEffectMaskData.Rectangle property

Obtient le rectangle des canaux.

```csharp
public Rectangle Rectangle { get; }
```

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [FilterEffectMaskData](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* Assemblée [Aspose.PSD](../../../)


