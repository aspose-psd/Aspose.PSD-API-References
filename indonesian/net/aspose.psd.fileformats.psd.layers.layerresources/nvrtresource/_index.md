---
title: "Kelas NvrtResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource. Kelas NvrtResource. Sumber daya dari Lapisan Penyesuaian Invert"
type: docs
weight: 3180
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
{{< psd/tize >}}
## NvrtResource class

Kelas NvrtResource. Sumber daya Lapisan Penyesuaian Invert.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Menginisialisasi instance baru dari kelas `NvrtResource`. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Menginisialisasi instance baru dari kelas `NvrtResource`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | Kunci info alat tipe. |

## Contoh

Contoh berikut menunjukkan cara mendapatkan NvrtResource.

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // NvrtResource didukung.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### Lihat Juga

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


