---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Aspose.PSD untuk Referensi .NET API
description: FilterEffectMaskData konstruktor. Menginisialisasi instance baru dariFilterEffectMaskData kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

Menginisialisasi instance baru dari[`FilterEffectMaskData`](../) kelas.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| guid | String | Panduan sumber daya. |
| rectangle | Rectangle | Persegi panjang saluran. |
| pixelsDepth | Int32 | Kedalaman piksel. |
| maxChannels | Int32 | Nilai saluran maks. |
| channels | ChannelInformation[] | Saluran. |
| userMask | ChannelInformation | Masker pengguna. |
| maskRectangle | Rectangle | Persegi panjang lembar masker. |
| sheetMask | ChannelInformation | Masker lembar. |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* perakitan [Aspose.PSD](../../../)


