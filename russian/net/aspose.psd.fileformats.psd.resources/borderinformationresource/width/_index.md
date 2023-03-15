---
title: BorderInformationResource.Width
second_title: Справочник по Aspose.PSD для .NET API
description: BorderInformationResource свойство. Получает или задает ширину границы.
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
## BorderInformationResource.Width property

Получает или задает ширину границы.

```csharp
public double Width { get; set; }
```

### Примеры

В следующем примере демонстрируется поддержка ресурса BorderInformationResource.

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

### Смотрите также

* class [BorderInformationResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* сборка [Aspose.PSD](../../../)


