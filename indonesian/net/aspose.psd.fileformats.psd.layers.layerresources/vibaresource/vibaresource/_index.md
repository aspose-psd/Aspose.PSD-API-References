---
title: "VibAResource.VibAResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor VibAResource. Menginisialisasi instance baru dari kelas VibAResource"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
{{< psd/tize >}}
## VibAResource constructor

Menginisialisasi instance baru dari kelas [`VibAResource`](../).

```csharp
public VibAResource()
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


