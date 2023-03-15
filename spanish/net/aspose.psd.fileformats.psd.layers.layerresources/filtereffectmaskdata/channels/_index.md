---
title: FilterEffectMaskData.Channels
second_title: Referencia de API de Aspose.PSD para .NET
description: FilterEffectMaskData propiedad. Obtiene los canales.
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/
---
## FilterEffectMaskData.Channels property

Obtiene los canales.

```csharp
public ChannelInformation[] Channels { get; }
```

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

* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* asamblea [Aspose.PSD](../../../)


