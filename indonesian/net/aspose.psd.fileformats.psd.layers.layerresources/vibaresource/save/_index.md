---
title: "VibAResource.Save"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "VibAResource metode. Menyimpan sumber daya ke kontainer aliran yang ditentukan"
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | StreamContainer | Stream container untuk disimpan. |
| psdVersion | Int32 | Versi PSD. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


