---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Aspose.PSD per riferimento API .NET
description: FilterEffectMaskData costruttore. Inizializza una nuova istanza diFilterEffectMaskData classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

Inizializza una nuova istanza di[`FilterEffectMaskData`](../) classe.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| guid | String | La guida alle risorse. |
| rectangle | Rectangle | Il rettangolo dei canali. |
| pixelsDepth | Int32 | La profondità dei pixel. |
| maxChannels | Int32 | Il valore massimo dei canali. |
| channels | ChannelInformation[] | I canali. |
| userMask | ChannelInformation | La maschera dell'utente. |
| maskRectangle | Rectangle | Il rettangolo della maschera del foglio. |
| sheetMask | ChannelInformation | La maschera in tessuto. |

### Esempi

Questo esempio dimostra come ottenere e impostare le proprietà della risorsa FXidResource.

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

// controlla dopo aver salvato
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

### Guarda anche

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* assemblea [Aspose.PSD](../../../)


