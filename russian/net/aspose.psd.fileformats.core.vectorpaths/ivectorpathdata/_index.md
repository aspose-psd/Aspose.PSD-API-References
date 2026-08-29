---
title: "Интерфейс IVectorPathData"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData интерфейс. Интерфейс для доступа к данным векторного пути"
type: docs
weight: 1360
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
{{< psd/tize >}}
## IVectorPathData interface

Интерфейс доступа к данным векторного пути.

```csharp
public interface IVectorPathData
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Получает или задает записи пути. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Получает или задает версию. |

## Примеры

Этот пример демонстрирует поддержку ресурса 'WorkingPathResource' в PsdImage.ImageResources для корректной работы операции обрезки.

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

// Загрузить сохранённое изображение и проверить изменения.
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

### См. также

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


