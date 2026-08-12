---
title: "ShmdResource.SubResources"
second_title: "Справочник API Aspose.PSD для .NET"
description: "ShmdResource свойство. Получает подресурсы ресурса shmd"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

Получает подресурсы ресурса shmd.

```csharp
public LayerResource[] SubResources { get; }
```

## Примеры

В следующем коде демонстрируется поддержка ресурса MlstResource, который предоставляет низкоуровневый механизм для управления состояниями слоев.

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

    // Отключить слой 1 на кадре 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### См. также

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


