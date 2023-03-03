---
title: BackgroundColorResource.Color
second_title: Справочник по Aspose.PSD для .NET API
description: BackgroundColorResource свойство. Получает или задает цвет фона.
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Получает или задает цвет фона.

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* сборка [Aspose.PSD](../../../)


