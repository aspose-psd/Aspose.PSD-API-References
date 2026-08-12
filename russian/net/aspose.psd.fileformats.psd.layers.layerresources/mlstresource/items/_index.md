---
title: "MlstResource.Items"
second_title: "Справочник API Aspose.PSD для .NET"
description: "MlstResource свойство. Получает или задает структуры"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

Получает или задает структуры.

```csharp
public OSTypeStructure[] Items { get; }
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

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


