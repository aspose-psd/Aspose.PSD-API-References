---
title: ShmdResource.SubResources
second_title: Справочник по Aspose.PSD для .NET API
description: ShmdResource свойство. Получает подресурсы shmd resource.
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Получает подресурсы shmd resource.

```csharp
public LayerResource[] SubResources { get; }
```

### Примеры

Следующий код демонстрирует поддержку ресурса MlstResource, который предоставляет низкоуровневый механизм для управления состояниями слоя.

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

    // Отключаем слой 1 на кадре 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Смотрите также

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* сборка [Aspose.PSD](../../../)


