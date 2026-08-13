---
title: "FXidResource.FXidResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FXidResource yapıcı. FXidResource sınıfının yeni bir örneğini başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
{{< psd/tize >}}
## FXidResource constructor

[`FXidResource`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | Int32 | Kaynak anahtarı. |
| sürüm | Int32 | Sürüm. |
| filterEffectMasks | FilterEffectMaskData[] | Filtre etkisi maskeleri. |

## Örnekler

Bu örnek, FXidResource kaynağının özelliklerini nasıl alıp ayarlayacağını gösterir.

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

// kaydetme sonrası kontrol et
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

### Ayrıca Bakınız

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


