---
title: "Класс BorderInformationResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource класс. Ресурс с информацией о границе настроек печати изображения"
type: docs
weight: 4110
url: /ru/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
{{< psd/tize >}}
## BorderInformationResource class

Ресурс с информацией о границе настроек печати изображения.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Паскаль-строка, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает сигнатуру ресурса. Должна всегда быть '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурса в байтах, включая его данные. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Получает или задает единицы границы. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Получает или задает ширину границы. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурса в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурса. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


