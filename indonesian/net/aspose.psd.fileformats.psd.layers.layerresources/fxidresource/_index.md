---
title: Class FXidResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FXidResource kelas. Sumber Filter Effects berisi saluran user mask dan sheet mask untuk smart filter.
type: docs
weight: 2460
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
## FXidResource class

Sumber Filter Effects berisi saluran, user mask, dan sheet mask untuk smart filter.

```csharp
public sealed class FXidResource : LayerResource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [FXidResource](fxidresource/)(int, int, FilterEffectMaskData[]) | Menginisialisasi instance baru dari`FXidResource` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [FilterEffectMasks](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/) { get; } | Mendapatkan masker efek filter. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/signature/) { get; } | Mendapat tanda tangan sumber daya lapisan. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/version/) { get; } | Mendapatkan versinya. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke wadah aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [FEidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/feidtypetoolkey/) | Kunci info alat jenis FEid. |
| const [FXidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidtypetoolkey/) | Kunci info alat tipe FXid. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


