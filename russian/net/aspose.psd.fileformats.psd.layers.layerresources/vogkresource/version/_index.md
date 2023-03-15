---
title: VogkResource.Version
second_title: Справочник по Aspose.PSD для .NET API
description: VogkResource свойство. Получает или задает версию.
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/
---
## VogkResource.Version property

Получает или задает версию.

```csharp
public int Version { get; set; }
```

### Стоимость имущества

Версия.

### Примеры

В следующем примере демонстрируется поддержка ресурса VogkResource.

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

    // Чтение
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Редактирование
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Смотрите также

* class [VogkResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* сборка [Aspose.PSD](../../../)


