---
title: "VogkResource.PsdVersion"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство VogkResource. Получает минимальную версию psd, требуемую для ресурса слоя. 0 указывает отсутствие ограничений"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/
---
{{< psd/tize >}}
## VogkResource.PsdVersion property

Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений.

```csharp
public override int PsdVersion { get; }
```

## Примеры

Следующий пример демонстрирует поддержку ресурса VogkResource.

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

### См. также

* class [VogkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


