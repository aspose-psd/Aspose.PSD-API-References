---
title: FXidResource.FXidResource
second_title: Aspose.PSD per riferimento API .NET
description: FXidResource costruttore. Inizializza una nuova istanza diFXidResource classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Inizializza una nuova istanza di[`FXidResource`](../) classe.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | Int32 | La chiave della risorsa. |
| version | Int32 | La versione. |
| filterEffectMasks | FilterEffectMaskData[] | Le maschere effetto filtro. |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* assemblea [Aspose.PSD](../../../)


