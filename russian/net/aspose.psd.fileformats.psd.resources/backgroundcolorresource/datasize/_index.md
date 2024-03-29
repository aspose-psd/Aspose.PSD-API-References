---
title: BackgroundColorResource.DataSize
second_title: Справочник по Aspose.PSD для .NET API
description: BackgroundColorResource свойство. Получает размер данных ресурса в байтах.
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

Получает размер данных ресурса в байтах.

```csharp
public override int DataSize { get; }
```

### Стоимость имущества

Размер данных ресурса.

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


