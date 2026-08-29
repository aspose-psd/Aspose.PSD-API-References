---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "FilterEffectMaskData konstruktor. Menginisialisasi instance baru dari kelas FilterEffectMaskData"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

Menginisialisasi instance baru dari kelas [`FilterEffectMaskData`](../).

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| guid | String | GUID sumber daya. |
| persegi panjang | Rectangle | Persegi saluran. |
| pixelsDepth | Int32 | Kedalaman piksel. |
| maxChannels | Int32 | Nilai maksimum saluran. |
| channels | ChannelInformation[] | Saluran. |
| userMask | ChannelInformation | Masker pengguna. |
| maskRectangle | Rectangle | Segi empat topeng lembar. |
| sheetMask | ChannelInformation | Topeng lembar. |

## Contoh

Contoh ini menunjukkan cara mendapatkan dan mengatur properti dari sumber daya FXidResource.

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

### Lihat Juga

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


