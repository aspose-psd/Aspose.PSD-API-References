---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство BackgroundColorResource. Возвращает минимально требуемую версию PSD"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Получает минимальную требуемую версию PSD.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Минимальная версия PSD.

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


