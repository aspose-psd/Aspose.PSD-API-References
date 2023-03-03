---
title: ShmdResource.SubResources
second_title: Aspose.PSD untuk Referensi .NET API
description: ShmdResource Properti. Mendapatkan sub resource dari shmd resource.
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Mendapatkan sub resource dari shmd resource.

```csharp
public LayerResource[] SubResources { get; }
```

### Contoh

Kode berikut menunjukkan dukungan sumber daya MlstResource yang memberikan mekanisme tingkat rendah untuk memanipulasi status lapisan.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Nonaktifkan layer 1 pada frame 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Lihat juga

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* perakitan [Aspose.PSD](../../../)


