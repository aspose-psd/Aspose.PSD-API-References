---
title: FXidResource.FXidResource
second_title: Referencia de API de Aspose.PSD para .NET
description: FXidResource constructor. Inicializa una nueva instancia delFXidResource clase.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Inicializa una nueva instancia del[`FXidResource`](../) clase.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| key | Int32 | La clave del recurso. |
| version | Int32 | La versión. |
| filterEffectMasks | FilterEffectMaskData[] | El efecto de filtro enmascara. |

### Ejemplos

Este ejemplo demuestra cómo obtener y establecer propiedades del recurso FXidResource.

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

// comprobar después de guardar
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

### Ver también

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* asamblea [Aspose.PSD](../../../)


