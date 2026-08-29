---
title: "BorderInformationResource.DataSize"
second_title: "Справочник API Aspose.PSD для .NET"
description: "BorderInformationResource свойство. Получает размер данных ресурса в байтах"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
{{< psd/tize >}}
## BorderInformationResource.DataSize property

Получает размер данных ресурса в байтах.

```csharp
public override int DataSize { get; }
```

### Property Value

Размер данных ресурса.

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


