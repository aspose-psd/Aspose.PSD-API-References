---
title: Class VogkResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VogkResource kelas. Sumber Data Asal Vektor.
type: docs
weight: 3370
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
## VogkResource class

Sumber Data Asal Vektor.

```csharp
public sealed class VogkResource : LayerResource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [VogkResource](vogkresource/)() | Menginisialisasi instance baru dari`VogkResource` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/) { get; set; } | Mendapat atau menyetel pengaturan asal bentuk. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/signature/) { get; } | Mendapat tanda tangan sumber daya lapisan. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/) { get; set; } | Mendapatkan atau menyetel versi. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke wadah aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey/) | Kunci info alat ketik. |

### Contoh

Contoh berikut menunjukkan dukungan sumber daya VogkResource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // Membaca
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Mengedit
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Lihat juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


