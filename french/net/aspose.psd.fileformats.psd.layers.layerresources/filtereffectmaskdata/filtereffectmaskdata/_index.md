---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Référence de l'API Aspose.PSD pour .NET
description: FilterEffectMaskData constructeur. Initialise une nouvelle instance duFilterEffectMaskData classe.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

Initialise une nouvelle instance du[`FilterEffectMaskData`](../) classe.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| guid | String | Le guide des ressources. |
| rectangle | Rectangle | Le rectangle des canaux. |
| pixelsDepth | Int32 | La profondeur de pixels. |
| maxChannels | Int32 | La valeur maximale des canaux. |
| channels | ChannelInformation[] | Les canaux. |
| userMask | ChannelInformation | Le masque utilisateur. |
| maskRectangle | Rectangle | Rectangle du masque de feuille. |
| sheetMask | ChannelInformation | Le masque en feuille. |

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
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* Assemblée [Aspose.PSD](../../../)


