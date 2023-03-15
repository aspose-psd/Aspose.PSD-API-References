---
title: BackgroundColorResource.MinimalVersion
second_title: Справочник по Aspose.PSD для .NET API
description: BackgroundColorResource свойство. Получает минимальную требуемую версию PSD.
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Получает минимальную требуемую версию PSD.

```csharp
public override int MinimalVersion { get; }
```

### Стоимость имущества

Минимальная версия PSD.

### Примеры

В следующем примере демонстрируется поддержка ресурса BackgroundColorResource.

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

### Смотрите также

* class [BackgroundColorResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* сборка [Aspose.PSD](../../../)


