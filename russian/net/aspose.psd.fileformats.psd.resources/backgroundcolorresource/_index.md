---
title: "Класс BackgroundColorResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource класс. Ресурс с информацией о границе настроек печати изображения"
type: docs
weight: 4100
url: /ru/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
{{< psd/tize >}}
## BackgroundColorResource class

Ресурс с информацией о границе настроек печати изображения.

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | Получает или задает цвет фона. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Паскаль-строка, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает сигнатуру ресурса. Должна всегда быть '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурса в байтах, включая его данные. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурса в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурса. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


