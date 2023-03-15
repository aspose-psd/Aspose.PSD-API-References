---
title: Class WorkingPathResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource сорт. Ресурс рабочего пути.
type: docs
weight: 3980
url: /ru/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
## WorkingPathResource class

Ресурс рабочего пути.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | Инициализирует новый экземпляр`WorkingPathResource` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Строка Паскаля, дополненная, чтобы сделать размер четным (нулевое имя состоит из двух байтов 0). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | Получает или задает записи пути. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает подпись ресурса. Всегда должно быть «8BIM». |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурсов в байтах, включая его данные. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | Получает или задает версию. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурсов в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурсов. |

### Примеры

Этот пример демонстрирует поддержку ресурса WorkingPathResource в PsdImage.ImageResources для корректной работы операции Crop.

```csharp
[C#]

// Обрезать изображение и сохранить.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Поиск ресурса WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Обрезать и сохранить.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Загружаем сохраненное изображение и проверяем изменения.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Поиск ресурса WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### Смотрите также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* сборка [Aspose.PSD](../../)


