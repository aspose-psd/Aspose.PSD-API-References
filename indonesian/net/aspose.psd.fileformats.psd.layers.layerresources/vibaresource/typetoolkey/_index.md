---
title: VibAResource.TypeToolKey
second_title: Aspose.PSD untuk Referensi .NET API
description: VibAResource bidang. Kunci info alat ketik.
type: docs
weight: 80
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/
---
## VibAResource.TypeToolKey field

Kunci info alat ketik.

```csharp
public const int TypeToolKey;
```

### Contoh

Contoh kode berikut menunjukkan dukungan sumber daya VibAResource.

```csharp
[C#]

// Contoh dukungan membaca dan menulis Sumber Daya Getaran saat runtime.
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

### Lihat juga

* class [VibAResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* perakitan [Aspose.PSD](../../../)


