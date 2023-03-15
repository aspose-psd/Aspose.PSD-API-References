---
title: Class SoCoResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource kelas. Kelas SoCoResource. Sumber daya ini berisi informasi tentang Color Fill Layers
type: docs
weight: 3010
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

Kelas SoCoResource. Sumber daya ini berisi informasi tentang Color Fill Layers

```csharp
public class SoCoResource : FillLayerResource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [SoCoResource](socoresource/)() | Menginisialisasi instance baru dari`SoCoResource` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | Mendapatkan warna RGB . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | Mendapat tanda tangan sumber daya lapisan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke wadah aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | Kunci info alat ketik. |

### Contoh

Contoh berikut menunjukkan bagaimana Anda mengedit SoCoResource (Layer Resource for Color Fill Layer)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Menemukan FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Menemukan SoCoResource di Layer Resource List
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // Menyetel properti Warna SoCoResource
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Lihat juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


