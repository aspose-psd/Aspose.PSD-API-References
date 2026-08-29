---
title: "VibAResource.Saturation"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti VibAResource. Mengambil atau mengatur nilai saturasi"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/
---
{{< psd/tize >}}
## VibAResource.Saturation property

Mendapatkan atau mengatur nilai saturasi

```csharp
public int Saturation { get; set; }
```

## Contoh

Contoh kode berikut menunjukkan dukungan sumber daya VibAResource.

```csharp
[C#]

// Contoh dukungan membaca dan menulis Sumber Daya Getaran pada waktu berjalan.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Lihat Juga

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


