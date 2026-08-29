---
title: "BackgroundColorResource.DataSize"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство BackgroundColorResource. Возвращает размер данных ресурса в байтах"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

Получает размер данных ресурса в байтах.

```csharp
public override int DataSize { get; }
```

### Property Value

Размер данных ресурса.

## Примеры

Следующий пример демонстрирует поддержку ресурса BackgroundColorResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // обновить BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### См. также

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


