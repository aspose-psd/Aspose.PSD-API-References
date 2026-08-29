---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur FilterEffectMaskData. Initialise une nouvelle instance de la classe FilterEffectMaskData"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

Initialise une nouvelle instance de la classe [`FilterEffectMaskData`](../).

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| guid | String | Le guid de la ressource. |
| rectangle | Rectangle | Le rectangle des canaux. |
| pixelsDepth | Int32 | La profondeur des pixels. |
| maxChannels | Int32 | La valeur maximale des canaux. |
| channels | ChannelInformation[] | Les canaux. |
| userMask | ChannelInformation | Le masque utilisateur. |
| maskRectangle | Rectangle | Le rectangle du masque de feuille. |
| sheetMask | ChannelInformation | Le masque de feuille. |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


