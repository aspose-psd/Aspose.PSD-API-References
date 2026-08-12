---
title: "IVectorPathData.Version"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство IVectorPathData. Возвращает или задает версию."
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/
---
{{< psd/tize >}}
## IVectorPathData.Version property

Получает или задает версию.

```csharp
public int Version { get; set; }
```

### Property Value

Версия.

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

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


