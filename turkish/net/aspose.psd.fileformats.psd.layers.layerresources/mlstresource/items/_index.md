---
title: "MlstResource.Items"
second_title: "Aspose.PSD for .NET API Referansı"
description: "MlstResource özelliği. Yapıları alır veya ayarlar"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

Yapıları alır veya ayarlar.

```csharp
public OSTypeStructure[] Items { get; }
```

## Örnekler

Aşağıdaki kod, katman durumlarını manipüle etmek için düşük seviyeli bir mekanizma sağlayan MlstResource kaynağının desteğini gösterir.

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

    // Çerçeve 1'de katman 1'i devre dışı bırak
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Ayrıca Bakınız

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


