---
title: "BorderInformationResource.MinimalVersion"
second_title: "Справочник API Aspose.PSD для .NET"
description: "BorderInformationResource свойство. Получает минимальную требуемую версию PSD"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
{{< psd/tize >}}
## BorderInformationResource.MinimalVersion property

Получает минимальную требуемую версию PSD.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Минимальная версия PSD.

## Примеры

Следующий пример демонстрирует поддержку ресурса BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // обновить BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### См. также

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


