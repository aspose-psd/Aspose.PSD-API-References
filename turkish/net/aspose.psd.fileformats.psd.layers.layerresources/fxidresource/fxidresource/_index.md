---
title: FXidResource.FXidResource
second_title: Aspose.PSD for .NET API Referansı
description: FXidResource inşaatçı. Yeni bir örneğini başlatır.FXidResource sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Yeni bir örneğini başlatır.[`FXidResource`](../) sınıf.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| key | Int32 | kaynak anahtarı. |
| version | Int32 | Sürüm. |
| filterEffectMasks | FilterEffectMaskData[] | Filtre efekti maskeleri. |

### Örnekler

Bu örnek, FXidResource kaynağının özelliklerinin nasıl alınacağını ve ayarlanacağını gösterir.

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

// kaydettikten sonra kontrol edin
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

### Ayrıca bakınız

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* toplantı [Aspose.PSD](../../../)


