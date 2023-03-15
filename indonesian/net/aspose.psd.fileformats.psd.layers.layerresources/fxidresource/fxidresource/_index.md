---
title: FXidResource.FXidResource
second_title: Aspose.PSD untuk Referensi .NET API
description: FXidResource konstruktor. Menginisialisasi instance baru dariFXidResource kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Menginisialisasi instance baru dari[`FXidResource`](../) kelas.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| key | Int32 | Kunci sumber daya. |
| version | Int32 | Versi. |
| filterEffectMasks | FilterEffectMaskData[] | Masker efek filter. |

### Contoh

Contoh ini mendemonstrasikan cara mendapatkan dan mengatur properti sumber daya FXidResource.

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

// periksa setelah menyimpan
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

### Lihat juga

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* perakitan [Aspose.PSD](../../../)


