---
title: SoCoResource.Color
second_title: Aspose.PSD untuk Referensi .NET API
description: SoCoResource Properti. Mendapatkan warna RGB .
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

Mendapatkan warna RGB .

```csharp
public Color Color { get; set; }
```

### Nilai Pengembalian

Warna RGB

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

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* perakitan [Aspose.PSD](../../../)


