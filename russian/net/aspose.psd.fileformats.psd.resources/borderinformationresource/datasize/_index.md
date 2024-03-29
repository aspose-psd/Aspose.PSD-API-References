---
title: BorderInformationResource.DataSize
second_title: Справочник по Aspose.PSD для .NET API
description: BorderInformationResource свойство. Получает размер данных ресурса в байтах.
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
## BorderInformationResource.DataSize property

Получает размер данных ресурса в байтах.

```csharp
public override int DataSize { get; }
```

### Стоимость имущества

Размер данных ресурса.

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


