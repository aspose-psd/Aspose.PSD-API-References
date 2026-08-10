---
title: "MlstResource.Items"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "MlstResource properti. Mendapatkan atau mengatur struktur"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

Mendapatkan atau mengatur struktur.

```csharp
public OSTypeStructure[] Items { get; }
```

## Contoh

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

    // Nonaktifkan lapisan 1 pada frame 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Lihat Juga

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


