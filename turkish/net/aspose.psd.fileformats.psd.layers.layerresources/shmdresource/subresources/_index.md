---
title: ShmdResource.SubResources
second_title: Aspose.PSD for .NET API Referansı
description: ShmdResource mülk. Shmd kaynağının alt kaynaklarını alır.
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Shmd kaynağının alt kaynaklarını alır.

```csharp
public LayerResource[] SubResources { get; }
```

### Örnekler

Aşağıdaki kod, katman durumlarını işlemek için düşük düzeyli bir mekanizma sağlayan MlstResource kaynağının desteğini gösterir.

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

    // 1. karede 1. katmanı devre dışı bırak
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Ayrıca bakınız

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* toplantı [Aspose.PSD](../../../)


